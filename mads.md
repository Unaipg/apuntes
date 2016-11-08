<center>

# Resumen MADS
## Metodologías Ágiles de Desarrollo software

____
</center>
# Bloque 1: Valores y principios ágiles para el desarrollo del software

### 1. Características del desarrollo software
El desarrollo de software es algo único y tiene sus peculiaridades a pesar de que se intente comparar con otras cosas. La metáfora del software como construcción ha sido especialmente dañina ya que el desarrollo software no es predecible.

El desarrollo software es una actividad totalmente nueva en la historia y es la actividad más compleja que existe. El software es **fácilmente modificable, flexible, reutilizable, publicable y complejo a nivel de dependencias** y todas estas características llevan a:

* Problemas: Bugs, problemas de desarrollo entre equipos, malentendidos.
* Ventajas: Diseño evolutivo del producto, adaptación al cambio.

Hay cada vez más herramientas para controlar el cambio:

* Herramientas de refactorización en los IDEs
* Sistemas de control de versiones como Git

#### El desarrollo del software no es una ingeniería tradicional

Las ingenierías tradicionales tienen metodologías de desarrollo basadas en la planificación exhaustiva:
* El diseño es complicado y creativo
* La construcción es directa a partir del diseño
* El coste de construcción es enorme en comparación con el coste de diseño.

Mientras que el desarrollo software es muy distinto
* EL coste del desarrollo es bajo
* Los diagramas de diseño(UML) son poco expresivos tanto para el usuario final, que no puede validar el diseño, como para los desarrolladores.
* El software es intangible y no se puede apreciar su valor hasta que no es utilizado por usuarios finales
* El desarrollo software es un proceso **no predecible**

#### Las cuatro dimensiones de un proyecto software
Un proyecto exitoso es el resultado de una buena combinación de estos cuatro elementos:
* Personal:
    * Composición, motivación, capacidad, preparación y formación
    * Se pueden mejorar en el proceso de reclutamiento y organización de personal
* Proceso
    * Evitar repetir el trabajo
    * Enfasis en la calidad
    * Escoger el modelo de ciclo de vida correcto
* Producto
    * Tamaño del producto
    * Características del producto
* Tecnología
    * Herramientas usadas
    * Lenguajes de programación
    * Frameworks

Cualquier cambio en uno de estos elementos sería una decisión de gran calado que se debería hacer al principio de un proyecto. En proyectos en marcha se pueden hacer ajustes y pequeños experimentos para mejorar.

#### Software como producto
* Distribución y despliegue

    La forma de despliegue tiene una influencia directa en la agilidad ya que de ello depende la manera de actualizar cambios y solucionar bugs. Esto ha cambiado mucho en los últimos años y actualmente las aplicaciones web hacen posible despliegues instantaneos de nuevas versiones.
* Uso

    El software es único no solo en su desarrollo si no en su finalidad ya que su objetivo es ser usado y aportar valor en ese uso. El software es **flexible** por lo que es complicado encontrar el diseño final y muchas veces hay que descubrir cual es mediante el esfuerzo conjunto de los equipos de diseño y desarrollo.

    Para saber el valor de una funcionalidad es necesaro que se use y dependerá de la satisfacción del cliente.

#### Calidad en el software
Se debe desarrollar software de calidad mejorando los procesos de desarrollo y el resultado final. Dos aspectos de la calidad del software son la **calidad del producto** y la **calidad del desarrollo**.

Un producto no funciona cuando:
* La aplicación solo cumple parcialmente las necesidades del usuario, faltan features, hay errores...
* La aplicación no entiende el contexto del usuario y este "tiene que pelearse con ella". (Problemas de usabilidad)

Un software está mal desarrollado cuando:
* Es lento, poco eficiente, poco robusto o contiene bugs.
* El código es poco modificable o contiene **deuda técnica**

La **deuda técnica** es el concepto de elementos que se hacen de una manera poco apropiada con el objetivo de que funcionen pero que después son difíciles de mantener y adaptar. Esta deuda habrá que afrontarla en el futuro si se continua el desarrollo del software y causará más problemas cuanto más tiempo exista.

### 2. Metodologías de desarrollo

Una metodología software define el modelo de vida del software y los roles y responsabilidades de los distintos actores que intervienen en el proceso. Además de un conjunto de reglas una metodología define ciertos valores, principios y buenas prácticas y herramientas.

**Modelo en cascada**

Se hace un fuerte énfasis en la planificación detallada y predecible donde el analisis y diseño se hacen en gran parte antes de la implementación. Cada fase del modelo genera un artefacto que es analizado y corregido antes de pasar a la siguiente fase.

Respecto a las pruebas, todas se realizan al final del desarrollo y se plantean como una verificación de que se cumplen los requerimientos. No se contempla el cambio, ni la evolución, ni la automatización de las pruebas.

**Modelo V**

En este modelo cada fase del ciclo de desarrollo define un conjunto de pruebas que deben realizarse sobre el producto final, estás pruebas se diseñan el mismo tiempo que el software en cada uno de los niveles. Es la evolución del modelo en cascada porque:
* Hace un mayor énfasis en las pruebas
* Propone distintos tipos de pruebas. De integración, unitarias...
* Existe una relación entre las fases iniciales de grano grueso y las finales de grano fino.

**Problemas de los modelos clásicos**
* Confianza excesiva en las especificaciones iniciales. Al final puede generar software que no satisface al usuario.
* Desarrollo monolítico. Que causa problemas con cambios y mantenimiento.
* Es imposible estimar más allá de 6 meses. Estimaciones mayores llevan a retrasos.
* Exceso de documentación inútil. El objetivo final del desarrollo es software que funciona, no pilas de documentos y diagramas.

