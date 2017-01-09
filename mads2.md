# 3. Historias de usuario

## Características de las historias de usuario

Las historias de usuario son la forma ágil de definir las características(*features*) de la aplicación. Estas resaltan el punto de vista funcional y del usuario final.

Las historias de usuario nos aportan una manera de tener escrito solo lo suficiente para que no olvidemos las features y para que podamos planificar al mismo tiempo que promueven la conversación y comunicación directa.

#### Definición de una historia

Estas historias se escriben en forma de ficha y está compuesta por los siguientes tres aspectos:

* Descripción escrita de la historiam usada como un recordatorio para la planificación.
* Una conversación sobre la historia que sirve para desgranar los detalles de la misma.
* Pruebas que contemplan y documentan los detalles y que pueden utilizarse para determinar cuando la historia está completa.

**Formato**

El formato más popular a la hora de formular las historias de usuario es:

* Título de la historia
* Descripción: Como un *< tipo de usuario >*, quiero *< acción específica que realizo >* para que *< resultado que quiero que ocurra >*

Es importante que una historia de usuario conteste a tres preguntas:

* ¿Quien es el usuario que realiza la acción?
* ¿Qué quiere hacer el usuario?
* ¿Por qué lo quiere hacer?

**Condiciones de satisfacción**

Es importante conocer las condiciones de satisfacción de una historia, también denominadas criterios de aceptación o definición de hecho. Estas condiciones se pueden escribir en la parte trasera de la tarjeta. Estas condiciones son valiosas para evitar dejar partes de la historia por hacer. Normalmente los equipos de desarrollo se centran en la parte técnica pero pueden dejar cosas por hacer de la integración.

#### INVEST
Una buena historia tiene 6 atributos:

1. **Independent**. Dependencias entre las historias crean problemas de priorización y sincronización.
2. **Negotiable**. No son contratos si no recordatorios de conversaciones.
3. **Valuable**. Las historias deben ser valiosas para los que pagan.
4. **Estimable**. El tamaño de la historia debe poder ser estimable.
5. **Small**. Para poder estimarse correctamente es recomendable que la historia sea pequeña, hay que dividir las épicas.
6. **Testable**. Las historias deben ser probadas y los tests automatizados.


## Descomposición de historias
Una historia típica debe poder terminarse y testearse entre medio día y un par de semanas como máximo por uno o dos programadores. Una historia más grande que eso suele denominarse épica y se debe descomponer en historias más pequeñas. En el backlog del sprint la historia se descompone en ítems de trabajo. Es importante que el backlog del producto esté balanceado entre items grandes y pequeños.

Una historia épica es demasiado grande para ser estimada, puede ser difícil de estimar por ser **compuesta o compleja**

#### Estimación del tamaño de las tareas.
Es conveniente estimar el tamaño de las historias en **puntos de historia** en lugar de horas de desarrollo. Esto permite comparar el tamaño de las historias independientemente de la habilidad o experiencia del equipo de desarrollo y medir la velocidad del sprint del equipo, que serán los puntos de historia completados en el sprint.

La velocidad del equipo puede cambiar durante el proyecto(porque ganan experiencia) pero el tamaño de las historias debe mantenerse constante.

#### Roles de usuario
Es muy importante identificar los distintos roles que pueden acceder a la aplicación, para ello se suele buscar un conjunto inicial de roles, se organiza el conjunto, se consolidan los roles y por último se refinan.

**Personas**

Son representaciones imaginarias de una persona de cada uno de los roles. Ayuda a entender las motivaciones e interacciones del usuario con el producto.

## Mapas de historias de usuario

Es una técnica propuesta por Jeff Patton. Es una actividad de discusión con los clientes en el que se van descubriendo las historias y se agrupan y ordenan para contar una historia con distintos niveles de prioridad. El resultado final es similar a un storyboard de cine.

En el cine los storyboards se realizan a partir de otro medio más impreciso, el guión y se usan para:

* Desarrollar, discutir y probar la historia
* Medio de comunicación de distintos equipos
* Estimar el coste de la producción

## Bocetos y prototipos de baja fidelidad
Los prototipos de baja fidelidad son **Mockups** de pantallas e interfaces de usuario y representan una forma adicionarl de capturar codnicones de satisfacción de las historias de usuario. También se usan storyboards donde se explica los distintos pasos de la aplicación.

# 4. Scrum, Kanban y XP

## Scrum

En scrum un equipo pequeño hace cambios pequeños que se integran regularmente para formar un proyecto grande en lugar de que un equipo grande haga cambios grandes.

