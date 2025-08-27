# 🚀 Taller de Pruebas de Software - SIS-FP

## 📝 Descripción del Proyecto

Este repositorio contiene la **Landing Page** desarrollada como parte del taller de pruebas de software, enfocado en el análisis y la demostración de la calidad del sistema **SIS-FP (Sistema de Integración y Seguridad Portuaria)**.

El objetivo principal de esta página es documentar el proceso del taller, desde la teoría de las pruebas hasta una demostración práctica con la herramienta **Apache Jmeter**.

---

## ✨ Características Principales

* **Página de Portada:** Información del aprendiz y una introducción al taller.
* **Fundamentos de Pruebas:** Resumen de los principales tipos de pruebas de software (Funcionales, de Rendimiento, Usabilidad y Seguridad).
* **Análisis para SIS-FP:** Recomendaciones de pruebas específicas para el sistema, enfocadas en la seguridad y el rendimiento.
* **Demostración con Jmeter:** Un resumen detallado de una prueba de inicio de sesión realizada con Jmeter, validando el correcto funcionamiento del *endpoint* de autenticación.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Para la estructura de la página.
* **CSS3:** Para el diseño y estilo visual.
* **Jmeter:** Herramienta de código abierto para pruebas de carga y rendimiento.

---

## 📈 Resultado de la Prueba de Carga (Jmeter)

Se realizó una **prueba de carga** con 6 usuarios virtuales simulando inicios de sesión simultáneos en el *endpoint* de login del backend de SIS-FP.

### Resumen de la prueba:
- **Tipo de prueba:** Pruebas de Carga (Validación de concurrencia en el login).
- **Herramienta:** Apache Jmeter.
- **Resultado:** La prueba fue **completamente exitosa**, obteniendo un código de respuesta **200 (OK)** en todas las 6 solicitudes. Esto confirma que el servicio de autenticación soporta la carga de usuarios concurrentes de manera eficiente.


---

## 👨‍🎓 Información del Aprendiz

* **Nombre:** Jhon Jairo Mejia Avila
* **Curso/Ficha:** Aprendiz en Desarrollo y Analisis de Software - Ficha 2885525
* **Institución:** SENA
* **Enlace de la Landing Page:** (https://jjmejiaavila.github.io/taller-pruebas-sena/)