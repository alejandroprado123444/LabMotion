# LabMotion — Laboratorio Virtual de Roce Estático y Dinámico

**LabMotion** es una aplicación web progresiva (Web App responsiva) diseñada para estudiantes universitarios de primer año de ingeniería y ciencias[span_0](start_span)[span_0](end_span)[span_1](start_span)[span_1](end_span). Transforma los sensores inerciales de un smartphone (giroscopio y acelerómetro) en un instrumento de medición de laboratorio para determinar experimentalmente los coeficientes de roce estático ($\mu_s$) y dinámico ($\mu_k$) sobre un plano inclinado[span_2](start_span)[span_2](end_span)[span_3](start_span)[span_3](end_span).

🔗 **Acceso directo a la Web App:** [https://fabulous-quokka-d2b4e9.netlify.app/](https://fabulous-quokka-d2b4e9.netlify.app/)

---

## 👥 Equipo y Roles Asignados

| Integrante | Rol Principal | Responsabilidades Clave |
| :--- | :--- | :--- |
| **Isidora González** | Product Owner / Responsable Científica | Definición del modelo físico, validación de ecuaciones y protocolos experimentales (5 repeticiones por superficie)[span_4](start_span)[span_4](end_span)[span_5](start_span)[span_5](end_span)[span_6](start_span)[span_6](end_span). |
| **Rashmi Abdelrahman** | Software / Datos / UX | Adquisición de sensores (`DeviceOrientation` / `DeviceMotion`), filtro de promedio móvil, motor de cálculo y exportación CSV[span_7](start_span)[span_7](end_span)[span_8](start_span)[span_8](end_span). |
| **Josefa Mondaca** | Hardware / Instrumentación / UX | Diseño y construcción de rampa articulada ($0^\circ - 45^\circ$), superficies intercambiables y diseño de interfaz responsiva[span_9](start_span)[span_9](end_span)[span_10](start_span)[span_10](end_span)[span_11](start_span)[span_11](end_span)[span_12](start_span)[span_12](end_span). |
| **Alejandro Prado** | Pedagógico / Científico | Diseño de la guía experimental del estudiante (Módulo 6), tablas de análisis y documentación técnica[span_13](start_span)[span_13](end_span)[span_14](start_span)[span_14](end_span)[span_15](start_span)[span_15](end_span). |

---

## 🔬 Fundamento Físico Implementado

1. **Coeficiente de Roce Estático ($\mu_s$):** Se calcula en el instante exacto en que el acelerómetro detecta el inicio del deslizamiento al alcanzar el ángulo crítico $\theta_c$[span_16](start_span)[span_16](end_span)[span_17](start_span)[span_17](end_span)[span_18](start_span)[span_18](end_span):
   $$\mu_s = \tan(\theta_c)$$

2. **Coeficiente de Roce Dinámico ($\mu_k$):** Se determina durante el descenso acelerado del dispositivo sobre la rampa a partir del ángulo $\theta$ y la aceleración lineal $a$[span_19](start_span)[span_19](end_span)[span_20](start_span)[span_20](end_span)[span_21](start_span)[span_21](end_span):
   $$\mu_k = \tan(\theta) - \frac{a}{g \cdot \cos(\theta)}$$

---

## 🚀 Instrucciones de Uso e Instalación

### Opción A: Uso directo en línea (Recomendado)
1. Ingresa desde el navegador de tu smartphone (Chrome o Safari) a: **[https://fabulous-quokka-d2b4e9.netlify.app/](https://fabulous-quokka-d2b4e9.netlify.app/)** *(requiere conexión segura HTTPS para habilitar permisos de sensores).*
2. Selecciona **Sensores del Móvil** y presiona **"Conectar Sensores del Teléfono"** otorgando los permisos solicitados[span_22](start_span)[span_22](end_span). *(Si no dispones de rampa física, selecciona **Modo Simulador**)[span_23](start_span)[span_23](end_span).*
3. Elige la superficie de prueba (**Madera**, **Lija** o **Goma EVA**), apoya el celular horizontalmente y presiona **"Calibrar a 0°"**[span_24](start_span)[span_24](end_span).
4. Presiona **"Iniciar Captura"**, eleva la rampa suavemente hasta que el teléfono deslice y revisa los gráficos en tiempo real[span_25](start_span)[span_25](end_span).
5. Presiona **"Exportar Registro CSV"** para descargar los datos del ensayo[span_26](start_span)[span_26](end_span).

### Opción B: Ejecución local
1. Clona este repositorio:
   ```bash
   git clone [https://github.com/](https://github.com/)<tu-usuario>/<tu-repositorio>.git
