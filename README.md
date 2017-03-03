# Open Data Day, Granada, 2017

Este año nos volvemos a reunir para hablar de datos abiertos, de
patrimonio abierto, y a machacar datos y sacar todo lo que podamos de
ellos.

# Qué

Estamos
[invitados, de nuevo, al Open Data day](http://opendataday.org/), un
evento a nivel internacional en el que se trata de abrir datos,
trabajar sobre datos abiertos, y en general acercar los datos a la
ciudadanía para mejorar la calidad de vida y tomar decisiones
informadas. 

En Granada venimos
celebrando [un hackatón](https://es.wikipedia.org/wiki/Hackathon), es
decir, un maratón de diseño y creación de aplicaciones que, en
espíritu del día de los datos abiertos, está abierto a todo el mundo.

# Quién

*Todo el mundo*

No, en serio, es un evento para todo el mundo. Se trata de un evento
en el que se aprende, se enseña, se conoce y se da uno a conocer. Si
tienes ciertos conocimientos de

* Diseño.
* Documentación.
* Periodismo.
* Visualización de datos.
* Programación.
* Prueba de aplicaciones.
* Comunicación.
* (tu afición y/o profesión y/o lo que te guste)

este hackatón es para ti. Sólo necesitas un equipo informático (la
conexión a Internet la ponemos nosotros), un poco de tiempo (no es
necesario que estés en el hackatón durante toda su duración), algunas
ideas sobre qué te gustaría obtener del hackatón y ganas de aprender y
de ayudar a liberar datos para que todo el mundo se beneficie de
ellos. [La inscripción es gratuita](https://www.meetup.com/es-ES/Granada-Geek/events/236840299/) y
los proyectos que se sugieren no están cerrados. Si se te ocurre
alguno más y estás dispuesto a trabajar con las personas que quieran
sumarse a ese proyecto, no tienes más que proponerlo en los
comentarios de la página de inscripción. 

# Cómo

El Open Data Day incluirá interesantes talleres sobre Patrimonio en la
UGR, que se convertirá en un proyecto si hay interés suficiente. 

Muy importante: **tráete tu portátil**. La mejor forma de colaborar
con el hackatón es trabajando con un teclado. Un *tablet* puede ser la
segunda mejor cosa, sobre todo si te dedicas a visualizar o a probar,
pero lo mejor es que ayudes escribiendo, programando o probando. 

Tampoco es necesario que estés allí todo el tiempo. Puedes ir y venir,
trabajar en tu casa o dejar de hacerlo. Cuanto más tiempo estés, más
ocasiones tendrás de aprender y de conocer gente, así como contribuir
al esfuerzo conjunto. Pero no es estrictamente necesario.

La Corrala está conectada a la red de la
[universidad](https://www.ugr.es), y tendremos cuentas de invitados
para las personas que no tengan cuenta en la misma. 

## Cómo trabajar con los diferentes proyectos.

Se trabajará en [GitHub](https://github.com) en todos los proyectos,
por lo que hacen falta, al menos, conocimientos de
[git](https://mini-git.github.io/) para poder trabajar con él. En el
caso de que no lo conozcas, te podemos ayudar sobre la marcha con una
tutoría personalizada, no te preocupes. También se puede usar desde la
web, aunque no se aconseja. Por lo mismo, conviene que se abra
previamente al hackatón una cuenta en el GitHub mencionado
anteriormente. 

### Carreras en cifras

Es un conjunto de datos sobre el que hemos venido trabajando a lo
largo de los años, así que merece la pena que lo actualicemos y
sigamos trabajando sobre él. El principal objetivo es analizar y
visualizar la desigualdad de género en las diferentes carreras
universitarias y su evolución a lo largo del tiempo. Trabajaremos en
[este repositorio](https://github.com/oslugr/carreras-en-cifras) y
posibles objetivos incluyen:
* Actualizar los datos al año en curso.
* Buscar datos de otras universidades y nacionales y analizarlos.
* Buscar correlación de estos datos con datos estadísticos de otro
  tipo: geográficos, empleabilidad, procedencia geográfica,
  demográficos.
* Relacionarlos con datos estadísticos de empleos y realizar
  predicciones sobre equilibrio de género en esas carreras a medio y
  largo plazo.
* Crear visualizaciones orignales e intractivas de estos datos.

Coordinando este proyecto desde la OSL estará
[Pablo](http://github.com/psicobyte). 

Para colaborar en este proyecto necesitamos
* Personas con conocimientos de visualización de datos.
* Personas con conocimiento de extracción de datos de la web
  (*scraping*).
* Personas con conocimientos de programación *front-end*.
* Personas que sean capaces, a partir de los datos, de generar un
  informe o crear una historia periodística.


### Patrimonio de Granada en la Wikipedia y Wikidata

El patrimonio de la UGR está relativamente mal representado en la
Wikipedia, con sólo algunos edificios emblemáticos, y dentro de estos
poca presencia en
[Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page), una
parte más desconocida de la wikipedia pero que permite, por ejemplo,
trabajar con datos de forma cuantitativa y precisa. Se trabajará sobre
[este repositorio](https://github.com/oslugr/patrimonioAbierto)

Diferentes subproyectos incluirán
* Uso de un cliente de la Wikipedia para crear automáticamente páginas
  a partir del contenido de la web de Patrimonio, que tiene licencia
  libre, con una posterior *curación* del mismo añadiéndole citas y, en
  su caso, imágenes.
* Uso de clientes de Wikidata para incluir automáticamente datos sobre
  los edificios patrimonio en la misma.
* Creación de *queries* para recopilar datos sobre Patrimonio UGR
* Visualización de datos de Patrimonio en un mapa a partir de la
  extracción automática de datos de la Wikipedia
* Creación automática de rutas sobre Patrimonio de la UGR de acuerdo
  con algún perfil.
  
En la OSL será [Germán](http://github.com/germaaan) quien esté a cargo
de este proyecto, junto con
[Chá Lucena](https://github.com/chalucena). El producto final será el
mapa, que se debería actualizar automáticamente según se añadan nuevos
elementos a la Wikipedia. 

### Contaminación en Andalucía: proyecto ContaminAND

Se habla mucho de la contaminación en Madrid, pero relativamente poco
de la contaminación en las principales ciudades andaluzas. El objetivo
de este proyecto es crear un API que permita leer desde *apps* o
cualquier programa las lecturas de la calidad del aire de las
diferentes ciudades andaluzas con medidores. En Granada
[exiten una serie de medidores](http://www.granada.org/inet/wambiente.nsf/b1b426e5d69467c3c125763b0031d0c4/9d664bddf7e64554c125764e003875c0!OpenDocument)
que depositan los resultados en
[esta página](http://www.juntadeandalucia.es/medioambiente/atmosfera/informes_siva/feb17/ngr170201.htm). Hay
que extraer periódicamente los resultados de esa página y publicarlos;
ese será el foco principal de este subproyecto coordinado en la OSL
por [JJ](http://github.com/JJ), [Renato](http://github.com/renatolrr) y [Manu](http://github.com/Makova). Trabajaremos sobre este [repositorio](http://github.com/oslugr/contaminAND)

Los diferentes subproyectos que se incluyen en este son:
* Extracción de datos de la página arriba indicada y almacenamiento de
  los mismos para su fácil disponiblidad, en Google Fusion Tables,
  Google SpreadSheet, o cualquier otro lugar donde estén
  disponibles. También en alguna base de datos.
* Creación de un middleware que publique los datos en un interfaz REST
  fácilmente disponible y sin limitación de peticiones.
* Creación de un *app* que avise sobre niveles de contaminación.
* Narración de la historia de la contaminación en una zona
  determinada.
* Correlación de los datos de contaminación con otros: enfermedades,
  meteorógicos, circulación si existen.
* Publicación de un informe sobre contaminación en una ciudad
  determinada.
  


# Cuándo

Comenzaremos el sábado alrededor de las 10 de la mañana,
conociéndonos, formando grupos y viendo el trabajo que hay por
delante. También buscando espacios dentro de la Corrala donde todos
podamos trabajar cómodamente. Terminaremos el domingo por la tarde,
con una presentación del trabajo realizado o simplemente yéndonos de
cervezas. El trabajo en un hackatón es muy auto-organizado, pero lo
interesante es que haya algo tangible al final del mismo y se presente
aquí. 

# Por qué


