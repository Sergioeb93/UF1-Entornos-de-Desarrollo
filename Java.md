# Java

1. [Introducción](#wavy_dash-1-introducci%C3%B3n)
2. [Historia](#wavy_dash-2-historia)
3. [Campo de aplicación](#wavy_dash-3-campo-de-aplicaci%C3%B3n)
4. [Clasificación](#wavy_dash-4-clasificaci%C3%B3n)
5. [Otras curiosidades](#wavy_dash-5-otras-curiosidades)
6. [IDE'S](#wavy_dash-6-ides)
7. [Frameworks](#wavy_dash-7-frameworks)
8. [Webgrafía](#wavy_dash-8-webgraf%C3%ADa)

 
## :wavy_dash: 1. INTRODUCCIÓN

Desde su lanzamiento a mediados de los años 90, Java se ha consolidado como una herramienta fundamental en el desarrollo de software, llegando a liderar el índice TIOBE _(TIOBE Programming Community index)_ durante gran parte las dos primeras décadas de los 2000 [^1]. Su simplicidad y robustez, sumadas a su enorme portabilidad, han contribuído indudablemente a la popularidad del lenguaje, utilizado hoy en día para crear todo tipo de aplicaciones imaginables.

## :wavy_dash: 2. **HISTORIA**

En el verano de 1991, un equipo de ingenieros de la compañía _Sun Microsystems_ liderados por _James Gosling_, comenzarían a trabajar en _The Green Project_, un programa cuyo objetivo fundamental perseguía el desarrollo de un lenguaje de programación único que pudiera ser utilizado por cualquier sistema digital o dispositivo de electrónica de consumo. Inicialmente denominado **Oak**, el lenguaje fue rebautizado posteriormente como **Green**, si bien, tras varias reconsideraciones, terminaría por identificarse como **Java**. Bajo la promesa de poder ejecutar el mismo código en cualquier dispositivo _(**WORA**, Write Once, Run Anywhere)_, en 1996 la empresa publicaría la primera _release_ del lenguaje, **Java 1.0**. Apenas un par de meses después, la primera versión de **Java** ya se habría utilizado para crear cientos de pequeñas aplicaciones y _applets_, pudiendo vislumbrarse la popularidad que le depararía en un futuro. 

Con la llegada de **Java 2** _(originalmente denominada como J2SE 1.2)_, se incorporaron diferentes configuraciones para distintos tipos de plataformas: por un lado, **J2EE**, destinada al desarrollo aplicaciones empresariales ejecutadas en entornos de servidor, y por otro, **J2ME** optimizada para aplicaciones móvil. Desde 2006, las distintas ediciones disponibles de Java pasarían a conocerse como **Java SE** _(Java Standard Edition)_, **Java EE** _(Java Enterprise Edition, equivalente a J2EE)_, y **Java ME** _(Java Micro Edition, equivalente a J2ME)_.

Tras un par de décadas doradas, **Java** continúa postulándose como uno de los lenguajes de programación más importantes de la industria tecnológica. Los cambios surgidos en el sector de desarrollo de software _(arquitectura de microservicios, cloud computing, Machine Learning, Inteligencia Artificial..)_, determinarán el futuro del lenguaje, exigiendo una mayor orientación hacia los datos _(con la integración de Deeplearning4j, o librerías tan populares como MOA y Weka...)_, las aplicaciones escalables _(apoyado en Spring Boot, Quarkus, Micronau...)_, la nube y la programación móvil. Gracias a la constante evolución y la introducción paulatina de mejoras por optimizar el rendimiento y la eficiencia del lenguaje _(mejoras en la velocidad y consumo de memoria, desarrollo de iniciativas para mejorar la concurrencia o la interoperabilidad del código nativo como Project Loom y Project Valhalla, etc..)_, **Java** continuará desempeñando un papel crucial en la industria del software durante los próximos años.

## :wavy_dash: 3. **CAMPO DE APLICACIÓN**
- `Aplicaciones móviles`. Lenguaje principal para _Android_ antes de la llegada de **Kotlin**. Actualmente, muchas aplicaciones móviles todavía se desarrollan en **Java**.
- `Desarrollo Web`. Ampliamente utilizado en el backend de muchas aplicaciones web.
- `Software de escritorio`
- `Programación de videojuegos`
- `Cloud computing`. 
- `IoT`
- `Aplicaciones empresariales`. Muy utilizado para el desarrollo de sistemas de gestión empresariales, ERPs y CRMs.
- `Ciberseguridad`.

## :wavy_dash: 4. **CLASIFICACIÓN**
Java se consolida como un lenguaje de alto nivel y propósito general, que se encuentra enmarcado en el paradigma de la Programación Orientada a Objetos. Se trata de un lenguaje multiplataforma de ejecución híbrida, requiriendo de un proceso de compilación previo _(valiéndose del compilador **javac**)_ que genera como resultado un fichero de _bytecode_ que habrá de ser interpretado posteriormente por una máquina virtual _(la **Java Virtual Machine** o **JVM**)_ y traducido al SO pertinente.
Asimismo, posee un tipado estático, y fuerte.


## :wavy_dash: 5. **OTRAS CURIOSIDADES**
- El videojuego más vendido de todos los tiempos, **Minecraft**, de _Mojang Studios_, está enteramente programado en **Java**.
- Recibe su nombre del amor que profesaba _James Gosling_, su creador, por el café, en honor a la isla indonesia en la que se considera que crecen los mejores granos de café.
- El _backend_ de empresas tan populares como **Spotify**, **eBay** o **Netflix** se apoya fundamentalemnte en **Java**.
- Los primeros 4 _bytes_ que permiten identificar un fichero `.class` válido almacenan el _magic number_ `0xCAFEBABE`.
- En los años 90, **Microsoft** lanzó su propia implementación de **Java**, **Microsoft Visual J++**, destinada a integrarse específicamente con el _Sistema Operativo_ de la compañía. Las modificaciones introducidas, incompatibles con el estándar multiplataforma definido en los términos de licencia establecidos por _Sun Microsystems_, costarían una demanda y el posterior cese en el desarrollo de la tecnología.
- El nombre Java no fue elegido porque suena bien, sino porque el equipo de desarrollo siempre estaba tomando café (de hecho, se pensaba llamar "Silk", pero Java encajaba mejor). Además, el logo de la taza de café se convirtió en un símbolo mundialmente reconocido.
- Java fue originalmente pensado para dispositivos pequeños, pero su verdadero éxito vino con las aplicaciones grandes. Aunque Java tiene un montón de herramientas y frameworks para hacer aplicaciones de escritorio, se usa muchísimo más para backend, es decir, en servidores.

## :wavy_dash: 6. **IDE’s**

- **[Eclipse](https://www.eclipse.org/)**  
  Uno de los IDE más populares para Java, extensible mediante plugins y con soporte para múltiples lenguajes de programación.

- **[Apache NetBeans](https://netbeans.apache.org/)**  
  IDE gratuito y de código abierto, ideal para desarrollo en Java, con integración nativa para tecnologías como Maven y Git.

- **[IntelliJ IDEA](https://www.jetbrains.com/idea/)**  
  Conocido por su inteligencia artificial avanzada y productividad, es uno de los IDE más potentes para Java y otros lenguajes.

- **[Visual Studio Code](https://code.visualstudio.com/)**  
  Editor ligero y altamente personalizable, con soporte para Java mediante extensiones y ampliamente utilizado para desarrollo web.

- **[BlueJ](https://www.bluej.org/)**  
  Diseñado específicamente para principiantes en Java, con una interfaz simple y enfocado en la enseñanza de programación orientada a objetos.
![image](https://github.com/user-attachments/assets/03ce1deb-8052-403e-8df5-4a4d3ff3404f)

## :wavy_dash: 7. **FRAMEWORKS**

Existen una amplia variedad de Frameworks disponibles para trabajar con **Java**, siendo los más populares:

- **[Spring Boot](https://spring.io/projects/spring-boot)**  
  Framework líder para crear aplicaciones Java empresariales de manera rápida y eficiente, con enfoque en la configuración automática y la productividad.

- **[Hibernate](https://hibernate.org/)**  
  Herramienta de mapeo objeto-relacional (ORM) que simplifica la interacción con bases de datos, permitiendo trabajar con objetos en lugar de consultas SQL directas.

- **[Struts](https://struts.apache.org/)**  
  Framework de desarrollo web basado en el patrón MVC (Modelo-Vista-Controlador), ideal para aplicaciones web robustas y escalables.

- **[Java Server Faces (JSF)](https://javaserverfaces.github.io/)**  
  Framework de interfaz de usuario para aplicaciones web basadas en Java, con componentes reutilizables y soporte para aplicaciones empresariales.

- **[Quarkus](https://quarkus.io/)**  
  Framework moderno diseñado para aplicaciones nativas en la nube, optimizado para contenedores y entornos serverless, con tiempos de arranque ultra rápidos.

- **[Play Framework](https://www.playframework.com/)**  
  Framework web y de microservicios altamente escalable, con enfoque en la productividad y la construcción de aplicaciones reactivas y modernas.

## :wavy_dash: 8. **WEBGRAFÍA**
[^1]: https://www.tiobe.com/tiobe-index/     
https://azure.microsoft.com/es-es/resources/cloud-computing-dictionary/what-is-java-programming-language     
https://docs.oracle.com/javaee/6/firstcup/doc/gkhoy.html
https://www.java.com/es/download/help/whatis_java.html  
https://www.java.com/releases/    
https://www.youtube.com/watch?v=NA-sB3zvluE&t=1  
https://www.linkedin.com/pulse/future-java-full-stack-development-whats-coming-2025-croma-campus-qq1vc/  
https://docs.oracle.com/javase/specs/jls/se23/jls23.pdf      
https://www.w3schools.com/java/java_intro.asp     
https://microsoft.fandom.com/wiki/Visual_J%2B%2B    
https://radio-weblogs.com/0100490/2003/01/28.html?ref=cafeba.be        
https://survey.stackoverflow.co/2024/technology#1-web-frameworks-and-technologies  
https://wiki.openjdk.org/display/loom/Main
