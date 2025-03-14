# :wavy_dash: Python :wavy_dash: <sup> por Sergio Espartero </sup>


1. [Introducción](#wavy_dash-1-introducci%C3%B3n)
2. [Historia](#wavy_dash-2-historia)
3. [Campo de aplicación](#wavy_dash-3-campo-de-aplicaci%C3%B3n)
4. [Clasificación](#wavy_dash-4-clasificaci%C3%B3n)
5. [Otras curiosidades](#wavy_dash-5-otras-curiosidades)
6. [IDE'S](#wavy_dash-6-ides)
7. [Frameworks](#wavy_dash-7-frameworks)
8. [Webgrafía](#wavy_dash-8-webgraf%C3%ADa)

## :wavy_dash: 1. INTRODUCCIÓN

Python es uno de los lenguajes de programación de alto nivel más utilizados en todo el mundo. Según la última encuesta de **Stack Overflow**, el 51% de los participantes trabajan o habrían trabajado extensamente con este lenguaje durante el último año, clasificándose así como la [tercera tecnología más utilizadas en el año 2024](https://survey.stackoverflow.co/2024/technology) [^1], siendo superado únicamente por **JavaScript** y el conjunto **HTML/CSS**.   
 
La simplicidad de su sintaxis, su versatilidad, el extraordinario respaldo comunitario existente, sumados al auge de la ciencia de datos y la Inteligencia Artificial, para las que **Python** goza de una extensa colección de librerías y frameworks, han catapultado su popularización durante la última década hasta ser galardonado como ["El lenguaje de programación del año"](https://www.tiobe.com/tiobe-index/) [^2] _("Programming Language of the Year", TIOBE index)_ hasta en 4 ocasiones desde 2018.

## :wavy_dash: 2. **HISTORIA**

El lenguaje fue diseñado inicialmente por _Guido Van Rossum_ en 1989, en el _Stichting Mathematisch Centrum (CWI)_ como sucesor de la tecnología **ABC** [^3], un lenguaje de programación imperativo originalmente destinado a reemplazar **BASIC** [^4]. Un par de años más tarde, en febrero de 1991, Python sería presentado públicamente por primera vez en el entorno de **USENET** [^5], un sistema de comunicación en línea precursor a los actuales foros de Internet, donde desarrolladores de todo el mundo interesados en la propuesta planteada por _Van Rossum_ plantearían sus dudas y sugerencias de mejora, contribuyendo innegablemente al desarrollo y difusión del joven lenguaje. 

Con el transcurso del tiempo, la continuidad del proyecto transitaría múltiples empresas _(BeOpen, Digital Creations, Zope Corporation...)_ bajo la responsabilidad de su creador original _(apodado cómicamente como el "dictador benevolente de por vida", BDFL, Benevolent Dictator For Life)_, hasta la fundación, en 2001, de la _Python Software Foundation (PSF)_, una organización sin ánimo de lucro que ostenta la propiedad intelectual del lenguaje [^6]. Tras la renuncia de _Van Rossum_ en 2018 y la posterior fundación del _Consejo de Dirección de Python_ _(Python Steering Council)_, ambas entidades contribuyen, en un esfuerzo comunitario con la Comunidad de Core Developers _(encargados de revisar y aprobar las **PEP's, Python Enhancement Proposals**)_, en la incesante evolución y crecimiento de **Python**. 

En la actualidad, la versión más reciente en la que se encuentra disponible el lenguaje es la `3.13.2`, lanzada el 4 de febrero de 2025. Bajo el estandarte de la filosofía _Open Source_, **Python** parece dirigirse hacia un futuro todavía más prometedor, con diversas iniciativas encaminadas a mejorar su rendimiento _(CPython [^8], Compiladores Just-In-Time [^9]...)_, expandir su uso en el desarrollo web _(PyScript [^10]...)_ y la computación en la nube _(AWS Lambda, Google Cloud Functions...)_, así como mantener su reinado en el sector de la _IA_ y el _Machine Learning_.

## :wavy_dash: 3. **CAMPO DE APLICACIÓN**
- `Desarrollo web`. Utilizado ampliamente para el _backend_ en el contexto del desarrollo de aplicaciones web, apoyado en las características de diferentes _frameworks_ enfocados a tal fin _(**Django**, **Pyramid**, **Flask**..)_. Aplicaciones tan conocidas como Spotify, Pinterest, Dropbox o Reddit han desarrollado su _backend_ con **Python**.
- `Ámbito científico`. El ecosistema de **Python** ofrece muchísimas herramientas y librerías de gran utilidad para la computación científica, erigiéndose como la principal competencia de **R** en esta área. Algunas de sus librerías más populares son **Scipy**, **Numpy** o **Pandas**. 
- `Educación`. La sencillez de su sintaxis, sumada a la cantidad de recursos gratuitos disponibles para aprender a utilizar el lenguaje, incluyendo herramientas, cursos y aplicaciones de entretenimiento _(a modo de páginas o juegos interactivos)_, destinados a facilitar la transición de lenguajes de programación visual _(diseñados para la introducción en el desarrollo del software de los más pequeños, como **Scratch** o **Blockly**)_ a **Python**, han contribuido significativamente a la consolidación del mismo como uno de los lenguajes predilectos para impartir los fundamentos básicos de la programación.
- `IA y Machine Learning`. Gracias a la ingente cantidad de librerías especializadas en _Inteligencia Artificial_ _(IA)_ y el _aprendizaje automático (ML)_, tales como **TensorFlow**, **PyTorch**, **Keras** y **Scikit-learn**, **Python** se ha consolidado como el lenguaje de programación predilecto para el desarrollo de modelos predictivos en un amplio abanico de sectores: medicina, robótica, videojuegos, finanzas, _procesamiento del lenguaje natural (NLP)_, _computer vision_...
- `Desarrollo de videojuegos`. Si bien la mayoría de motores de videojuegos se construyen sobre **C++** o **C#**, **Python** ha irrumpido en el sector _gaming_ cobrando una especial relevancia para el desarrollo de prototipos, juegos cortos, scripts de procesos o eventos _(como el control de la conducta de los NPC..)_ y, en relación con lo anterior, la integración de la IA en los videojuegos. Ciertos elementos de **Civilization IV**, **Battlefield 2** y **Eve Online** ha sido desarrollados en **Python**.
- `Automatización y Scripting`. 
- `IoT`. Desde el monitoreo y control de dispositivos _(sensores, cámaras...)_, hasta la recolección, análisis e integración de datos recogidos _(y en especial, con plataformas cloud: **AWS IoT**, Google Cloud IoT...)_, **Python** dispone de un amplio número de bibliotecas _(**RPi.GPIO**, **Adafruit_IO**, **MQTT**...)_ idóneas para el trabajo con todo tipo de dispositivos **IoT**.
- `Ciberseguridad`. Utilizado fundamentalmente para automatizar tareas periódicas _(escaneo de redes, recolección de información...)_, la escritura de _exploits_ y/o pruebas de penetración _(**Metasploit**, **SQLMap**...)_  y el desarrollo de herramientas destinadas al análisis de vulnerabilidades _(**requests**, **BeautifulSoup**...)_ facilitando la securización de las aplicaciones ante los ciberataques más habituales.
- `Aplicaciones empresariales`. En el sector empresarial, muchas organizaciones y sistemas _ERP_ y _CRM_ han optado por recurrir a **Python** como su lenguaje de programación base, en gran medida impulsados por sus ventajas _Open Source_. Plataformas tan populares como **Odoo** o **Tryton** son ejemplos representativos de la importante presencia del lenguaje en este ámbito.

## :wavy_dash: 4. **CLASIFICACIÓN**
Python es un lenguaje de alto nivel, multiplataforma, de licencia _Open Source_ e interpretado. Su flexibilidad posibilita un abordaje **multiparadigma**, adaptándose, en el marco de la **programación imperativa**, a los modelos **procedural** y **orientado a objetos** _(POO)_, y pudiendo admitir, a mayores, cierto grado de **programación funcional** en función de las necesidades del contexto. A pesar de poseer un **tipado dinámico**, que admite el cambio del tipo de datos almacenado en una variable _(especificado en tiempo de ejecución)_, si bien, a su vez, presenta un **tipado fuerte**, restringiendo las operaciones que pueden ser realizadas entre tipos incompatibles _(impidiendo, por ejemplo, llevar a cabo operaciones matemáticas entre una cadena y un valor tipo numérico)_. 


## :wavy_dash: 5. **OTRAS CURIOSIDADES**
- El nombre del lenguaje está inspirando en el programa de la _BBC_ **“Monty Python´s Flying Circus”**, del que Guido Van Rossum se consideraba un gran fan. [^]

- **Python** fue publicado Existe una falsa tendencia a considerar **Python** como un lenguaje relativamente Fue publicado 4 años antes que **Java**, aunque 
- >REVISAR: En una encuesta realizada en 2015, superó en popularidad al Francés como lenguaje de preferencia para el aprendizaje.

- Cuando el intérprete de **Python** recibe la instrucción `import antigravity`, se redirige al usuario a una página web en la que se reproduce un [pequeño fragmento de cómic sobre el lenguaje](https://xkcd.com/353/), a modo de _easter egg_.
- De igual, forma, puede leerse un poema escrito por _Tim Peters_, un gran contribuidor de la comunidad de **Python**, al realizar un `import this`.
- Está considerado uno de los 9 lenguajes que influyeron en el desarrollo de **JavaScript** [^https://exploringjs.com/js/book/ch_nature.html], concretamente, en lo referente a los _Generators_.


## :wavy_dash: 6. **IDE’s**

- `IDLE`[https://docs.python.org/3/library/idle.html]. _Integrated Development and Learning Environment_. _Open Source_. **Multiplataforma**. Entorno de desarrollo incorporado por defecto en la implementación estándar de **Python** desde la release `1.5.2b1`. Utilizado con frecuencia por principantes o en entornos educativos debido a su sencillez _(carece de ciertas características avanzadas, como la posibilidad de introducir breaking points en el proceso de depuración ni dispone de una terminal integrada)_ y facilidad de uso. 
- `Pycharm`. _Freemium_. **Multiplatafomra**. Creado por _JetBrains_, se oferta como un _IDE_ especialmente preparado para el campo de la ciencia de datos y el desarrollo web. Dispone de una _IA_ integrada capaz de generar documentación y bloques de código completos en función del contexto en el que se enmarca, así como opciones de depuración avanzadas (visualización interactiva de datos durante el proceso, depuración asíncrona...).
- `Jupyter`[https://docs.jupyter.org/en/latest/what_is_jupyter.html]. _Open Source_. **Multiplataforma**. _Project Jupyter_. Muy popular en el campo de la ciencia de datos y el _machine learning_, este particular entorno integrado en el navegador proporciona algunas características esenciales tales como resaltado de sintaxis, autocompletado, depuración, etcétera.
- `Spyder`[https://www.spyder-ide.org/about]. _Open Source_. **Multiplataforma**. Incluído por defecto en la distribución **Anaconda** de **Python**. Desarrollado de forma comunitaria, **Spyder** se consolida como uno de los IDE's predilectos para el desarrollo científico, facilitando la interpretación de los datos al posibilitar la visualización de las representaciones gráficas generadas directamente en el programa. 
- `NetBeans`. _Open Source_. **Multiplataforma**. Originalmente desarrollado por _Sun Microsystems_, y posteriormente donado a la _Apache Software Foundation_, **Apache NetBeans** se considera uno de los _IDE's_ más utilizados para el desarrrollo de software en múltiples lenguajes, que, a mayores de ofrecer las habituales funcionalidades de edición _(autocompletado, refactorización...)_ y depuración _(breakpoints, ejecución paso a paso..)_, soporta _frameworks_ destinados al **desarrollo web** como **Django**, resultando especialmente apto para los proyectos enmarcados en este campo. 
- `Visual Studio Code`. _Open Source_. **Multiplataforma**. _Propiedad de **Microsoft**_. [https://pypl.github.io/IDE.html] Posicionado como el segundo _IDE_ más popular del momento, dispone de una extensión para trabajar con **Python**, proporcionando, además de las características generales disponibles para todos los lenguajes _(autocompletado de código, depuración interactiva o con breaking points, refactorización...)_ algunas funcionalidades remarcables tales como la realización de _linting_ del código _(**Pylint**, **Pyflakes**...)_ o  la integración de **Jupyter Notebooks** dentro del entorno de **Visual Studio Code**.

## :wavy_dash: 7. **FRAMEWORKS**

Python dispone de una amplia multitud de Frameworks, siendo entre ellos, los más usados (en función del número de estrellas y forks disponibles en Github):
- `Django`
- `Flask`
- `FastAPI`
- `Tornado`
- `Sanic`

## :wavy_dash: 8. **WEBGRAFÍA**
[^1]: https://survey.stackoverflow.co/2024/technology
[^2]: https://www.tiobe.com/tiobe-index/
[^3]: https://docs.python.org/3/faq/general.html#why-was-python-created-in-the-first-place
[^4]: https://homepages.cwi.nl/~steven/abc/language.html
[^5]: https://www.larazon.es/emergente/usenet-desconocido-sistema-global-discusion-internet_202310196530d38b5740dc00012b064c.html
[^6]: https://www.python.org/psf/mission/
[^8]: https://github.com/faster-cpython/cpython
[^9]: https://docs.pyscript.net/2025.3.1/

https://wiki.python.org/moin/OrganizationsUsingPython  
https://www.python.org/about/apps/
https://www.geeksforgeeks.org/history-of-python/
https://github.com/mahmoud/awesome-python-applications
https://www.datasciencesociety.net/the-evolution-and-impact-of-python-in-modern-programming/
https://dev.to/jottyjohn/python-the-language-of-the-future-38n0
https://www.geeksforgeeks.org/unknown-facts-about-python/
https://www.cygnus-software.com/papers/gamescriptinginpython.html
https://medium.com/pythoneers/10-not-so-known-facts-about-python-programming-c8c4f44dbc02
https://docs.python.org/es/3.13/using/editors.html
https://kinsta.com/blog/python-frameworks/
https://xkcd.com/353/
https://www.jetbrains.com/es-es/pycharm/
https://www.anaconda.com/docs/tools/working-with-conda/ide-tutorials/spyder  
https://netbeans.apache.org/front/main/index.html
