# Guía de Laboratorio: Estudio Experimental del Roce Estático y Dinámico con LabMotion

**Asignatura:** Física Mecánica (Primer Año Universitario)  
**Herramienta:** Web App LabMotion (`https://fabulous-quokka-d2b4e9.netlify.app/`)  
**Modalidad:** Aprendizaje basado en indagación (Ciclo PREDICCIÓN → EXPERIMENTACIÓN → ANÁLISIS)

---

## 1. Objetivos de Aprendizaje
* Determinar experimentalmente el coeficiente de roce estático ($\mu_s$) a partir del ángulo crítico de deslizamiento ($\theta_c$).
* Calcular el coeficiente de roce dinámico ($\mu_k$) midiendo la aceleración lineal durante el descenso sobre un plano inclinado.
* Comparar el comportamiento tribológico de tres superficies distintas (**Madera**, **Lija** y **Goma EVA**) y evaluar la repetibilidad experimental.

---

## 2. Materiales Necesarios
* Smartphone con navegador actualizado (Chrome o Safari) y sensores inerciales activos (o uso en *Modo Simulador*).
* Rampa articulada graduable ($0^\circ - 45^\circ$) con tope de seguridad acolchado en el extremo inferior.
* Tres láminas intercambiables: **Madera**, **Lija** y **Goma EVA**.
* Funda o soporte plano antideslizante para asegurar el contacto uniforme del teléfono.

---

## 3. Fase 1: Predicción (Antes de medir)
Antes de encender la aplicación, responde en tu equipo:
1. Ordena de menor a mayor los tres materiales (**Madera**, **Lija**, **Goma EVA**) según cuál crees que tendrá mayor coeficiente de roce estático ($\mu_s$). Justifica tu hipótesis.
2. Si duplicas el ángulo de inclinación una vez iniciado el movimiento, ¿qué ocurrirá con el valor de $\mu_k$? ¿Cambiará o se mantendrá constante?

---

## 4. Fase 2: Procedimiento Experimental (Paso a Paso)
1. **Ingreso:** Abre `https://fabulous-quokka-d2b4e9.netlify.app/` desde el navegador de tu teléfono.
2. **Conexión:** Selecciona **Sensores del Móvil** y presiona **"Conectar Sensores del Teléfono"** otorgando los permisos de movimiento/orientación *(si no cuentas con rampa física, selecciona **Modo Simulador**)*.
3. **Selección de superficie:** Elige **Madera** en el menú desplegable de superficie de prueba.
4. **Calibración:** Apoya el smartphone completamente horizontal sobre la base ($0^\circ$) y presiona **"Calibrar a 0°"**.
5. **Captura de datos:** Coloca el teléfono en la parte superior de la rampa inclinable, presiona **"Iniciar Captura"** y eleva el plano suavemente hasta que el dispositivo comience a deslizar y llegue al tope inferior.
6. **Repetición:** Repite el ensayo **5 veces** para la misma superficie para asegurar validez estadística.
7. **Cambio de material:** Cambia la lámina a **Lija** y luego a **Goma EVA**, repitiendo los pasos 3 al 6 para cada una.
8. **Exportación:** Presiona **"Exportar Registro CSV"** para descargar todos los datos recopilados.

---

## 5. Fase 3: Registro de Resultados y Análisis

### Tabla 1: Resumen de Mediciones Experimentales (5 repeticiones por superficie)

| Superficie | $\theta_c$ Promedio ($^\circ$) | $\mu_s$ Promedio ($\tan \theta_c$) | Desviación Estándar $\sigma(\mu_s)$ | $\mu_k$ Promedio | Desviación Estándar $\sigma(\mu_k)$ |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Madera** | | | | | |
| **Lija** | | | | | |
| **Goma EVA** | | | | | |

### Preguntas de Análisis y Cierre
1. **Contrastación:** ¿Coincidió el orden experimental de $\mu_s$ con tu predicción inicial? Explica cualquier diferencia observada.
2. **Relación física:** En todas tus mediciones, ¿se cumple que $\mu_s > \mu_k$? Fundamenta físicamente por qué cuesta más iniciar el movimiento que mantenerlo.
3. **Fuentes de error:** Identifica dos factores experimentales (ej. velocidad al levantar la rampa, vibraciones o rugosidad no uniforme) que expliquen la dispersión entre tus 5 repeticiones.