**Fundamentos de la propuesta ágil**

El **modelo en espiral** es el antecesor de los modelos ágiles. En el se aprovecha la característica de que el software es fácilmente modificable.

En cada una de las iteraciones se añaden nuevas funcionalidades o si es necesario se refina alguna de las ya existentes. Al final de cada iteración del modelo en espiral se obtenía un prototipo, lo cual permitía tener una retroalimentación rápida y determinar cuales son las funcionalidades válidas y cuales no. Además también permite mejorar la estimación del tiempo que se va a necesitar y el cliente puede probar el prototipo para indicar posibles modificaciones.

La **propuesta ágil** se basa en
* Ciclos cortos que incorporan todas las fases de vida del proyecto.
* Retroalimentación temprana para dirigir mejor la evolución del proyecto.

### 3. ¿Qué es ágil?
En las metodologías ágiles el objetivo del desarrollo es resolver un problema, por lo que incluye también un proceso de exploración de necesidades mediante la comunicación continua.

Estas metodologías comprenden que el cambio es inevitable, tanto durante el proyecto en forma de incertidumbre y modificaciones de los requisitos al ver los resultados, como una vez terminado el proyecto en forma de mantenimiento y modificaciones debidos a cambios en el proceso de negocio.

**La realidad del desarrollo**

| **Lo que nos gustaría** | **La realidad**|
|-------------------------|----------------|
|Los clientes saben lo que quieren|Los clientes descubren lo que necesitan|
|El equipo sabe como construirlo|Los desarrolladores descubren como hacerlo|
|Nada cambiará en el camino|Muchas cosas cambian en el camino|
|Hay mucho tiempo y dinero para hacerlo|Hay más cosas que hacer que tiempo y dinero disponible|

Por estos motivos es fundamental utilizar herramientas, frameworks y diseño de código que permita introducir cambios fácilmente y también diseñar y ejecutar tests de los distintos módulos y funcionalidades del producto conforme se va desarrollando.

**Desarrollo incremental**

Todas las metodologías utilizan iteraciones cortas en las que al final de cada iteración debe haberse avanzado en el desarrollo del producto software y debe existir un conjunto de _features_ que antes no existían y se integran correctamente con las ya existentes.

Un modelo ágil debe permitir la integración rápida de las nuevas características en el producto software existente.

#### Principios ágiles
* Satisfacer al cliente con entrega rápida de software útil
* Entrega frecuente de software funcional
* La simplicidad es esencial, se intenta minimizar la cantidad de trabajo
* Las iteraciones cortas entregan valor al cliente y permiten obtener feedback para el equipo.

Cuando se hace un desarrollo incremental se deben uncluir en cada incremento todas las capas de la aplicación para que el cliente pueda comprobar la aplicación. Se deben descomponer las funcionalidades grandes en funcionalidades más pequeñas pero todas deben tener todas las capas de la aplicación.

**Producto mínimo viable**

Se trata de una idea para construir startups que se puede aplicar al desarrollo software en la que se intenta hacer primero lo que más incertidumbre genera. También se basa en las **mejoras incrementales** que permiten mantener una velocidad constantes y hacer mejores estimaciones.

**Algunas metodologías ágiles**
* Extreme programming - Valores y prácticas
* Scrum - Ciclo de desarrollo
* Lean / kanban - Mejora continua, flujo

No hay una metodología que sea la mejor y se pueda aplicar siempre. Además estas metodologías están empezando a ser aplicadas en muchas empresas y la mayoría de las veces ni siquiera se aplican de manera correcta.

**Continous delivery**

La entrega continua es la respuesta a las prácticas tradicionales en las que la integración y el despliegue se hace al final del proceso de desarrollo de manera manual y costosa. Muchas de estas ideas vienen del desarrollo open source. Los principios de la entrega continua son:
* Crear un proceso de release repetible y fiable
* Automatizar todo lo que sea posible
* Mantener todo bajo el control de versiones
* Si duele hacerlo con más frecuencia
* introducir calidad en el sistema
* Hecho significa lanzado
* Todo el mundo es responsable del proceso de entrega
* Mejora continua

___
## Manifiesto ágil

En el año 2001 habían muchas propuestas al modelo de desarrollo en cascada que en aquellos momento se denominaban ligeras(lightweight). En febrero de 2001 un grupo de 17 desarrolladores muy activos en estas tecnologías re reunieron con la idea inicial de entender mejor los enfoques de cada uno. En esta reunión se redactó un manifiesto y se acordó el apartado de los valores y el nombre que se usaría para este conjunto de técnicas: **Ágiles**

Todas estas prácticas tienen sentido en el marco de un conjunto de valores y principios en lugar de ser una manera dogmática de trabajo. Además estos valores deben ser compartidos por toda la empresa, no solo el equipo de desarrollo. Si se intentan copiar las metodologías ágiles sin aplicar estos principios se llega a una repetición ritual que no aporta nada.

<center>

| **Gestor de proyectos** | **Lider del equipo**|**Desarrollador** | **Product owner**|
|-------------------------|----------------|------------------|--------|
|Tablero de tareas|Planning pocker|Refactorización|Backlog del producto|
|Puntos de historia|Retrospectivas|Programación por parejas|Item del backlog|
|Diagramas de quemado|Comunicación osmótica|Integración continua|Historias de usuario|
|Diagramas de flujo acumulado|Sentarse juntos|Sistemas de control de versiones|Ranking relativo|
|Velocidad del proyecto|Servan leadership|Desarrollo dirigido por tests|Iteración|
|Estimación|||Release|
|Temas||||
|Priorización|||||

