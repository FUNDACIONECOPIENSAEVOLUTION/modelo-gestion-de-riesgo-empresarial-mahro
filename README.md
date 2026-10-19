# MAHRO — Adaptabilidad empresarial y resiliencia organizacional

Prototipo web estático del **Modelo Administrativo Híbrido de Resiliencia Organizacional (MAHRO)**. Está pensado para que cada empresa adapte funciones, cargos, responsables y flujos a su estructura y capacidad. El Sistema de Comando de Incidentes se integra como referencia táctica; no es el nombre del sistema.

## Sitio

La página principal está en `index.html`. Con GitHub Pages habilitado para la rama `main` y la carpeta raíz, se publica en:

https://fundacionecopiensaevolution.github.io/modelo-gestion-de-riesgo-empresarial-mahro/

El sitio no requiere instalación, compilación, dependencias ni servicios externos para sus funciones principales.

## Módulos

- Resumen de la integración MAHRO: respuesta táctica, gobernanza de crisis y continuidad del negocio.
- Centro de comando: contexto del incidente, periodo operacional, bitácora y decisiones.
- Operación MAHRO: objetivos, recursos, conteo agregado de personas, mapa de sede y acciones por fase, prioridad y responsable.
- Directorio editable de funciones y cargos empresariales, precargado con equivalencias de la propuesta MAHRO.
- Continuidad: procesos críticos, responsables, prioridades y alternativas de recuperación.
- Gobernanza: comité de crisis, enlaces externos y decisiones estratégicas.
- Modelo MAHRO: gráfico de adaptación empresarial, organigrama empresarial redibujado en `assets/mahro-organigrama-empresa.png` y flujo integrado.
- Fundamento y método: explica la investigación cualitativa de casos múltiples para la propuesta 1.A y la metodología mixta y participativa de la propuesta 1.B.
- Propuestas: presenta las dos escalas de investigación —intraempresarial e interorganizacional— y su relevancia ante el sismo del 10 de agosto de 2026, con enlaces a fuentes oficiales.
- Impresión y respaldo JSON para exportar o importar datos.

## Datos y alcance

Los datos de operación, cargos, plano y marcas se guardan en el almacenamiento local del navegador. No se sincronizan entre usuarios ni se envían a un servidor. Usa **Exportar** para descargar un respaldo JSON y **Importar respaldo** para recuperarlo en ese navegador.

Esta versión es demostrativa y sirve para revisión, planeación y ejercicios. No ofrece GPS en vivo, despacho de recursos, coordinación multiusuario, autenticación ni almacenamiento central. No reemplaza los planes aprobados, las responsabilidades legales ni los protocolos de las autoridades competentes. No registres datos médicos identificables, credenciales ni información sensible de la empresa.

## Fuentes del proyecto

- [Tablero SCI de referencia](https://instructorandradedcc.github.io/modelo-sci-dcc/)
- [Propuesta MAHRO](https://instructorandradedcc.github.io/PROPUESTA-MAHRO/)
- [Propuestas doctorales y organigrama adaptado](https://instructorandradedcc.github.io/propuesta-doctoral-administraci-n-uniandes/)

## Publicación

Si GitHub Pages aún no está activo para la raíz de `main`, en **Settings → Pages** selecciona **Deploy from a branch**, la rama `main` y la carpeta `/(root)`.
