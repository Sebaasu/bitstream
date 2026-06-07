# Simulador de Transmisión de Bits - ETN 703

Este proyecto es un simulador web interactivo diseñado para visualizar y comprender los métodos de codificación de línea y las técnicas de detección y corrección de errores en sistemas de telecomunicaciones. Desarrollado como proyecto final para la asignatura ETN 703 (Teoría de Telecomunicaciones I) de la Universidad Mayor de San Andrés (UMSA).

La aplicación es completamente estática, ejecutándose en el navegador del lado del cliente sin dependencias ni servidores externos.

## Características

El simulador permite procesar un flujo de bits y analizar en tiempo real:

### Códigos de Línea
Representación gráfica y tablas de transición para los siguientes esquemas:
* NRZ-L (Non-Return-to-Zero Level)
* NRZ-I (Non-Return-to-Zero Inverted)
* AMI (Alternate Mark Inversion)
* MLT-3 (Multi-Level Transmit 3)
* Manchester
* Manchester Diferencial

### Detección y Corrección de Errores
Cálculo paso a paso y paneles explicativos para:
* VRC (Redundancia Vertical / Paridad Simple)
* LRC (Redundancia Longitudinal)
* CRC (Redundancia Cíclica)
* Checksum (Suma de comprobación)
* Código de Hamming (con matriz de paridad)

## Tecnologías Utilizadas

* HTML5 y CSS3 para el diseño y maquetación interactiva.
* JavaScript (Vanilla) para la lógica de cálculo y procesamiento de datos.
* Canvas API para el renderizado gráfico de las formas de onda.

## Ejecución Local

Para ejecutar el simulador localmente, clone el repositorio y abra el archivo `index.html` en cualquier navegador moderno:

```bash
git clone https://github.com/Sebaasu/bitstream.git
cd bitstream
# Abrir en el navegador (en sistemas basados en Unix/Linux)
xdg-open index.html
```

## Despliegue

El proyecto se despliega en GitHub Pages a partir de la rama `main`. La aplicación web interactiva se encuentra disponible en:
[https://sebaasu.github.io/bitstream/](https://sebaasu.github.io/bitstream/)