</center>

**Valores del manifiesto ágil**
* Individuos e interacciones sobre procesos y herramientas
    * Es importante fijarse en los miembros del equipo, motivaciones y preferencias e interacciones
    * Si las personas no se comprometen con el proceso, este no funcionará
    * Más importante que la documentación es la comunicación entre el equipo.
* Software que funciona sobre documentación exhaustiva
    * El software que funciona proporciona valor
    * Hay documentación necesaria, pero se debe eliminar aquella que no lo es
    * El código es la mejor documentación. Las pruebas y los ejemplos de validación del product owner
* Colaboración con el cliente frente a negociación de un contrato
    * También se aplica dentro de la empresa
    * La flexibilidad y apertura de la colaboración permiten cometer fallos sin que nadie se sienta señalado. El objetivo es común y todos están comprometidos
    * El product owner es el miembro más importante del equipo y es tan autor como el resto del equipo.
* Responder al cambio frente a seguir un plan
    * Debe haber un plan, pero flexible y adaptable a los cambios que se puedan introducir
    * No se deben ver los cambios como errores
    * El gestor del proyecto debe estar comprobando y reaccionando continuamente, no planificar al principio

#### Los doce principios del Manifiesto Ágil

1. Our highest priority is to satisfy the customer through early and continous delivery of valuable software
    * Tres ideas: Lanzar pronto el software, entregar valor continuamente y satisfacer al cliente.
    * Es difícl entender como va a funcionar el software hasta que los clientes lo usan
    * La colaboración debe primar sobre los contratos. Una empresa puede usar software incompleto y generar valor con ello.
2. Welcome changing requirements, even late in development. Agile processes harness change for the customers competitive advantage.
    * No es fácil modificar código que ya está hecho.
    * Muchas veces los cambios vienen de cambios en el negocio o para conseguir ventajas competitivas.
    * Los cambios no son errores, son una forma de mejorar y aprender.
3. Deliver working software frequently, from a couple of weeks to a couple of months, with a preference to the shorter timescale
    * Las iteraciones pequeñas tienen ventajas. Son más fáciles de planificar, los objetivos están más claros, producen productos usables y permiten tener una visión de más alto nivel
    * No se deben perder de vista los objetivos a largo plazo. Una feature grande puede necesitar varias iteraciones.
4. Bussiness people and developers must work together daily throughout the project
    * Si el cliente no responde a los desarrolladores en poco tiempo se producen retrasos
    * La interacción permite que el equipo priorice las características de más valor.
    * Un buen product owner puede reducir la cantidad de tiempo que los equipos deben pasar comunicandose, por ejemplo preparando las reuniones.
5. Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done.
    * Si los desarrolladores no trabajan en conjunto y acusan a los demás la atmosfera de trabajo empeora
    * La motivación por el proyecto y la confianza deben fomentarse y eso es trabajo del lider del equipo
6. The most efficent and effective method of conveying information to and within a development team is face-to-face conversation.
    * Las conversaciones son más valiosas que la documentación, pero estas deben estar preparadas y ser eficientes. Si tienes que hablar con alguien prepara lo que quieres decirle.
    * El fin es crear un sentimiento de comunidad de forma que se cree conocimiento implícito que no sea necesario comunicar una y otra vez.
7. Working software is the primary messure of progress
    * La mejor manera de medir el progreso es con funcionalidades implementadas y probadas.
    * Al probar el software acabado es más fácil hacerse una idea del progreso que mirando informes y diagramas.
8. Agile processes promote sustainable development. The sponsors, developers and users should be able to maintain a constant pace indefinitely
    * No se debe caer en hacer horas extra cuando se acerca la fecha límite porque a la larga no es sostenible.
    * El desarrollo iterativo es más realista porque permite mantener el mismo ritmo durante toda la iteración y estimar mejor qué habrá hecho al final.
9. Continous attention to technical excellence and good design enhances agility
    * Se deben usar buenas técnicas, prácticas y herramientas en el desarrollo.
    * Es importante resolver los bugs tan pronto como aparezcan. Cuanto más se tarda en eliminar un bug más difícil es hacerlo.
10. Simplicity -- the art of maximizing the amount of job not done -- is essential
    * Es peor escribir código de más que borrar código.
    * Cuanto mayor sea el código más dependencias tendrá y más difícil será solucionar errores y añadir cambios.
11. The best architectures, requirements and designers emerge from self-organizing teams.
    * Lo contrario de un equipo auto-organizado es un equipo que sigue ciegamente los diseños propuestos
    * En un equipo ágil todos comparten la responsabilidad de la arquitectura del proyecto
    * En lugar de un gran diseño inicial, las características aparecen de forma incremental. Esto fuerza a usar técnicas que permitan construir el sistema poco a poco.
12. At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly.
    * Un equipo no solo debe mejorar el software, debe mejorar la manera de construir software
    * Se debe hablar de los errores y lo que se ha hecho mal de manera constructiva para mejorar. También se debe valorar lo que se ha hecho bien.

___
## Desarrollo *lean*

#### Historia de la fabricación lean
**Cadena de producción**

Típicas de la industria automovilística funciona descomponiendo el proceso en pequeños pasos especializados donde el producto se va moviendo de un paso a otro. Esto genera trabajadores fáciles de formar y fáciles de reemplazar que se especializan en hacer poco pero hacerlo bien.

