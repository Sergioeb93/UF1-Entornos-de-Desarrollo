# UF1-Entornos-de-Desarrollo
Práctica UF1 Entornos de Desarrollo LaSalle

---

## Entornos de Desarrollo Integrados (IDE)
Es un programa con el que puedes escribir, probar y ejecutar código de forma efectiva, proporciona las herramientas necesarias para desarrollar Software.

Generalmente, un IDE se compone de:
- **Un Editor de Código**: Como un procesador de texto para escribir código
- **Compilador o Intérprete**: Para ejecutar el código
- **Debugger**: Para detectar y corregir errores del código
- **File Browser**: Para gestionar archivos dentro de un proyecto


Si no tuvieramos los IDEs (como antiguamente), deberíamos escribir el código en un editor de texto sin ningun tipo de ayuda visual. Luego, para compilar el código deberíamos hacerlo manualmente escribiendo una serie de comandos. Si había algún tipo de error, se tenía que ejecutar por separado y analizarlos uno a uno. Lo que lo hacía todo un proceso más lento y complicado.

Con los IDE se nos simplifica mucho la tarea de programar al integrar en un solo lugar la escritura, la compilación y ejecución del código permitiendo así encontrar y corregir los errores de forma rápida y eficiente sin tantas complicaciones y organizar los proyectos fácilmente.

Existen muchos IDE hoy en día, también en función del lenguaje de programación que queramos usar, las características de nuestro proyecto... Algunos ejemplos son: *IntelliJ IDEA*, *Android Studio, Xcode, Eclipse o Microsoft Visual Studio*.

Los IDE tienen características que automatizan y facilitan el proceso de programación. A continuación mostraremos unos ejemplos de estas características en el IDE de InstelliJ IDEA:
- **Autoformatear**: Tabula de forma automática el código para principalmente mayor entendimiento de este.
- **Autocompletar**: Predice el código poniéndolo como sugerencia para mayor rapidez al escribir, reduciendo así también posibles errores gramaticales.
- **Generar Código**: Genera código automáticamente, en vez de escribirlo manualmente. Así agiliza la escritura del código sobretodo para estructura repetitivas. Es ideal por ejemplo para crear *constructores, getters, setters, toString(), etc.*
- ***Live Templates***: Son plantillas o partes de un código los cuales podemos escribir con una abreviatura, por ejemplo escribiendo simplemente sout ya tenemos el método `System.out.println()`. Básicamente sirve para escribir código repetitivo de forma más rápida.
- **Comentarios**: Es parte del código el cual no se ejectua. Y sirve para organizar el código, explicarlo y hacerlo más entendible y añadir notas. Para seleccionar que parte es comentario se añade `//` en la línea de código, y `/*`[comentario]`*/`. Incluso se puede añadir comentarios especiales como el *TODO:* para marcar "tareas" en un futuro o el *FIXME:* para marcar partes del código que faltan por arreglar.

Estas son unas pocas características útiles de las que dispone IntelliJ IDEA para aumentar la productividad y facilitar el desarrollo pero existen muchísimas más, como la refactorización, la depuración, la búsqueda avanzanda...

---

## Frameworks

---

### Historia de Java

Java nació en 1991 como un proyecto dentro de Sun Microsystems. En ese momento se llamaba "Oak" y se pensaba en un lenguaje para dispositivos pequeños, como cajas decodificadoras de TV. Pero pronto se dieron cuenta de que Internet estaba tomando mucha fuerza, así que decidieron redirigirlo a la programación para la web. Así fue como nació Java, un nombre inspirado por el café que siempre tomaban los desarrolladores.

El primer Java, Java 1.0, se lanzó en 1996. Desde entonces ha ido evolucionando con mejoras en seguridad, rendimiento y nuevas características. En 2010, Oracle compró Sun Microsystems y, desde entonces, Oracle se encarga de Java. A pesar de los años, Java sigue siendo muy popular y se está adaptando para trabajar bien con nuevas tecnologías como los microservicios.

---

### Campo de Aplicación Principal

Java es un lenguaje súper versátil, pero donde realmente brilla es en aplicaciones que necesitan ser fuertes, seguras y escalables. Es muy usado en sistemas empresariales grandes, aplicaciones móviles en Android y en servidores.

### Ejemplos reales:

