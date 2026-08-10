# Datos utilizados en el libro

Esta carpeta contiene los conjuntos de datos y materiales complementarios usados en los ejemplos del libro.

| Archivo | Propósito | Dimensiones |
|----|----|---:|
| `S07D_Acuicultura.csv` | Copia de trabajo del archivo S07D (Acuicultura) del Tercer Censo Nacional Agropecuario (3er CNA), 2014, DANE. | 3.447 filas × 13 columnas |
| `diccionario_acuicultura.xlsx` | Diccionario resumido de las variables utilizadas de S07D (Acuicultura). | 13 filas × 4 columnas |
| `bd_antropometricas.xlsx` | Base pedagógica de medidas antropométricas orientada por Miguel Oswaldo Pérez Pulido (UDES). | 260 filas × 17 columnas |
| `taller_medidas_antropometricas.pdf` | Material complementario asociado con la actividad de medidas antropométricas. | Documento PDF |

## Uso reproducible

Los capítulos del libro llaman estos archivos mediante rutas relativas, por ejemplo:

``` r
readr::read_csv("data/S07D_Acuicultura.csv")
readxl::read_excel("data/bd_antropometricas.xlsx")
```

Por esta razón, la carpeta `data/` debe conservar su nombre y ubicación en la raíz del proyecto.

## Fuente y condiciones de uso

### Base S07D (Acuicultura)

La base `S07D_Acuicultura.csv` corresponde a una copia de trabajo del archivo **S07D (Acuicultura)** del **Tercer Censo Nacional Agropecuario (3er CNA), 2014**, producido por el **Departamento Administrativo Nacional de Estadística (DANE), Colombia**. El archivo oficial documenta 13 variables. En esta copia se eliminó únicamente una columna auxiliar de índice generada durante una exportación previa, sin modificar las variables sustantivas del DANE.

**Cita sugerida:** Departamento Administrativo Nacional de Estadística (DANE). (2014). *Tercer Censo Nacional Agropecuario - 2014 - 3er CNA: S07D (Acuicultura)* \[Conjunto de datos\]. Catálogo de Microdatos del DANE.

Diccionario oficial: <https://microdatos.dane.gov.co/index.php/catalog/513/data-dictionary/F4?file_name=S07D(Acuicultura)>

Las condiciones de reutilización de esta fuente deben respetar los términos definidos por el DANE.

### Base antropométrica

La base `bd_antropometricas.xlsx` fue construida con fines académicos a partir del **Taller de Clase No. 2: Práctica sobre Medidas Antropométricas**, desarrollado en la asignatura **Estadística Descriptiva y Probabilidad**, orientada por el profesor **Miguel Oswaldo Pérez Pulido** en la **Universidad de Santander (UDES)**.

**Crédito de la base:** Miguel Oswaldo Pérez Pulido, Universidad de Santander (UDES).

La base se utiliza con fines pedagógicos dentro del recurso. En la versión incluida no se observan campos de identificación directa como nombres o documentos de identidad.