El problema de este método es que genera falta de motivación en los trabajadores y que es muy rígido por lo que se tarda mucho en responder a cambios.

**Sistema de producción Toyota**

El sistema Toyota, también conocido como "just-in-time" fue el utilizado por la industria japonesa para superar a los americanos tras la segunda guerra mundial. Las características de este modelo son:
* Eliminar los desperdicios, es decir todo lo que no genera valor al cliente
* Fijar ciclos de producción cortos para no tener inventario. Se crea solo lo que se vende.
* En cuanto se detecta un error se para la cadena
* Cultura de mejora continua a todos los niveles en una empresa
* Pensar en todo el conjunto, equipos multifuncionales
* Herramientas para visualizar el proceso
* La esencia es una mentalidad basada en la mejora continua y el desarrollo de los empleados.

El objetivo de este método no es la producción en masa si no fabricar y servir el producto inmediatamente después de que el cliente hiciese el pedido. Una de las características de este modelo es que se pueden añadir cambios hasta muy tarde en el ciclo de desarrollo porque se retrasan las decisiones irreversibles todo lo posible, de esta manera cuando se toman se tiene el máximo de información.

Se ha visto que aplicar este método genera ganancias en el coste, tiempo y esfuerzo de ingeniería comparado con los métodos tradicionales.


#### Prácticas de fabricación lean

Las ideas que dan origen a los sistemas de fabricación lean son:
* El proceso siempre puede ser mejorado y los trabajadores son los que mejor pueden proponer estas mejoras
* Método científico: Los trabajadores crean hipótesis, se prueban, se analizan los resultados y si se confirma la hipótesis el cambio se hace permanente.
* Se deben identificar los distintos pasos del proceso de producció
* Una idea central es la continua eliminación de los desperdicios mediante la simplificación
* La producción se vuelve fluida cuando se eliminan los desperdicios, se mejora la calidad y el tiempo de producción y costes se reducen.
* Esta forma de trabajo genera una alta disciplina y alta respuesta al cambio
* Es una mentalidad, no un conjunto de reglas

**Desperdicios**

Son todos aquellos elementos que no añaden valor al producto. Si minimizamos los desperdicios maximizaremos la cantidad de trabajo útil que genera valor.

Ejemplos de desperdicios son la espera, el inventario, la documentación excesiva...

**Sistemas de fabricación pull**

Estos sistemas son uno de los pilares de la fabricación *lean*. El proceso se divide en un conjunto de pasos que necesitan recursos y consumen los resultados de procesos anteriores.

En los sistemas **push** se planifica antes de empezar la cantidad de trabajo y cuando el proceso anterior acaba "empuja" a la siguiente celda para que continue procesando. Esto genera en ocasiones sobrecarga de las celdas.

Al contrario, los sistemas **pull** ponen el origen del trabajo al final de la cadena, en la entrega del producto. Cada celda tiene un número máximo de productos (**WIP**) y cuando se consume uno de los productos se notifica a una celda anterior que se necesita un nuevo componente. Este sistema regula el flujo de recursos mediando un proceso de fabricación reemplazando solo lo que ha sido consumido y lo que es inmediatamente entregable.

El WIP es un término que indica el número de items que están siendo procesados en una celda o fase del proyecto. Esto obliga a que no se acepten más items una vez que se llega al WIP. Mediante el flujo de trabajo pull junto con el WIP se garantiza que no se produce sobreinventario y permite detectar de manera fácil los cuellos de botella.

**Kanban**

Una de las herramientas más importantes para organizar el proceso de producción son las **kanban**, señales visuales que implementan el sistema pull. Una kanban es una señal o ayuda visual que indica que un centro de trabajo ha finalizado un proceso, necesita trabajo o necesita más materiales.

Los **tableros kanban** permiten que los centros de trabajo hagan un seguimiento de las necesidades de los clientes o proveedores y respondan de manera rápida y adecuada.

#### Principios de Mary Poppendieck del desarrollo lean de software
Mary Poppendieck fue una de las primeras personas en proponer aplicar la filosofía lean al desarrollo software. Definió 7 principios para el desarrollo lean de software:

1. Eliminar los desperdicios
    * Producir solo lo necesario en el momento en el que se necesita. Si algo no se utiliza no podemos darnos cuenta de sus fallos.
    * Desperdicios en el desarrollo software
        * Demasiados requisitos para una release
        * Demasiada arquitectura para las necesidades actuales
        * Demasiado código para poder ser probado adecuadamente
    * Desperdicios en la creación del producto
        * Demasiadas funcionalidades para el usuario final
        * Tener que reaprender algo por falta de comunicación. Cuando alguien en el equipo aprende algo, ese conocimiento debe extenderse a todo el equipo rápidamente.
2. Fomentar la calidad
    * Construye software que tenga sentido para los usuarios y forme una unidad coherente
    * Los clientes y los usuarios suelen ser distintos. Para satisfacer al cliente hay que satisfacer al usuario
    * Minimiza la deuda técnica
        * Refactoriza siempre que tengas oportunidad
        * Haz revisiones del código
    * Haz énfasis en las pruebas para crear software sin defectos
    * Las características deben trabajar juntas para crear un producto único, integrado y fácil de usa. De esta manera se logra un software con integridad conceptual
