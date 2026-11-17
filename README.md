# 📊 Panel de Control y Métricas Pro (v4.1.1)

Consola inteligente de monitorización académica y rendimiento personal con motor NLP local, memoria temporal evolutiva, sistema Pomodoro integrado y verificación de integridad criptográfica. 100% gratuito, sin suscripciones y de código abierto (Licencia MIT).

---

## 🚀 Modalidades de Uso

Este proyecto está diseñado para adaptarse a cualquier entorno con un único código base:

* **🌐 Versión Web (Siempre actualizada):** Accede directamente desde el navegador de tu ordenador o móvil a través de [GitHub Pages / Repositorio](https://github.com/JUAN3000-CMD/panel-metricas). Se actualiza automáticamente y cuenta con detección de versiones remota.
* **💻 Versión Local / Portable (Escritorio Offline):** *(⚠️ EN DESARROLLO, PRÓXIMAMENTE ⚠️)* Descarga el paquete ejecutable desde la sección Releases para llevarlo en una memoria USB o usarlo sin conexión a internet.
* **🛠️ Código Fuente (Educativo):** Clona o descarga este repositorio para estudiar su funcionamiento, modificarlo o adaptarlo a tus necesidades bajo los términos de la **Licencia MIT**.

---

## ✨ Características Principales

* **Gestión Dinámica de Categorías y Ponderaciones:** Crea tus propias asignaturas o áreas, añade calificaciones parciales con pesos configurables (x1, x2, x3) y visualiza el promedio ponderado en tiempo real.
* **🧠 Asistente Pro NLP Local:**
  * Basado en `Compromise.js` y similitud del coseno (TF-IDF) ejecutado íntegramente en tu navegador, sin enviar datos a servidores externos.
  * **Memoria Evolutiva (4 meses):** Pídele que recuerde fechas o datos (*"recuerda que el examen es el viernes"*). Los recuerdos se mantienen activos durante 120 días y luego pasan automáticamente a referencia histórica compacta.
  * Simulador de impacto de notas, consejos de estudio y modo No Molestar (DND).
* **⏱️ Temporizador Pomodoro Configurable:** Ciclos de estudio, descanso corto y descanso largo personalizables mediante un panel estético con avisos integrados.
* **📅 Agenda y Calendario:** Registro ordenado de exámenes y entregas pendientes.
* **📊 Visualización y Reportes PDF:** Gráficas comparativas por categoría, evolución histórica y exportación directa a documento PDF profesional (`html2pdf.js`) con renderizado optimizado.
* **🔒 Copias de Seguridad Firmadas (SHA-256):** Exportación e importación de datos en formato `.json` con firma digital de integridad para evitar archivos corruptos o manipulados.
* **📱 Diseño Adaptable (Responsive) y Modo Oscuro:** Interfaz optimizada para pantallas de escritorio, tablets y teléfonos móviles con transiciones fluidas.

---

## 📖 Guía Rápida

1. **Configura tus categorías:** Pulsa en *⚙️ Gestionar Categorías* para añadir el código y nombre de tus asignaturas o métricas.
2. **Define tus metas:** Ajusta el *Umbral Objetivo* y la *Meta de Categorías* desde las tarjetas superiores utilizando los nuevos modales flotantes.
3. **Guarda tus avances:** Aunque los datos se conservan automáticamente en el almacenamiento local del navegador (`localStorage`), utiliza el botón *💾 Exportar* para descargar una copia de seguridad en `.json` firmada criptográficamente.

---

## 🔄 Política de Versiones

* Las actualizaciones de interfaz y nuevas funcionalidades se publican de forma continua en la rama `main` (versión Web) y se empaquetan periódicamente en GitHub Releases.
* Las versiones anteriores estables permanecen disponibles en Releases para garantizar la retrocompatibilidad.

---

## 📄 Licencia

Este proyecto se distribuye bajo los términos y condiciones de la **Licencia MIT**. Eres libre de usarlo, modificarlo y compartirlo.
