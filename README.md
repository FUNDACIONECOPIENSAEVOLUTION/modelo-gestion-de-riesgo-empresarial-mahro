# MAHRO — Adaptabilidad empresarial y resiliencia organizacional

Prototipo web estático del **Modelo Administrativo Híbrido de Resiliencia Organizacional (MAHRO)**. Está pensado para que cada empresa adapte funciones, cargos, responsables y flujos a su estructura y capacidad. El Sistema de Comando de Incidentes se integra como referencia táctica; no es el nombre del sistema.

## Sitio

La página principal está en `index.html`. Con GitHub Pages habilitado para la rama `main` y la carpeta raíz, se publica en:

https://fundacionecopiensaevolution.github.io/modelo-gestion-de-riesgo-empresarial-mahro/

El sitio no requiere instalación ni compilación. El mapa geográfico carga Leaflet y mosaicos de OpenStreetMap desde internet; el plano de sede, dibujo, datos y respaldos funcionan localmente.

## Módulos

- Resumen de la integración MAHRO: respuesta táctica, gobernanza de crisis y continuidad del negocio.
- Centro de comando: contexto del incidente, periodo operacional, bitácora y decisiones.
- Operación MAHRO: objetivos, recursos, conteos agregados de personas (incluye valoración y traslado), registro fotográfico local, mapas de sede y geográfico, símbolos arrastrables, dibujo libre y zonas de peligro poligonales con etiqueta e impresión.
- Directorio editable de funciones y cargos empresariales, precargado con equivalencias de la propuesta MAHRO.
- Continuidad: procesos críticos, responsables, prioridades y alternativas de recuperación.
- Gobernanza: comité de crisis, enlaces externos y decisiones estratégicas.
- Modelo MAHRO: gráfico de adaptación empresarial, organigrama empresarial redibujado en `assets/mahro-organigrama-empresa.png` y flujo integrado.
- Fundamento y método: explica la investigación cualitativa de casos múltiples para la propuesta 1.A y la metodología mixta y participativa de la propuesta 1.B.
- Propuestas: presenta las dos escalas de investigación —intraempresarial e interorganizacional— y su relevancia ante el sismo del 10 de agosto de 2026, con enlaces a fuentes oficiales.
- Ubicación GPS del dispositivo bajo permiso explícito, con copia o envío voluntario de coordenadas por WhatsApp y opción de guardar un punto.
- Nueva operación con reinicio de datos operativos y conservación del directorio y la configuración organizacional.
- Impresión y respaldo JSON para exportar o importar datos.

## Datos y alcance

Los datos de operación, cargos, planos, puntos, zonas delimitadas y evidencias se guardan en el almacenamiento local del navegador. El GPS se consulta únicamente tras pulsar **Iniciar GPS**; no se guarda ni transmite de forma automática. Al usar **Compartir por WhatsApp**, el usuario elige abrir esa aplicación con un enlace de mapa. No existe sincronización entre usuarios ni envío de datos al repositorio. Usa **Exportar** para descargar un respaldo JSON y **Importar respaldo** para recuperarlo.

Esta versión es demostrativa y sirve para revisión, planeación y ejercicios. No ofrece rastreo multiusuario en vivo, despacho de recursos, autenticación ni almacenamiento central. El listado de afectaciones se maneja como conteos agregados, sin ficha nominativa de pacientes. No reemplaza los planes aprobados, las responsabilidades legales ni los protocolos de las autoridades competentes. No registres datos médicos identificables, credenciales ni información sensible de la empresa.

## Fuentes del proyecto

- [Tablero SCI de referencia](https://instructorandradedcc.github.io/modelo-sci-dcc/)
- [Propuesta MAHRO](https://instructorandradedcc.github.io/PROPUESTA-MAHRO/)
- [Propuestas doctorales y organigrama adaptado](https://instructorandradedcc.github.io/propuesta-doctoral-administraci-n-uniandes/)

## Publicación

Si GitHub Pages aún no está activo para la raíz de `main`, en **Settings → Pages** selecciona **Deploy from a branch**, la rama `main` y la carpeta `/(root)`.