3. Crear conocimiento
    * Hay dos tipos de conocimiento. El del producto que estamos desarrollando y el del proceso y la manera de desarrollar productos.
    * Se debe usar el feedback de los proyectos para mejorar la manera de desarrollar software. Se usan gráficas que permiten medir el proceso y encontrar cuellos de botella y se pueden cambiar cosas como la metodología, arquitectura o la tecnología.
4. Decidir lo más tarde posible
    * Toma las decisiones cuando más información disponible haya.
    * Diferencia entre compromisos y opciones, intenta que la arquitectura y el desarrollo permita maximizar las opciones.
    * Se puede añadir al desarrollo incremental donde se crea primero un nucleo mínimo y luego se van añadiendo características. Mantener una baja interdependencia es importante.
    * Se pueden hacer pruebas A/B para comprobar una característica y ver que versión del producto genera más valor.
5. Entregar rápido
    * Ciclos cortos de entrega minimizan los retrasos y los constes asociados.
    * Las entregas y desarrollos rápidos permiten proporcionar más características a los clientes y permiten que el Product Owner pueda decidir con más información.
    * Utiliza la técnica del mapa de la cadena de valor y la característica mínima promocionable.
    * La cadena de valor nos permite definir las columnas del tablero kanban y comprobar como se mueven las tareas en ese tablero.
    * Utiliza técnicas de entrega continua.
6. Respetar a la gente, potenciar el equipo
    * Un equipo es un conjunto de personas comprometidas con un objetivo común.
    * Establece un entorno de trabajo centrado y efectivo que genera un trabajo sostenible.
    * Evita heroes que meten muchas horas y sacan el trabajo ellos solos.
    * Respeto entre los compañeros.
7. Optimizar el conjunto
    * Todo el equipo debe tener claro el objetivo final dle proyecto y como el software va a añadir valor al usuario final
    * Los contratos deben basarse en la confianza.

**Diagrama de flujo acumulativo**

Se cuenta semana a semana cuantos items se terminan en esa fase del desarrollo y se anota el incremento en el diagrama. De esta forma se pueden hacer un diagrama de fluja de las historias de usuario acabadas que nos permitirá estimar la velocidad de desarrollo. Esta velocidad permite estimar el número de tareas realizadas en una fecha determinada.

Otro concepto importante es el **cycle time** o **lead time**, el tiempo medio que tarda en completarse una funcionalidad.

---
## Bloque 2: Integración y entrega continua


### Pruebas Ágiles

Hay dos enfoques complementarios de los tests.

Enfoque tradicional basado en QA que sirve para comprobar que no hay bugs y probar que el código hace lo especificado. En este enfoque primero se especifica, luego se codifica y por último se prueba.

Enfoque basado en TDD, XP y metodolofías ágiles en el que los tests ayudan a especificar el desarrollo y son ejemplos de funcionamiento que indican como debe funcionar el código. Los tests se diseñan a la vez que la especificación y por último se codifica.

#### Elementos de los tests

Las partes de la ejecución de un test son:
1. Crear un estado de comienzo definido
2. Ejecutar código de prueba que llama al método a probar
3. Comprobar que el estado final se corresponde con el esperado
4. Limpiar

El punto 1 es clave. Si es fácil crear un estado de comienzo definido sin dependencias y solo con algunos parámetros será un **test unitario** mientras que si se deben configurar elementos externos y el resultado afecta a más de un componente tendremos un **test de integración**.

Existen técnicas de programación como el mocking o la inyección de dependencias que permiten sustituir los elementos externos del código a probar para probarlos como tests unitarios.

**Tipos de test**

* **Tests unitarios**: Prueban la funcionalidad del código en partes del código que no interactuan con elementos externos. Se usan stubs y mocks para sustituir los recursos externos y se ejecutan en el entorno del desarrollador.
* **Tests de integración**: Prueban la funcionalidad del código que depende de recursos externos y se ejecutan en entornos preparados que requieren una configuración especial.
* **Tests funcionales**: Tests que simulan los usuarios finales
* **Pruebas de stress**: Prueban el rendimiento del sistema

**Unit tests**

En XP y TDD se tiene una visión relajada del nivel de aislamiento que tiene que tener un test unitario
* Invoca una funcionalidad concreta y realiza una única comprobación sobre la conducta de esa funcionalidad.
* La unidad a probar puede llamar a otras unidades(que tendrán que haber sido probadas).
* Debe ser repetible e independiente y debe probar un pequeño incremento de la funcionalidad del sistema.
* Debe poder ejecutarse en local y ser independiente de otros desarrollos.
* Debe ser sencillo, legible y mantenible.

Mientras que en una visión estricta:
* Debe probar una clase aislada del resto.
* Se deben realizar sobre clases aisladas en las que se sustituyen las relaciones con otras clases por stubs o mocks
* Si falla sabemos claramente cual es la clase responsable.
* Visión orientada a pruebas entendida como control de calidad.

Si un test no es unitario se puede convertir en unitario incluyendo mocks en el código a probar que sustituyen los objetos reales.

**Tests automatizados**

Los tests automatizados deben ser:
* Rápidos, sobre todo los unitarios, hay que tener en cuenta que pueden llegar a ser miles de tests que se ejecutan muchas veces.
* Aislados, un test no debe depender de otros y deben poder ejecutarse en orden distinto.
* Atómicos, cada test solo debe probar una cosa.



#### TDD, Test Driven Development

Es una práctica de desarrollo dentro de XP aunque se puede utilizar en cualquier otra metodología. El proceso de desarrollo tiene tres fases:
1. Escribir un test que compruebe la funcionalidad que se va a añadir. Debe fallar.
2. Escribir un código que haga que el test funcione, aunque sea una solución sucia.
3. Refactorizar el código.

