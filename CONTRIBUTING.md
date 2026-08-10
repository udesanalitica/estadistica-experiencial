# Guía para contribuir

*Estadística Experiencial Aplicada* se concibe como un recurso educativo que puede mejorar a partir de la revisión de su comunidad. Esta guía establece criterios para proponer cambios sin comprometer la reproducibilidad, la accesibilidad ni el uso responsable de datos.

## Aportes que resultan útiles

| Aporte | Ejemplos |
|---|---|
| **Correcciones** | Erratas, conceptos imprecisos, enlaces rotos, código que no ejecuta |
| **Mejoras didácticas** | Explicaciones más claras, ejercicios, preguntas de interpretación |
| **Código R** | Alternativas más legibles, reproducibles o pedagógicas |
| **Datos** | Conjuntos de práctica que puedan redistribuirse legalmente |
| **Accesibilidad** | Texto alternativo, estructura de encabezados, mejoras de lectura |
| **Documentación** | Diccionarios de variables, instrucciones de ejecución, fuentes |

## Antes de reportar un problema

Revise si el comportamiento puede reproducirse con la versión actual del proyecto. Al abrir un *issue*, indique:

1. capítulo o archivo donde aparece el problema;
2. resultado esperado;
3. resultado obtenido;
4. mensaje completo de error, cuando aplique;
5. versión de R y paquetes relevantes, si se trata de un problema de ejecución.

Repositorio: <https://github.com/udesanalitica/estadistica-experiencial/issues>

## Proponer cambios mediante Git

Una contribución técnica puede seguir este flujo:

1. hacer un *fork* del repositorio;
2. crear una rama con un nombre descriptivo;
3. realizar el cambio;
4. ejecutar `quarto render` desde la raíz del proyecto;
5. revisar que no existan errores de renderizado;
6. enviar un *pull request* explicando qué se modificó y por qué.

Para modificaciones amplias —por ejemplo, un capítulo nuevo o un cambio de estructura— es preferible abrir primero un *issue*.

## Criterios de reproducibilidad

Los aportes de código deben:

- utilizar rutas relativas al proyecto;
- evitar dependencias de carpetas personales;
- incluir los datos necesarios o una forma documentada de obtenerlos;
- declarar paquetes adicionales cuando sean indispensables;
- fijar una semilla con `set.seed()` cuando intervenga aleatorización;
- ejecutarse desde una sesión limpia de R siempre que sea posible.

El propósito es que otra persona pueda reproducir el ejemplo sin reconstruir manualmente el entorno del autor.

## Datos: qué puede incorporarse

Los datos propuestos deben tener una fuente identificable y condiciones de uso compatibles con su publicación en el proyecto.

No se deben incorporar:

- datos personales identificables;
- información confidencial o reservada;
- bases obtenidas bajo acuerdos que impidan su redistribución;
- archivos cuya procedencia o permiso de uso no pueda demostrarse.

Cuando un conjunto provenga de una fuente pública, debe conservarse la atribución y documentación necesaria para identificar su origen.

## Figuras, capturas y otros recursos gráficos

Cada figura debe ser propia, generada por código o contar con derechos suficientes para su utilización en el proyecto.

Además:

- toda imagen informativa debe incluir texto alternativo significativo;
- se recomienda generar gráficos mediante R cuando sea posible;
- las capturas de pantalla deben utilizarse solo cuando aporten información que no pueda expresarse mejor mediante texto o código;
- no debe asumirse que citar una imagen tomada de Internet equivale a tener permiso para redistribuirla.

## Coherencia pedagógica

Los nuevos ejemplos deben distinguir, cuando corresponda:

**problema → datos → procedimiento → resultado → interpretación**

Si se presentan distintas herramientas para una misma tarea —por ejemplo, R base y `ggplot2`— debe explicarse la finalidad pedagógica de la comparación para evitar que el lector la interprete como una inconsistencia.

## Licenciamiento de aportes

La Universidad de Santander (UDES) es titular de los derechos patrimoniales de la obra principal. El proyecto se encuentra en proceso de formalización de su esquema de licenciamiento abierto.

Quien envíe una contribución declara que tiene derecho a compartir el material aportado y autoriza su revisión e incorporación al proyecto. La publicación de contribuciones bajo licencias abiertas se realizará de acuerdo con el esquema que sea formalizado institucionalmente para la obra.

La autoría de aportes sustantivos será reconocida de acuerdo con la naturaleza y alcance de la contribución.

## Convivencia

Las discusiones deben concentrarse en el contenido, el código y las decisiones pedagógicas. Se espera un intercambio respetuoso y orientado a mejorar el recurso.

## Contacto

Para asuntos que no correspondan a un *issue*, utilice los canales institucionales del proyecto.

**Universidad de Santander (UDES)**  
Bucaramanga, Santander, Colombia
