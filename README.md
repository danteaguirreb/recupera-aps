# RECUPERA APS

Prototipo académico para explorar la gestión trazable de cupos liberados en atención primaria. El proyecto se desarrolló en **Entornos Digitales, Servicios de Innovación e Inteligencia Artificial**, como trabajo del Grupo 09 del Magíster en Data Science e Inteligencia Artificial de la Universidad del Desarrollo.

## Estado y límites

La versión V5 es una demo local con casos sintéticos. No utiliza datos de pacientes, no se conecta a Rayen/Keirón, no modifica agendas reales y no cuenta con evaluación de impacto institucional. Las decisiones clínicas y de agenda permanecen en personas responsables. La línea base del informe analítico es candidata y requiere conciliación institucional; las estimaciones financieras son escenarios, no ahorros demostrados.

## Demo

Abra [`web/index.html`](web/index.html) en un navegador de escritorio. No requiere instalación ni conexión a internet. Restablezca los datos de demostración antes de cada recorrido; use únicamente los casos ficticios incluidos.

## Material seleccionado

- `reports/dossier-final.pdf`: dossier integrado del proyecto.
- `reports/informe-no-show-v0.6.pdf`: análisis agregado de inasistencias y costo de capacidad.
- `presentation/defensa-final.pdf`: presentación final de defensa.
- `notebooks/analisis-asistencia-costos.ipynb`: metodología de línea base y valorización de capacidad.
- `notebooks/presupuesto-costos-saas.ipynb`: escenario de costos SaaS y supuestos de operación.
- `docs/verificacion-tecnica.md`: comprobaciones automáticas reportadas para V5.

## Reproducibilidad y datos

Los datos clínicos y laborales fuente se excluyen intencionalmente. El notebook analítico solo puede ejecutarse localmente con acceso autorizado a las fuentes, configurando `MDS_NOSHOW_ROOT` con la carpeta del proyecto que contiene `02_Datos_Fuente` y `MDS_NOSHOW_HMAC_KEY` con una clave aleatoria privada de al menos 32 bytes. Los identificadores internos se transforman con HMAC-SHA256; la clave no se incluye aquí. No se recomienda publicar resultados detallados ni cambiar la visibilidad de este repositorio sin autorización institucional y del equipo.

El notebook de presupuesto contiene supuestos y montos agregados derivados de información institucional; este repositorio permanece privado mientras no exista autorización de publicación. Los resultados guardados de los notebooks se eliminaron para evitar exponer valores de fuente. No se incluyen bases, nóminas, extractos, capturas de reuniones, feedback privado ni instrucciones docentes.

## Origen y autoría

Proyecto grupal del Grupo 09. Los informes y la defensa identifican a sus coautores. Este repositorio conserva la atribución original y no implica que todos los integrantes hayan aprobado su difusión pública.