**Principios**

Las pruebas sirven para especificar el código a desarrollar.

El primer paso es saber como probar la funcionalidad centrándonos en las entradas y salidas de la unidad a probar, no en como se realiza su implementación, de esta manera esas pruebas serán la mejor documentación de como funciona el código.

Las pruebas permiten fijar algo en el código ya que el código puede cambiarse siempre y cuando pase todas las pruebas.

Tres reglas del Tío Bob
1. No está permitido escribir código para producción a menos que sea para hacer pasar un test que falla.
2. No está permitido escribir más de un test que falle.
3. No está permitido escribir más código del que sea suficiente para pasar un test que falla.

**Consecuencias del TDD**

El TDD genera una sensación de seguridad y permite refactorizar sin miedo. Además el resultado de la codificación no es solo código, es código y las pruebas necesarias para asegurarse de que funciona correctamente. Esta metodología obliga a reflexionar sobre la funcionalidad del código en lugar de la implementación.

**Pruebas Bottom-up y Top-down**

Estas pruebas se diferencian en la forma de construir los tests del sistema.
* Bottom-up
    * Se prueban y construyen componentes elementales.
    * Las pruebas de funcionalidades de mayor nivel no necesitan mocks ni stubs porque los elementos básicos ya están construidos y probados.
    * El diseño OO tiende a crecer orgánicamente a partir de un punto de partida inicial mediante la refactorización.
* Top-down
    * Se construyen tests que prueban funcionalidades sin tener todavía implementados los componentes.
    * En una primera fase se usan stubs y mocks para probar las conexiones entre los componentes no implementados.
    * Después se van sustituyendo los stubs y mocks por componentes reales.
    * Se prueba desde el principio en un diseño OO bien definido.

**Estrategias para hacerlo verde**

* Para hacer el test **verde** se puede falsear el código haciendo que devuelva valores a establecidos a mano y refactorizar hasta que se tenga la funcionalidad.
* Siempre que se puede se implementa y se prueba código real.
* Solo se generaliza el código si hay más de un ejemplo que lo requieren

**ATDD: Acceptance TDD**

Se diseñan los tests de aceptación a partir de historias de usuario. Una condición de satisfacción es un test de aceptación de alto nivel que debe completarse para marcar la historia de usuario como terminada.

#### Testing en equipos ágiles
En el desarrollo tradicional el equipo de pruebas está totalmente separado del equipo de desarrollo. Los testers suelen ser personas con menor formación que los desarrolladores que se dedican a encontrar bugs antes que los usuarios finales. Este proceso de testing se hace al final de la fase de desarrollo para asegurarse de que el producto final está libre de errores.

En los equipos ágiles sin embargo los desarrolladores son también los que hacen el papel de testers y en caso de haber testers especializados se integran con el equipo y trabajan durante todo el proceso de desarrollo del software. Para esto hacen:

* Proceso incremental e iterativo
* Pasos pequeños.
* Suite de tests automatizados.
* Revisiones de código.
* Usar nuestros productos nosotros mismos. Dogfooding
* Monitorización.

#### Testing e integración continua

**Entornos de prueba**

Habitualmente se habla de 4 tipos de entornos:
* Local: El utilizado por los desarrolladores.
* Integración: Donde se lanzan los tests de integración.
* Stage: Es un entorno similar a producción donde se realizan pruebas manuales.
* Producción.

**Herramientas**

Servidor de integración continua: Es una máquina que monitoriza constantemente el estado del repositorio del proyecto lanzando todos los tests en las distintas configuraciones y proporcionando informes y notificaciones del estado. Una de las aplicaciones más conocidas para este cometido es **Jenkins**

Sistema de seguimiento de incidencias: También llamado Bug Tracking es un sistema que complementa a los tableros Kanban y Scrum capturando y almacenando la información de los bugs además de guardando un histórico. También permite una mejor comunicación entre los equipos.

---
### Integración y entrega continua

#### Introducción
Aunque se utilicen metodologías ágiles en el equipo de desarrollo, un desarrollo software incluye mucho más que el desarrollo del software en si, además se debe hacer ágil el proceso de testing y despliegue. No comulga con los valores ágiles que haya grandes tiempos de despliegue o de integración entre software creado por varios equipos.

Los desafios a los que se enfrenta un equipo ágil respecto a la integración y despliegue son:
* Desarrollo de código. ¿Como desarrollar software de forma que el código se integre continuamente?
    * Sistemas de control de versiones.
    * Políticas de desarrollo e integración.
    * Políticas de revisión de código.
* Servidores de integración, pruebas y despliegue automatizado. ¿Como automatizar la construcción, prueba y despliegue?
    * Herramientas de virtualización.
    * Herramientas de gestión de actualizaciones.
    * Software de ejecución de procesos y tareas como Jenkins.
* Incorporar nuevas funcionalidades. ¿Como decidir que características incluir y hacer que el producto evolucione?
    * Interruptor de características.
    * Abstracción que permite cambiar fácilmente las características.
    * Pruebas A/B.

#### Integración continua
La integración continua es una práctica de desarrollo que requiere que los desarrolladores integren el código en un repositorio compartido varias veces al día. Un servidor de integración realiza una build automática del repositorio compartido , lanza todos los tests y detecta los problemas de compilación o ejecución de las pruebas siempre que el código cambia. Mediante esta técnica se consigue detectar pronto los problemas de integración de los cambios desarrollados de forma independiente.

**Entornos de despliegue**

