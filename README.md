# Pipeline para una minería de datos

## Introducción

La administración moderna está dirigida hacia los datos; los datos de
clientes y corporaciones están siendo reconocidas como activos estratégicos.
Las decisiones basadas en mediciones objetivas son mejores que decisiones
basadas en opiniones subjetivas que pueden ser confusas y tener una alta
desviación estadística de la realidad.

Los datos son creados constantemente y una tasa que siempre incrementa
Calulares, redes sociales, tecnologías para imágenes que determinan
diagnósticos médicos, compras en supermercados y muchas más cosas están 
creando datos, los cuales están siendo guardados en muchas partes a la vez
por muchos motivos. La minería de datos es la manera que tenemos para 
analizar, procesar y convertir estos datos en información que instruya,
responda y ayude a entender y tomar decisiones. 

La habildad para extraer conocimiento útil pero usualmente escondido de
estos datos se está convirtiendo en una tarea cada vez más importante
en el mundo competitivo de hoy. Cuandos los datos se usan para predecir,
el comportamiento furuto de una empresa es menos incierto y eso solo
puede ser una ventaja; "el precabido vale por dos".

Los avances tecnológicos y la industria computacional han sido testigos
de un crecimiento enorme en los sectores de hardware y software. Las
bases de datos sofisticadas han alentado al almacenamieto de datasets
masivos, y esto creó la necesidad de la minería de datos en el contexto
de las empresas y negocios. La minería de datos, algunos podría decir, 
que tiene sus raices en las estadísticas y el aprendizaje de máquina,
está dedicada a la colección de datos, su descripción, análisis y 
predicción desde los mismos. 


La minería de datos usa los métodos científicos de exploración y 
apliación. Somos presentados con un cantidad masiva de datos, que 
muchas veces debemos considerar como la población (es decir, que tenemos
todo lo que existe a nuestra disposición). La minería de datos es un proceso
que usa una variedad de métodos de análisis de datos para descubir
patrones y relaciones desconocidas, inesperadas, interesantes y relevantes
en los datos que pueden ser utilizados para hacer predicciones válidas
y precisas. 

-----------------------------------------------------------------------------

## Sobre este repositorio

El proceso de minería de datos depende ciertamente de los datos que se desean
analizar, pero en este repositorio intentaré recopilar la mayor cantidad de 
información posible sobre lo que he aprendido estos últimos años sobre el tema,
utilizando además la información desde fuentes bibliográficas reconocidas
y recomendando otros repositorios que me parecen tienen información bastante
útil sobre el tema.

Hago este repositorio en español debido a que está orientado a la comunidad
de habla hispana, considero que existen muchas fuentes importantes a las que
acudir en inglés, y no muchas de este tipo en español. El contenido del mismo
está bajo la licencia Apache 2.0, mediante la cual esta información es 
reproducible y distribuible, o trabajos derivadas de la misma, a través de 
cualquier medio, con o sin modificaciones, con la condición que se cumpla
lo estipulado por la licencia. La licencia se encuentra en este repositorio.

Todas las sugerencias, ayudas, y dudas son bienvenidas. Las dudas, problemas,
o errores de fondo que encuentren en el repositorio pueden ser consultadas conmigo a 
través de los Issues de GitHub, y las sugerencias de nuevas secciones, errores
ortográficos, ejemplos, etc., pueden añadirse a través de Pull Requests de GitHub.

------------------------------------------------------------------------------

## ¿Qué es un "Pipeline" en la ciencias de la computación?


Pipeline es un término inglés que puede traducirse como “tubería”. Aunque no 
forma parte del diccionario de la Real Academia Española (RAE), cada vez es más 
utilizada en computación e informática. Desde hace varias décadas se comenzó a 
utilizar para hacer referencia a un tipo de arquitectura para computadores.
Estas tuberías virtuales se crean para segmentar los datos y, de este modo,
incrementar el rendimiento de un sistema digital. Segmentar los cálculos, 
por lo tanto, permite mejorar la frecuencia de trabajo. Este tipo de flujo 
de datos implica que *la salida de una fase es una entrada de otra*. Esta 
es la frase clave para entender el procesamiento de datos, información y 
trabajos en un pipeline. 

En nuestro caso aplicaremos el concepto de pipeline a la minería de datos. 
Con esto me refiero a aplicar una serie de procesamientos, i.e. flitrados, 
depuraciones, cálculos, agrupaciones, a los datos que deseamos analizar. 
La fuente de los datos puede ser muy distinta, y es importante entender 
de donde vienen y su estructura antes de pensar en aplicar este pipeline. 

## Lo más importante -> Tener buenas preguntas

Un proceso de minería de datos es inútil si no sabemos para qué lo estamos 
haciendo. Es de vital importancia que sepamos el motivo por el cual queremos
hacer un proceso de minería de datos, qué queremos obtener de él y si en 
realidad es relevante hacerlo. 

Muchas veces seremos encargados de un proyecto de minería de datos el cual
no es de nuestra iniciativa sino de la de una empresa o un tercero, de igual
manera es importante entender sus necesidades e intereses para poder ubicarnos
y poder tener una meta que alcanzar con el proceso. Muchas veces habrán muchas 
preguntas interesantes a las cuales deseamos darles respuesta, esto aunque es
muy bueno, puede llevar al equipo de desarrollo a considerar aspectos que tal
vez no conduzcan por buenos caminos a la investigación, por lo tanto también es
importante poder discernir que preguntas son las principales y las que deben 
guiar el proceso de desarrollo de la minería de datos. 

Ejemplos de preguntas interesantes en proyectos de minería de datos - cabe 
destacar que las preguntas también deben considerar algunos asepectos sobre 
la estructura de los datos de entrada, la forma en que queremos los datos 
de salida, y claro todo lo referente a los diferentes objetivos del proyecto, 
estas pueden estar dirigidas hacia los intereses de un cliente que nos contrate,
o intereses propios sobre unos datos que deseamos analizar:

1. Preguntas genéricas:

- ¿Qué estructura tienen los datos de entrada?
- ¿Qué quiero obtener de los resultados de esta minería de datos?
- ¿Por qué me importa hacer esta minería de datos?
- ¿Qué beneficios puedo obtener al hacer esta minería de datos?
- ¿Tengo los datos suficientes para poder darle respuesta a mis preguntas?
- ¿Puedo obtener otros datos aparte de los que tengo?
- ¿Existe una descripción de los datos, campos, tablas, cabeceras?
- ¿Existen otros artículos, proyectos o trabajos que hayan realizado algo 
parecido a lo que quiero? En caso de que sí, ¿qué metodologías utilizaron?, 
¿qué resultados obtuvieron? ¿qué análisis y conclusiones obtivieron de 
sus resultados? ¿están publicados los datos que utilizaron, y puedo acceder
a ellos?
