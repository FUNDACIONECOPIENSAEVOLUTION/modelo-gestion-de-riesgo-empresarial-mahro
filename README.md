# MAHRO — Gestión empresarial del riesgo

Prototipo web estático para explorar la integración del **Sistema de Comando de Incidentes (SCI)**, la **gobernanza de crisis** y la **continuidad del negocio** dentro del Modelo Administrativo Híbrido de Resiliencia Organizacional (MAHRO).

## Sitio

La página principal está en `index.html`. Con GitHub Pages habilitado para la rama `main` y la carpeta raíz, se publica en:

https://fundacionecopiensaevolution.github.io/modelo-gestion-de-riesgo-empresarial-mahro/

El HTML contiene su CSS y JavaScript; no requiere instalación, compilación, dependencias ni servicios externos. El archivo previo `index2.html` se conserva sin cambios.

## Módulos del prototipo

- Resumen de los tres componentes MAHRO.
- Contexto del incidente y periodo operacional.
- Objetivos tácticos, recursos y bitácora.
- Conteo agregado de personas afectadas, sin nombres ni datos médicos.
- Procesos críticos y estado de continuidad.
- Funciones del comité de crisis, enlaces externos y registro de decisiones.
- Impresión y respaldo de datos en JSON.

## Datos y alcance

Los datos se guardan en el almacenamiento local del navegador desde el que se usa la página. No se sincronizan con otras personas ni se envían a un servidor. Usa **Exportar** para crear un respaldo JSON y **Importar respaldo** para recuperarlo en ese navegador.

Esta versión es demostrativa y sirve para revisión, planeación y ejercicios. No ofrece GPS en vivo, despacho de recursos, coordinación multiusuario, autenticación ni almacenamiento central. No es un sistema operativo de respuesta a emergencias ni reemplaza los planes aprobados, las responsabilidades legales o los protocolos de las autoridades competentes. No registres datos personales, información médica identificable, credenciales ni información sensible de la empresa.

## Fuentes del proyecto

- [Tablero SCI de referencia](https://instructorandradedcc.github.io/modelo-sci-dcc/)
- [Propuesta MAHRO](https://instructorandradedcc.github.io/PROPUESTA-MAHRO/)
- [Propuestas doctorales](https://instructorandradedcc.github.io/propuesta-doctoral-administraci-n-uniandes/)

## Publicación

Si GitHub Pages aún no está activo para la raíz de `main`, en **Settings → Pages** selecciona **Deploy from a branch**, la rama `main` y la carpeta `/(root)`. GitHub Pages publica el `index.html` raíz después de procesar el commit.