Existen diferentes entornos en los que se lanzan pruebas sobre la build de la aplicación. Ordenados de mayor a menor parecido con producción podemos encontrar normalmente:
* Local: El ordenador del desarrollador donde se ejecutan los tests unitarios.
* Desarrollo: Ordenador de integración continua donde se ejecutan los tests unitarios constantemente.
* Integración: Se sustituyen los mocks por servicios reales aunque con copias parciales de los de producción.
* Test/QA: Entornos en los que se realizan pruebas funcionales y de interfaz de usuario. Pueden ser manuales.
* Stage/Preproducción: Entorno identico al de producción donde se hace una última validación de la nueva versión a desplegar en producción. Se hacen también pruebas de rendimiento.
* Producción: Entorno que usan los clientes reales de la aplicación.

**Principios de la integración continua**
* El sistema siempre debe poder ser probado y construido con éxito.
* Todo el mundo hace merge de los cambios con frecuencia
* Después de cada commit el sistema integra inmediatamente.
* Se desarrolla el sistema en pequeños incrementos.

**Flujo de trabajo de integración continua**
* Los desarrolladores prueban su código en sus espacios de trabajo privados.
* Se mezclan los cambios en el repositorio.
* El servidor CI monitoriza el repo y comprueba cuando hay cambios.
* El servidor CI construye el sistema y ejecuta las pruebas.
* El servidor CI informa de la construcción exitosa.
* Si falla el build el servidor CI alerta al equipo.
* El equipo arregla el problema lo antes posible.


**7 Pasos**
1. Commit early, commit often.
2. Never commit broken code.
3. Fix build failures inmediately.
4. Fail fast.
5. Act on metrics.
6. Build on every target environment.
7. Create artifacts from every build.



#### Builds
Se entiende por build el conjunto de ficheros binarios y de configuración obtenidos a partir de la compilación del código fuente de un proyecto y su configuración para ser desplegado y lanzado en un entorno. Un elemento fundamental son las dependencias.

Es importante automatizar este proceso.

**¿Qué contiene un build?**

* Compilación: Se asegura de que el codigo compila en todas las plataformas objetivo.
* Ejecución de tests: Se asegura de que el producto funcione como se espera.
* Integración con la BDD: Automatiza la creación de los datos de test.
* Inspección de código: Asegura un código sano.
* Deploy automatizado: Asegura que el producto puede lanzarse en cualquier momento y permite probar el estado del producto en todo momento.
* Generación de documentación: Asegura que la documentación está al día.
* Uso de un script: Debe poder funcionar desde la linea de comandos y ser independiente del IDE.

Es conveniente mentener las dependencias externas en un repositorio local de artefactos al igual que las builds antiguas de nuestro proyecto para poder acceder a ellas sin necesidad de volver a descargarlo todo.

#### Entrega continua
Se trata de conseguir una puesta en producción del software:
* Poco arriesgada
* Frecuente.
* Barata.
* Rápida.
* Predecible.
* Reproducible

**Ventajas de la entrega continua**
* Estabilidad y confianza en el proceso de despliegue y lanzamiento
* Feedback continuo
* Cuanto antes se detecta un error más fácil es solucionarlo
* Mejora la calidad del producto.

**Técnicas de la entrega continua**

* Pequeños cambios se despliegan continuamente.
* Todos los builds son candidatos al release.
* Todo debe estar en el control de versiones.
* Tuberías de despliegue.
* Integración continua: Atomatización de buils, tests, despliegues y cambios.

**Integración de grandes cambios**

Hacer incrementos pequeños no significa que no se trabaje con características que necesiten muchas modificaciones. Es posible ir desarrollando, probando y colocando las piezas para que el sistema evolucione y que en el futuro sea fácil añadir una nueva característica. Para ello se puede utilizar:
* Un buen diseño del codigo, como por ejemplo usar factorías e interfaces. Hoy en día se usa más la inyección de dependencias en este aspecto.
* Pequeños cambios en las apis compatibles con los tests de regresión.
* Interruptores de características.

#### Tubería de despliegue
Es una implementación automatizada del proceso de construir, desplegar, probar y lanzar nuestro sistema. Una tubería de despliegue garantiza visibilidad, feedback y control.

Práctias de la tubería de despliegue:
* Solo construir los binarios una vez.
* Desplegar de la misma forma en todos los entornos.
* Smoke-Test your deployments
* Desplegar una copia en producción.
* Cada cambio debería propagarse instantaneamente por la tubería.
* Si falla cualquier parte de la tubería, parar la cadena.

**Configuración**

Una aplicación es el conjunto de los binarios, configuración y datos, cambiando cualquiera de esos elementos se puede cambiar la aplicación. Por ese motivo todos los elementos deben entrar en el sistema de gestión de versiones para poder recuperar una versión determinada.

Los ficheros de configuración determinan valores necesarios para ejecutar y probar una aplicación aunque también se puede leer la configuración de las variables de entorno del sistema. Estos ficheros modifican la aplicación en cosas como mensajes al usuario, imágenes o incluso en ocasiones comportamiento, aunque no es aconsejable.

Los objetivos de la gestión de la configuración son permitir:
* Reproducir cualquiera de nuestros entornos.
* Realizar fácilmente un cambio incremental.
* Comprobar el cambio que ha ocurrido en un entorno particular y recuperar el origen del mismo.
* Que cualquier miembro del equipo obtenga la información que necesita y pueda realizar cambios.