1. **Android**: La mayoría de las aplicaciones móviles de Android están escritas en Java (aunque ahora también se usa mucho Kotlin).
2. **Bancos**: Grandes bancos como JPMorgan Chase usan Java en sus sistemas porque es confiable y robusto.
3. **LinkedIn**: La red social profesional utiliza Java para manejar la enorme cantidad de datos y usuarios.
4. **JavaFX**: Un proyecto de Java para aplicaciones de escritorio con interfaces gráficas ricas, pero no despegó mucho.

---

### Tipado de las Variables, Paradigmas y Ejecución

Java es un lenguaje estáticamente tipado, lo que significa que debes declarar el tipo de las variables antes de usarlas (como `int`, `String`, etc.). Esto puede sonar algo rígido, pero ayuda a evitar errores y hace que el código sea más seguro.

En cuanto a los paradigmas de programación, Java es orientado a objetos. Esto quiere decir que el código se organiza alrededor de objetos (cosas como personas, coches, empleados, etc.) y clases (plantillas para esos objetos). Pero también puedes usar algunas técnicas de programación funcional, como las expresiones lambda y los streams desde la versión 8 de Java.

En cuanto a la ejecución, Java usa un enfoque híbrido: el código se compila a bytecode (un formato intermedio) y luego la Java Virtual Machine (JVM) lo interpreta. Esto le da a Java su característica más famosa: "Escribe una vez, ejecuta en cualquier lugar", ya que puedes ejecutar Java en casi cualquier dispositivo sin tener que preocuparte por la plataforma.

---

### Curiosidades

Un dato curioso es que el nombre Java no fue elegido porque suena "cool", sino porque el equipo de desarrollo siempre estaba tomando café (de hecho, se pensaba llamar "Silk", pero Java encajaba mejor). Además, el logo de la taza de café se convirtió en un símbolo mundialmente reconocido.

Otra curiosidad es que Java fue originalmente pensado para dispositivos pequeños, pero su verdadero éxito vino con las aplicaciones grandes. Algo gracioso es que, aunque Java tiene un montón de herramientas y frameworks para hacer aplicaciones de escritorio, se usa muchísimo más para backend, es decir, en servidores.

---

### IDEs

- **IntelliJ IDEA**: Este IDE es muy popular entre los desarrolladores de Java por su facilidad de uso y funciones inteligentes que ayudan a escribir código rápido.
- **Eclipse**: Es uno de los IDEs más conocidos para Java, usado mucho para desarrollo de aplicaciones grandes.
- **NetBeans**: Otro IDE para Java, más orientado a aplicaciones de escritorio o sistemas pequeños.

### Frameworks

- **Spring Framework**: El Spring es el framework más popular de Java. Sirve para todo tipo de aplicaciones, desde microservicios hasta aplicaciones web y backend.
- **Hibernate**: Si necesitas trabajar con bases de datos, Hibernate es tu amigo, ya que convierte el código Java en algo que se pueda entender en una base de datos.
- **JavaFX**: Un framework para hacer aplicaciones de escritorio con interfaces gráficas, aunque no tuvo tanto éxito como se esperaba.

---

### Empresa Detrás y Licencias

El responsable de Java hoy en día es Oracle Corporation. Aunque Java comenzó con Sun Microsystems, Oracle compró la compañía en 2010, y desde entonces son los que mantienen y desarrollan el lenguaje.

En cuanto a las licencias, Java se distribuye bajo una licencia GPL, lo que significa que es gratis para usar y modificar. Sin embargo, si eres una empresa que necesita soporte, hay una versión comercial de Java llamada Oracle JDK, que tiene un costo.

---

### Características Destacables

1. **Portabilidad**: Java sigue siendo uno de los pocos lenguajes que puede ejecutarse en casi cualquier sistema operativo gracias a la JVM.
2. **Seguridad**: Java es conocido por ser seguro, con características como el sandboxing, que ayuda a proteger las aplicaciones contra virus y hackers.
3. **Escalabilidad**: Empresas grandes lo usan porque permite crear sistemas que pueden manejar mucho tráfico y gran cantidad de datos.
4. **Multihilo**: Java permite trabajar con multihilos (hacer muchas cosas al mismo tiempo), lo cual es esencial en aplicaciones de alto rendimiento.
5. **Comunidad gigante**: Al ser un lenguaje tan popular, siempre encontrarás soporte y recursos para aprender o resolver problemas.

---

En resumen, Java sigue siendo un lenguaje de alto rendimiento y confiable, ideal para proyectos de gran escala, aunque hoy en día convive con otros lenguajes como Kotlin para Android o Python para desarrollo web.