**Estructura**

Hay tres roles definidos en scrum:

* **Product Owner**: Se encarga de la comunicación del equipo con los stakeholders y es quien mantiene la visión general del proyecto, organiza las prioridades y se encarga de planificar las releases. Se encarga del **Product backlog**
* **Scrum Master**: Es el lider del equipo, aunque funciona más como un coach. Es parte del equipo pero se encarga también de asegurarse de eliminar impedimentos y preparar y moderar las reuniones y retrospectivas.
* **Equipo de desarrollo multifuncional**: Es un equipo auto-organizado que se encarga del desarrollo, la calidad del mismo y de mantener un ritmo adecuado. Son los encargados del **Sprint backlog**

**Daily scrum**

Es una reunión diaria en la que todo el equipo de desarrollo se reune de pie (para que la reunión sea breve). Durante esa reunión todos los desarrolladores expondrán tres puntos al resto del equipo.

1. Que hizo ayer
2. Que pretende hacer hoy
3. Los impedimentos que pueden surgirle para su objetivo de hoy

**Backlog management**

1. Se escriben las historias de usuario
2. Se estiman las historias. Hay distintas técnicas, una conocida es planning poker
3. Las tareas grandes o épicas se dividen y se vuelven a estimar
4. Se priorizan las tareas.

**Velocidad**
Es la cantidad de puntos de historia que puede completar el equipo en una cantidad de tiempo. Se mide usando los sprints anteriores y se actualiza con cada sprint. Se utiliza para determinar cuantas historias de usuario pueden hacerse en un sprint y para saber si una feature estará disponible en una fecha determinada.