Los tipos de configuración que encontramos son:
* Scripts de build que pueden obtener la configuración e incorporarla a los binarios en tiempo de construcción.
* Software de empaquetado que puede inyectar la configuración en tiempo de empaquetamiento.
* Scripts de despliegue o instaladores que pueden obtener la información necesaria y pasarla a la aplicación en tiempo de despliegue o como parte del proceso de instalación.
* La aplicación puede conseguir la configuración en tiempo de arranque o en tiempo de ejecución.

**DevOps**

Los developers son los encargados de añadir nuevas características y normalmente trabajan en entornos locales. Usan herramientas y Lenguajes que permiten abstraer y automatizar.

Los trabajadores de operations son los que se encargan de mantener el sitio web seguro, rápido y estable. Son los encargados también de detectar y solucionar problemas.

La filosofía DevOps es una filosofía de trabajo donde los desarrolladores y los operadores trabajan en conjunción creando automatización con conceptos como Infrastructure-as-code.

---

## Flujos de trabajo en GIT
El primer elemento de un sistema de integración continua es un sistema de control de versiones. **Git** es un sistema de control de versiones que permite clonar repositorios en distintas máquinas, hacer cambios en la versión clonada y publicar esos cambios. Normalmente se define un repositorio compartido y uno local para cada desarrollador.

**Pull requests**

Es una funcionalidad proporcionada por servicios de Git como GitHub y Bitbucket que permiten usar la interfaz web para solicitar un merge entre ramas que residen en el servidor remoto, pudiendo estar estas ramas en distintos repositorios(haces un fork y luego haces un pull request al proyecto principal). Se pueden seguir actualizando las ramas hasta que se produce el merge y entonces la web nos ofrece la opción de borrar la rama mergeada.

**Flujos de trabajo**

Dentro de los flujos de trabajo existen varias opciones posibles. Las recomendaciones generales son:
* Una única rama de desarrollo principal, en la que todos los desarrolladores hacen commit diario.
* La rama de desarrollo se despliega diariamente en el servidor de integración continua.
* La ventaja es que los errores se encuentran rápido y hay una sensación de progreso compartido.
* Se pueden definir short-life branches en las que se trabaja unos días y se integran con la rama principal

#### GitFlow

Existen dos ramas de larga duración(long-lived): **master y develop** y múltiples ramas **feature** que deben partir de develop y ser mergeadas de nuevo con develop una vez terminadas.

Los merges se deben hacer con --no-ff para que se mantenga la información de las ramas por separado y no se integre.

Las ramas **release** deben partir de develop y mergearse con develop y master simultaneamente, en estas ramas se prepara todo lo relacionado con hacer una nueva release, como cambiar el número de versión.

Las ramas **hotfix** salen de master y se integran con develop y master. Sirven para arreglar errores.
___

## Herramientas para la integración continua

Diariamente la aplicación se integra y se ejecutan las pruebas unitarias y de integración. Es un proceso automático en el que:
* Se descarga la última versión del control de versiones
* Se lanza el script de build.
* Se publican los resultados de los tests en una página accesible a todo el equipo.

Algunas herramientas de integración continua son:
* Bamboo
* Cruise control
* Jenkins
* GO
* TravisCI

**Entornos de prueba**

La última parte de la tubería de despliegue consiste en probar los builds compilados en distintos entornos de prueba. Cada uno de estos entornos puede tener distintas configuraciones y estar formado por múltiples máquinas. Estos entornos son:
* Tests de integración y aceptación.
* UAT.
* Tests de capacidad.
* Producción.

Es esencial usar el mismo proceso de despliegue en todos los entornos. Las características diferentes de cada entorno deben estar en los ficheros de configuración, no en el script de despliegue. El script de despliegue debe configurar el entorno, desplegar los binarios y poner en marcha las aplciaciones y comprobar que funcionan.

**Gestión de entornos de prueba y producción**

Cuanto menos control tenemos sobre el código que se ejecuta más posibles son los comportamientos inesperados. Se busca tener control total sobre el entorno en el que se despliega la aplicación y que los cambios en esos entornos se realicen mediante procesos automatizados y registrados.

En cada entorno se deben definir claramente:
* Configuración.
* Software que se despliega.
* Topología de la red.
* Estado.

El objetivo final es poder hacer un despliegue con tan solo dos parámetros, el entorno de despliegue y la build a desplegar.

#### Docker

Docker es una plataforma basada en contenedores que permite entre otras cosas simplificar el despliegue de aplicaciones.
* Es similar a la virtualización pero utiliza el sistema operativo host(rendimiento)
* La tecnología docker permite configurar una máquina con una serie de dependencias y ejecutar comandos con ella desde el host.
* Una máquina configurada se denomina contenedor/*container*.

* Estos contenedores pueden ejecutarse en cualquier sistema operativo de la misma arquitectura.
* En un host se pueden ejecutar varios containers y conectarse entre si.
* Su ejecución se lanza desde scripts configurables.
* La mayoría de las plataformas cloud permiten ejecutar contenedores.

Toda la configuración de un contenedor se almacena en un solo fichero llamado **Dockerfile**

**Imágenes y contenedores**

Una imagen es un sistema de ficheros y parámetros configurables que permiten modificar la ejecución de la imagen.
* Se compilan mediante el Dockerfile.
* No tienen estado y no cambian.
* Ejecutan un solo comando y termina su ejecución. El comando puede ser un servicio y quedarse en espera hasta que acaba su ejecución.

Un contenedor es una imágen en ejecución. El comando

``` docker run```

ejecuta un contenedor partiendo de una imágen.
