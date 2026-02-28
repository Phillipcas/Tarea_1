# Tarea-1 — Ejercicio 2

## Descripción del proyecto

Este repositorio contiene el desarrollo del **Ejercicio 2** correspondiente a la tarea conjunta del curso. El análisis se realiza en **R Markdown** con el objetivo de garantizar la replicabilidad de los resultados.

El trabajo estudia el comportamiento de distintas series macroeconómicas y laborales para México utilizando información del INEGI, construyendo tasas de cambio anuales, medidas de volatilidad, comparaciones gráficas y una matriz de varianzas y covarianzas.

---

## Estructura del repositorio

```id="2vv6f4"
Tarea-1/
│
├── BASES DE DATOS/
│   ├── PIB REAL ANUAL (INEGI).xlsx
│   ├── SALARIO ANUAL (INEGI).xlsx
│   ├── DESOCUPACION (INEGI).xlsx
│   ├── PARTICIPACION (INEGI).xlsx
│   ├── OCUPACION INFORMAL (INEGI).xlsx
│   └── TASA INFORMAL (INEGI).xlsx
│
└── Ejercicio_2.Rmd
│
└── Ejercicio_2.PDF
```

---

## Contenido del análisis

El archivo `Ejercicio_2.Rmd` incluye:

1. Construcción de series anuales para:

   * PIB real
   * Salarios reales
   * Desocupación
   * Participación laboral
   * Ocupación en el sector informal
   * Informalidad laboral

2. Cálculo de:

   * Tasas de cambio anual (log-diferencias)
   * Volatilidad de cada serie

3. Presentación de resultados mediante:

   * Tablas
   * Gráfica comparativa de tasas de cambio
   * Matriz de varianzas y covarianzas

4. Interpretación económica de los resultados.

---

## Requisitos

El código requiere los siguientes paquetes de R:

```r id="yxh7a1"
readxl
dplyr
ggplot2
scales
kableExtra
knitr
tidyr
```

En caso necesario, instalar con:

```r id="kr4x0e"
install.packages(c(
  "readxl",
  "dplyr",
  "ggplot2",
  "scales",
  "kableExtra",
  "knitr",
  "tidyr"
))
```

---

## Ejecución

1. Descargar o clonar el repositorio.
2. Abrir `Ejercicio_2.Rmd` en RStudio.
3. Ejecutar los chunks o compilar el documento mediante **Knit** (HTML o PDF).

---

## Consideraciones de replicabilidad

* Las rutas de los archivos son relativas al repositorio.
* Es necesario mantener la estructura de carpetas y los nombres de los archivos.
* El análisis está diseñado para ejecutarse sin modificaciones adicionales cuando se conserva dicha estructura.

---