**Scrum Checklist**
<center>
![Imagen Scrum1](https://github.com/Unaipg/apuntes/blob/master/assets/scrum1.png?raw=true)
</center>
<center>
![Imagen Scrum2](https://github.com/Unaipg/apuntes/blob/master/assets/scrum2.png?raw=true)
</center>
___
## Kanban
Tiene su origen en los sistemas de fabricación Lean y en los sistemas pull. Hubo una buena recepción por la comunidad y se integró con la metodología más utilizada en aquel momento: Scrum.

Kanban es un método para mejorar los procesos usados por los equipos ágiles. Los equipos empiezan analizando como construyen el software y lo utilizan para mejorar este proceso. El objetivo de Kanban es conseguir mejoras en el proceso de desarrollo persiguiendo **cambios evolutivos** obtenidos mediante experimentos. Se utilizan elementos de la metodología lean como el lead time o el flujo para medir el funcionamiento del equipo.

#### Motivaciones

* Conseguir un ritmo de trabajo sostenible
* Visualizar en todo momento la carga de trabajo del equipo de desarrollo(WIP)
* Visualizar y estandarizar el flujo de trabajo de historias de usuario
* Políticas explícitas como los límites de WIP, definición del DONE...

#### Kanban in a nutshell

* Visualizar el flujo de trabajo

    1. Dividir el trabajo en pequeñas partes, escribir cada elemento en  una tarjeta y ponerla en un tablero.
    2. Crear un tablero compartido por el equipo, dividido en columnas que identifican en que parte del flujo de trabajo se encuentra el elemento.
* Limitar el WIP. Se asigna un número límite de elementos que puede haber en cada estado del flujo de trabajo.
* Medir el tiempo medio de terminación de un elemento. También llamado **lead time** y optimizar el proceso para hacerlo tan pequeño y predecible como sea posible


#### Tablero Kanban
El tablero Kanban sirve para representar las distintas fases del proceso por las que deben pasar los items de trabajo.

Al indicar en que lugar del proceso está cada pieza de trabajo permite al equipo identificar colas, cuellos de botella... Se busca hacer visible lo invisible ya que cuando algo se hace visible es más fácil identificar un problema y conseguir una solución.

El tablero se actualiza en tiempo real por los miembros del equipo y los problemas se identifican en reuniones diarias. Al limitar el trabajo en proceso (WIP) la gente se centra en acabar cosas en lugar de comprometerse a mucho trabajo a la vez. Para mover una tarjeta se siguen reglas explícitas, lo que obliga a discutir y acordar políticas de progreso.
___

Kanban consta de 3 partes

### 1. Visualizar el flujo de trabajo
**Historias de usuario e ítems de trabajo**

Todas las historias deben ir acompañadas de criterios de aceptación. En caso de ser demasiado grandes habrá que dividirlas en tareas más pequeñas y a su vez dividiremos estas tareas en **items de trabajo** que se representan como tarjetas que se pegan en el tablero kanban. Los items de trabajo tampoco pueden ser demasiado pequeños.

Los post-it con items de trabajo contienen:

* Descripción del item de trabajo. Concisa, precisa y entendible por todo el equipo.
* Fecha de comienzo.
* Quien está trabajando en el item.
* Plazo de finalización.
* Código de identificación con el que podemos buscar el item en otro lugar
* Indicador de progreso
* Tamaño del item (S, M, L)

**Tablero kanban**

El objetivo principal es mostrar visualmente en qué está trabajando el equipo en un momento dado.

* Es un elemento para la reflexión, comunicación y discusión en las reuniones diarias.
* Permite ver distintas métricas relacionadas con el flujo como el WIP y el número de ítems terminados por semana.
* Fuerza a definir políticas estrictas de flujo de trabajo y terminación.

El uso de tableros online presenta algunas ventajas:

* Cálculo automático de diagramas y velocidades.
* Consultas

y algunas desventajas:

* No es visible en un espacio de trabajo
* Necesidad de scroll no permite verlo todo de un vistazo
* Falta de flexibilidad

La solución que se plantea es actualizar diariamente una copia del tablero físico en alguna herramienta online

### 2. Limitar el WIP

Limitar el WIP evita el exceso de multitarea y sobrecargas en las siguientes partes de la cadena de proceso. El límite del WIP debe establecerse por consenso ya que la tensión generada por establecer un WIP obliga a discutir y analizar el equipo y el proyecto.

El límite óptimo se obtiene midiendo, experimentando y mejorando. Se suele empezar con una regla sencilla como *2personas-1* y se estudia el flujo y optimiza el límite.

El límite del WIP fuerza a terminar las tareas antes de acometer con tareas nuevas .

**Clases de servicio**

En kanban se pueden definir condiciones adicionales que afectan al límite de WIP según la clase de servicio del ítem de trabajo.

Un ejemplo muy común es la clase "Expedite" que se le da a los items urgentes que tienen prioridad sobre el resto, para ellos se crea un canal adicional en el tablero con WIP 1 que se llama *canal rápido* o *fast lane*.

### 3. Medir y optimizar el flujo (tiempo medio de terminación)

**Tiempo medio de terminación. Lead time**

Es el tiempo medio que tarda un ítem de trabajo en ser procesado en cada paso y equivale al número de ítems terminados por unidad de tiempo. Se suele analizar su evolución a lo largo del proyecto usando diagramas de flujo acumulativos.

**Cadena de valor**

La definición de la cadena de valor por la que pasan los items de trabajo es importante tanto para analizar el flujo como para detectar cuellos de botella.

### Resumen de Kanban

1. Visualizar el flujo de trabajo
2. Limitar el Work In Progress
3. Media y optimizar el flujo
4. Hacer explícitas las políticas
    * Definition of done
    * Classes of service
    * Service level agreement
5. Retroalimentación y mejora continua
    * Ritmo y cadencia
    * Daily standups
    * Retrospectivas

**Receta para el cambio a Kanban**

1. Centrarse en la calidad
2. Reducir el Work In Progress
3. Entregar con más frecuencia
4. Equilibrar la demanda con el rendimiento
5. Priorizar
6. Atacar las fuentes de variabilidad para mejorar la predictibilidad
---
## Kanban vs. Scrum

#### Similitudes

* Lean y ágiles
* Planificación pull
* Limitan el WIP
* Usan transparencia para empujar la mejora del proceso
* Se centran en entregar software que puede ser puesto en producción de forma temprana y frecuente
* Equipos auto-organizados
* Requieren dividir el trabajo en trozos
* El plan de puesta en producción se optimiza continuamente basándose en datos empíricos

#### Diferencias

|**Scrum**|**Kanban**|
|:---:|:---:|
|Iteraciones con límite de tiempo|Límite de tiempo opcional|
|El equipo se compromete a una cantidad de trabajo por iteración|Compromiso opcional|
|Se usa velocidad como métrica por defecto|Se usa el lead time como métrica por defecto|
|Equipos multidisciplinares|Multidisciplinaridad opcional|
|Ítems de máximo un sprint|Tamaño libre|
|Diagrama de burnout|Ningún diagrama en especial|
|WIP limitado por sprint|WIP limitado de forma directa|
|Se prescribe la estimación|Estimacion opcional|
|No se añaden items dentro de la iteración|Se pueden añadir items siempre que haya capacidad|
|Backlog del sprint pertenece a un equipo|El tablero Kanban puede ser compartido por varios equipos|
|3 roles (PO,SM,Team)|No hay roles|
|El tablero se borra al final de cada sprint|El tablero es persistente|
|Backlog de producto priorizado|Priorización opcional|

---
## Extreme programming

#### Historia de XP

**Historia**

Su origen es a finales de los 80 en la comunidad Smalltalk. Durante los 90 *Kent Beck* y *Ward Cunningham* refinaron sus prácticas extendiendo la idea de que el desarrollo de software es un proceso adaptativo y orientado a las personas. El primer proyecto considerado XP fue el C3 de Chrysler(1993-1997).

Un hito importante fue la publicación de la segunda edición del "libro blanco" de Kent Beck.

**Evolución**

Han sido publicadas dos versiones del libro *Extreme programming explained* en 2000 y 2005. La primera versión trata 12 prácticas principales mientras que la segunda trata 13 prácticas principales y 11 secundarias, tomando algunas de otras metodologías. En este cambio se puede ver el proceso de evolución y maduración de la metodología.

#### Algunos conceptos clave

**Promesas de XP**

* Reducir el riesgo del proyecto
* Mejorar la respuesta ante cambios en el negocio
* Mejorar la productividad a lo largo de toda la vida del software
* Hacer más divertido el trabajo del equipo

**Las pruebas son un elemento fundamental de XP**

El punto más destacado de XP es el énfasis en las pruebas y la práctica del TDD. En XP las pruebas son el elemento fundamental del desarrollo y todos los desarrolladores deben escribirlas mientras escriben el código.

Estas pruebas se integran en un proceso de integración y construcción continua, lo que lleva a una plataforma muy estable para el desarrollo futuro.

El énfasis en las pruebas como ha sobrepasado la metodología y se ha introducido en múltiples metodologías y equipos de desarrollo, aunque no usen el resto de XP.

**El triangulo de hierro**

Hay tres factores relacionados: tiempo, coste y alcance, que tienen efecto en la calidad. La calidad se encuentra en el código, en la funcionalidad y en los aspectos de UX.

Una solución fácil para aumentar la velocidad es reducir la calidad pero es una mala decisión ya que aumenta la deuda técnica acumulada y el cliente espera una calidad mínima y no se sentirá satisfecho si no se cumple.

En XP se fija el coste, el tiempo y la calidad y se negocia el alcance.

#### Valores y principios

**5 Valores**

1. Comunicación
2. Simplicidad
3. Retroalimentación
4. Valentía
5. Respeto

**11 principios**

* **Humanidad**: El software lo desarrollan personas
* **Economía**: Asegurar el valor económico de lo que haces
* **Beneficio mutuo**: Buscamos prácticas que beneficien a todos
* **Auto-similitud**: Aplica patrones conocidos a múltiples problemas
* **Mejora**: Excelencia en el desarrollo a través de la mejora. Se busca perfeccionar, no la perfección
* **Diversidad**: Dos ideas sobre un diseño presentan una oportunidad, no un conflicto
* **Reflexión**: Los buenos equipos piensan como y por qué hacen el trabajo, no esconden errores
* **Flujo**: Entrega continua de valor
* **Oportunidad**: Los problemas son oportunidades de cambio
* **Redundancia**: Los elementos complejos debería estar duplicados, las partes complejas se deben mirar dos veces
* **Fallo**: Un fallo no es un desperdicio si sirve para aprender algo
* **Calidad**: No se va más rápido rebajando la calidad
* **Pequeños pasos**: ¿Qué es lo menos que puedes hacer que sea reconocible y vaya en la dirección correcta?
* **Responsabilidad aceptada**: El que acepta algo se hace cargo de ello

#### Las 13 prácticas

1. Sit together
    * Usar un espacio abierto donde todo el equipo pueda trabajar para que florezca la comunicación. Cuantas más reuniones cara-cara más productivo se vuelve el proyecto.
2. Whole team
    * La sensación de equipo en el que todos apoyan el trabajo, crecimiento y aprendizaje de todos. Estos equipos son dinámicos, cuando un trabajo disminuye el encargado puede hacer otra cosa.
3. Informative workspace
    * Poner en sitios visibles las tareas y su estado(kanban) y las gráficas de evolución del proyecto.
4. Energized work
    * Trabajar a pleno rendimiento, pero solo las horas que se pueda de manera sostenida. Es posible mejorar la productividad gestionando mejor el tiempo.
5. Pair programming
    * Todo el código de producción debe ser escrito con dos personas delante del ordenador que mantienen un diálogo y analizan, prueban y diseñan simultaneamente.
    * Las ventajas es que las ideas quedan más claras, se mantienen concentrados entre ellos y se cumplen mejor los estándares del equipo.
    * Se aconseja rotar las parejas, no invadir el espacio personal del otro y no juntar a dos programadores novatos.
6. Stories
    * Escribir las historias en una tarjeta pequeña indicando nombre, descripción y tiempo estimado y colocar las tarjetas en un sitio visible, como la pared.
7. Weekly cycle
    *  Se hace una reunión al principio de cada semana donde se revisa el progreso, se negocia con el cliente y se dividen las historias en tareas.
    * Se escriben todas las pruebas al comenzar la semana y tienen que pasarse cuando acabe la semana.
    * Un ciclo semanal es lo suficientemente corto como para hacer experimentos y que no pase nada.
8. Quarterly cycle
    * Es conveniente hacer reuniones con un ciclo superior al semanal para ver la evolución del proyecto en conjunto por lo que cada tres meses se buscan cuellos de boterra, de planifican los temas para el trimestre y se centra una visión general de cómo el proyecto encaja en la organización y el valor que añade.
9. Slack
    * Trabajar con un colchon que suavice la tensión. Es importante establecer una atmósfera de confianza en la que los desarrolladores y los que hacen las peticiones se comuniquen de manera clara y honesta.
    * Los trabajos con plazos no realistas introducen errores no manejables, minan la moral y construyen relaciones antagonistas. Cumplir con compromisos tine efectos contrarios
10. Ten-Minute Build
    * 10 minutos para construir automáticamente todo el sistema y ejecutar todos los tests. Debe estar completamente automatizado y se deben ejecutar todos los tests, no solo los de la nueva parte del sistema.
    * En *continous delivery* se va un paso más allá y se automatiza el despliegue de nuevas funcionalidades.
11. Continous integration
    * No dejar más de dos horas de programación sin integrar los cambios. Se busca asegurar la parte de programación que es impredecible y puede tener mayor coste que el propio desarrollo. El sistema resultante debe estar listo para ser desplegado.
    * Integración sincrona: Cada pareja después de un par de horas de programación sube sus cambios y se lleva a cabo el proceso de integración
    * Integración asíncrona: Todas las noches si hace una build
12. Test-first programming
    * Antes de escribir cualquier código se escriben las pruebas.
    * Las ventajas de escribir pruebas son:
        * Cohesión y acoplamiento: Si el test es difícil de escribir es que hay problemas de diseño
        * Confianza: Código claro y limpio genera confianza entre compañeros.
        * Ritmo: Es fácil llevar un ritmo cuando los pasos son siempre hacer un test, hacer código que lo pase.
13. Incremental design
    * Diseño gradual con pasos pequeños y seguros. El diseño debe hacerse conforme vamos adquiriendo experiencia.
    * Los equipos XP trabajan duro para crear condiciones en las que el coste de modificar software sea bajo.

**Prácticas secundarias**

|Team|Business|
|---|---|
|Real customer involvement|Root-cause analysis|
|Team continuity|Negotiated scope contract|
|Shrinking teams|Pay-per-use|
|||
|||
|**Programming**|**Deliverying**|
|Shared code|Incremental deployment|
|Code and test|Daily deployment|
|Single code base|

## Escalando Ágil

Scrum habla de un equipo de entre 3 y 9 personas, pero a veces es inevitable escalar cuando se trabaja en más de un proyecto o es un proyecto grande que necesita más de 9 personas para su desarrollo.

**Un equipo desarrollando varios productos**

Hay un solo PO que prioriza el backlog y un único backlog en el que se colocan las historias de todos los productos. En un tablero Kanban se pueden hacer distintos canales para cada producto.

Esto presenta como problema la pérdida de concentración por parte del PO y del equipo ya que la cantidad de información que puede retener un equipo es limitada y porque el cambiar de contexto genera dificultades.

#### LeSS Large-Scale Scrum

Propuesto por *Craig Larman* y *Bas Vodde*. Hay otras opciones como SAFe y Nexus en las que no vamos a profundizar.

**Prácticas e ideas comunes con Scrum**

LeSS es una versión ampliada de Scrum por lo que mantiene muchas de sus prácticas e ideas.

* Hay un solo backlog de producto
* Una única definición de terminado
* Un único incremento de producto potencialmente entregable
* Un product owner
* Los equipos (sean la cantidad que sean) son multidisciplinares

En LeSS todos los equipos están en un Sprint común con el objetivo de terminar un único producto entregable en cada sprint.

**Producto**

Scrum se basa en desarrollar un producto, no un proyecto. Ese producto será usado y aportará valor a los usuarios y su definición determinará el alcance. Una definición amplia del producto permite:

* Mejorar la priorización de las características centrándonos en el usuario
* Resover las dependencias usando feature teams (equipos orientados a características)
* Evitar funcionalidades duplicadas

La definición del producto debe ser lo más centrada en el usuario posible.

**Product Owner**

El product Owner se encarga del backlog del producto. En LeSS solo hay un product owner y un product backlog para un producto completo. Este Product owner no debe trabajar solo en el refinamiento del backlog del producto, debe hacerse por los distintos equipos que trabajan directamente con los otros stakeholders y usuarios.

Cualquier priorización pasa por el product owner.

**Equipos**

Scrum requiere equipos multifuncionales y autogestionados. En LeSS cada miembro de un equipo se dedica 100% a su equipo y los equipos serán grupos de larga duración para asegurar estabilidad. A pesar de la separación entre equipos no hay problema en que se compartan espacios.

Lo mejor es que los equipos construyan features en lugar de componentes.

**Sprint**

Conceptualmente solo hay un sprint a nivel de producto que lleva a un único incremento del producto. En la práctica se debe hacer:

* Un Sprint planning para todos los equipos al mismo tiempo
* Una revisión de sprint y retrospectiva para todos los equipos a la vez
* Refinamiento del backlog del producto a nivel de equipos, da igual cuando

En LeSS hay dos Sprint plannings, al primero asisten representantes de todos los equipos y es donde se seleccionan los items, se aclaran dudas y se define el objetivo del sprint. El segundo Sprint planning se hace de manera local en cada equipo, genera un sprint backlog y se centra en la creación de un plan de trabajo para que todos los items estén terminados al final del sprint.

**Daily Scrum**

El scrum diario se realiza por equipos y es igual que el de scrum.

**Coordinación e integración**

En LeSS la coordinación e integración busca una **coordinación descentralizada** para proporcionar límites y una estructura para evitar caos. Hay diferentes formas de coordinar e integrar los equipos.

* Hablar: No hay protocolos, vas y hablas con gente de otros equipos
* Comunicarse con el código: Se usa integración continua y al integrar el código se debe leer el código añadido por los demás
* Enviar observadores a los Daily scrums
* Comunidades de componentes: Listas de correos o grupos de mensajería para compartir información

**Definición de terminado**

En Scrum la definición de terminado es una lista de criterios que debe cumplir el software para cada ítem del backlog. No se debe confundir definición de terminado con criterios de aceptación, la misma definición de terminado se aplica a todos los items del backlog del producto.

En LeSS la definición de terminado debe ser común para todos los equipos.

**Sprint review**

En Scrum es un punto de inspección-adaptación al final de cada Sprint en el cual los clientes y stakeholders examinan los resultados del sprint y discuten cambios y nuevas ideas. Es donde se dirige la dirección del producto.

En LeSS todos los equipos participan en el Sprint review. Se puede usar un formato parecido a las ferias científicas donde cada equipo expone sus avances en el producto.

**Retrospectiva y retrospectiva general**

Cada equipo hace una retrospectiva y después se hace una general con el PO, los scrum masters y los representantes de cada equipo. Se deben explorar los siguientes puntos:

* ¿Cómo de bien están trabajando los equipos juntos?
* ¿Están funcionando las comunidades en la práctica?
* ¿Hay que compartir algo que ha hecho el equipo?
* ¿Los equipos están aprendiendo juntos?
* ¿Los equipos están cerca de los clientes?
* ¿Hay asuntos sistémicos organizacionales que causan problemas en como operan los equipos?
* ¿Lo está haciendo bien el PO?
* ¿Está manteniendo el PO sus cinco relaciones?

**Refinamiento del backlog del producto**

Es un proceso que se realiza a mitad del sprint para refinar los ítems del backlog y dejarlos listos para Sprints futuros. No debe ocupar más de un 10% del tiempo de sprint. Las actividades clave son:

* Dividir ítems grandes
* Detallar los ítems hasta que estén listos
* Estimar

**Otros elementos de LeSS**

* Excelencia técnica
* Principios
* Estructura
* Gestión
* Adopción
