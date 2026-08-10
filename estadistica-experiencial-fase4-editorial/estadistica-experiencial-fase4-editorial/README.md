# Estadística Experiencial Aplicada

**Aprendizaje práctico de la estadística descriptiva con R**

Recurso educativo digital en español para explorar estadística descriptiva mediante datos, programación en R, visualización y análisis reproducible.

📖 **Sitio web:** <https://udesanalitica.github.io/estadistica-experiencial/>

---

## Qué propone este proyecto

El libro parte de una idea sencilla: aprender estadística resulta más significativo cuando los conceptos se relacionan con datos y preguntas concretas.

Cada unidad combina explicación conceptual, código en R, resultados, visualizaciones e interpretación. El objetivo es que el lector pueda avanzar desde la comprensión de una variable y su distribución hasta el análisis conjunto de dos variables, mientras adquiere prácticas iniciales de programación y documentación reproducible.

**Dirigido a:** estudiantes y docentes de educación superior que requieran una introducción aplicada a la estadística descriptiva y al uso de R.

**Requisitos previos:** no se presupone experiencia avanzada en programación.

---

## Estado actual

El recurso se encuentra **en desarrollo y revisión**. Todavía no se ha realizado una implementación formal con estudiantes o docentes y, por tanto, esta versión no reporta resultados de aprendizaje ni valoraciones de usuarios.

La siguiente etapa prevista es una implementación piloto que permita documentar el uso del material y orientar mejoras posteriores.

---

## Ruta de aprendizaje

El contenido incluye:

- fundamentos y tipos de variables;
- preparación y organización de datos;
- tablas de frecuencia;
- visualización estadística;
- medidas de tendencia central y dispersión;
- medidas de posición y forma;
- análisis bivariado;
- uso crítico de inteligencia artificial como apoyo;
- reproducibilidad con R y Quarto.

---

## Reproducir los análisis

Para ejecutar los ejemplos localmente se requiere:

- [R](https://cran.r-project.org/);
- [Quarto](https://quarto.org/);
- RStudio u otro entorno compatible;
- los paquetes indicados por el proyecto.

Instalación inicial de los principales paquetes:

```r
install.packages(c(
  "dplyr", "ggplot2", "gt", "janitor", "kableExtra", "knitr",
  "purrr", "readr", "readxl", "scales", "summarytools", "writexl"
))
```

Desde la raíz del proyecto:

```bash
quarto render
```

Los archivos de datos se referencian mediante rutas relativas, por ejemplo `data/archivo.csv`, para evitar dependencias de rutas personales.

---

## Organización del repositorio

```text
├── _quarto.yml          Configuración del libro
├── index.qmd            Prefacio e información editorial
├── 01-*.qmd ...         Capítulos temáticos
├── reproducibilidad.qmd Reproducibilidad y Quarto
├── contribuir.qmd       Orientación para participar
├── data/                Datos y documentación asociada
├── img/                 Recursos gráficos utilizados
├── CONTRIBUTING.md      Reglas detalladas de contribución
└── README.md            Presentación del proyecto
```

---

## Contribuir

Se reciben aportes que mejoren la calidad del recurso, especialmente:

- correcciones conceptuales, editoriales o de código;
- mejoras de reproducibilidad;
- propuestas de ejercicios;
- documentación de datos;
- mejoras de accesibilidad;
- ejemplos alternativos para la enseñanza de estadística.

Antes de enviar cambios, consulte [`CONTRIBUTING.md`](CONTRIBUTING.md).

Los problemas pueden reportarse mediante los *Issues* del repositorio y los cambios concretos pueden proponerse mediante *Pull Requests*.

---

## Derechos, apertura y licenciamiento

La Universidad de Santander (UDES) es titular de los derechos patrimoniales de la obra.

El proyecto es de **acceso gratuito**. Se propone publicar los contenidos textuales y las figuras propias bajo **Creative Commons Atribución 4.0 Internacional (CC BY 4.0)** y el código fuente bajo **licencia MIT**. Este esquema se encuentra pendiente de formalización institucional.

Mientras se completa esa formalización, la reutilización o adaptación del contenido debe sujetarse a las autorizaciones aplicables de la Universidad de Santander. Los conjuntos de datos mantienen las condiciones establecidas por sus respectivas fuentes.

---

## Cómo citar

> León, F. J., Pérez Pulido, M. O., & Pinto Guarguatí, L. A. (2026). *Estadística experiencial aplicada: aprendizaje práctico de la estadística descriptiva con R*. Universidad de Santander (UDES). <https://udesanalitica.github.io/estadistica-experiencial/>

---

## Autores

- **Francisco Javier León**
- **Miguel Oswaldo Pérez Pulido**
- **Leonardo Andrés Pinto Guarguatí**

Universidad de Santander (UDES) — Bucaramanga, Colombia.

---

## Tecnologías

[R](https://www.r-project.org/) · [Quarto](https://quarto.org/) · GitHub · GitHub Pages
