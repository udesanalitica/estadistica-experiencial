# Datos utilizados en el libro

Esta carpeta contiene los conjuntos de datos y materiales complementarios usados en los ejemplos del libro.

| Archivo | Propósito | Dimensiones |
|---|---|---:|
| `S07D_Acuicultura.csv` | Ejemplos con datos del sector acuícola del Tercer Censo Nacional Agropecuario (DANE). | 3.447 filas × 14 columnas |
| `diccionario_acuicultura.xlsx` | Diccionario resumido de variables de la base de acuicultura. | 14 filas × 4 columnas |
| `bd_antropometricas.xlsx` | Actividades pedagógicas con medidas antropométricas. | 260 filas × 17 columnas |
| `taller_medidas_antropometricas.pdf` | Material complementario asociado con la actividad de medidas antropométricas. | Documento PDF |

## Uso reproducible

Los capítulos del libro llaman estos archivos mediante rutas relativas, por ejemplo:

```r
readr::read_csv("data/S07D_Acuicultura.csv")
readxl::read_excel("data/bd_antropometricas.xlsx")
```

Por esta razón, la carpeta `data/` debe conservar su nombre y ubicación en la raíz del proyecto.

## Fuente y condiciones de uso

La base de acuicultura proviene de información oficial del Departamento Administrativo Nacional de Estadística (DANE); en el capítulo de fundamentos se enlaza el diccionario oficial correspondiente. Las condiciones de reutilización de bases provenientes de terceros deben respetar los términos definidos por su fuente original.

La base antropométrica se utiliza con fines pedagógicos dentro del recurso. En la versión incluida no se observan campos de identificación directa como nombres o documentos de identidad.
