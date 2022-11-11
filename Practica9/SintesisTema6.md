# <FONT COLOR=" #1829f5 "><h2> **Patrones de diseño**</h2>

## <FONT COLOR=" #1624c9 "><h3>¿Qué es?</h3> 

### Es una plantilla que puede aplicarse en muchas situaciones diferentes.<br> Son descripciones de clases y objetos relacionados.


### Resuelve problemas concretos, haciendo que sean flexibles, elegantes y reutilizables,<br> se pueden aplicar soluciones a problemas sin la necesidad de redescubrirlos.

### Diseña, nomina, abstrae e identifica aspectos clave usados en una estructura de diseño general,<br> facilitando trabajar en proyectos, ya que conserva un orden y se evitan posibles errores o fallas dentro del entorno.

## <FONT COLOR=" #1624c9 "><h3>Elementos de un patrón de diseño</h3>

### <u>Nombre</u>: Este ayuda a describir el problema y facilita a transmitir el patrón.

### <u>Problema</u>: Describe las circunstancias para poder aplicar el patrón, el contexto para usarlo.

### <u>Solución</u>: Describe todos los elementos que participan en el patrón de diseño, los relaciona, <br>especifica las responsabilidades y colaboraciones.

### <u>Consecuencias</u>: Describe los resultados, ventajas y desventajas al aplicar el patrón de diseño.

## <FONT COLOR=" #1624c9 "><h3>Tipos de patrones de diseño</h3>

### Creacionales

#### Estos abstraen el proceso de creación de objetos, ayudan a diseñar <br> clases en forma independiente a como los objetos son creados, compuestos  <br> y representados. Este tipo de patrones resuelven problemas recurrentes.

#### Se subdividen en

##### <u>Factory</u>: Esta tiene una interfaz abstracta para crear un objeto, y delega a sus <br> subclases la responsabilidad de decidir a partir de cuál clase concreta <br> se instanciaría dicho objeto.

##### <u>Abstract Factory</u>: Busca definir una interfaz abstracta para crear una familia de objetos <br> relacionados que son dependientes de una variedad de soluciones concretas.

##### <u>Builder</u>:Este patrón busca encapsular los detalles de la construcción de objetos<br> tales como la instanciación de partes de un objeto compuesto  en forma <br> lógicamente organizada.

##### <u>Prototype</u>: Este patrón permite crear otros objetos simplemente haciendo una copia <br>  del objeto prototipo y haciéndo las modificaciones respectivas.

##### <u>Singleton</u>:Es útil cuando se requiere una sola instancia de una clase durante el <br> ciclo de vida de la aplicación. Su principal objetivo consiste en garantizar <br> que una clase sólo tenga una instancia.

### Estructurales

#### Estos patrones tienen que ver con la forma en que las clases y los objetos <br> son agrupados para formar grandes estructuras.

#### Se subdividen en

##### <u>Decorator</u>: Este patrón es utilizado para extender la funcionalidad de un objeto <br> de manera dinámica, sin tener que cambiar el código fuente de la clase <br> original o hacer uso de la herencia de implementación.

##### <u>Adapter</u>:El patrón Adaptador se utiliza para transformar una interfaz de una clase <br> en otra, de tal modo que una clase que no pudiera utilizar la primera.

##### <u>Facade</u>: Este patrón permite interactuar en forma centralizada con un subsistema de clases.

##### <u>Proxy</u>: Es un patrón de diseño estructural que te permite proporcionar un <br> sustituto o marcador de posición para otro objeto. Un proxy controla el acceso al objeto original, <br>permitiéndote hacer algo antes o después de que la solicitud llegue al objeto original.

##### <u>Bridge</u>: El patrón Bridge permite desacoplar la abstracción de jerarquias de su <br> implementación, de manera que ambas puedan ser modificadas <br> independientemente.

##### <u>Counting Proxy</u>: Es útil para diseñar un conjunto de operaciones tales como registro y <br> conteo que son requeridas para su ejecución antes y/o después de que un objeto <br>cliente invoca un método o un servicio de un objeto proveedor.

##### <u>Aggregate Enforcer</u>: Recomienda que cuando un objeto agregado es construido, <br>debe ser creado completamente.

##### <u>Object Cache</u>: Sugiere mantener una copia de un objeto en la memoria, con el objetivo de <br> proveer un tiempo de respuesta más rápido a las solicitudes de los cliente.

##### <u>Composite</u>: Permite a un objeto cliente tratar de manera idéntica a componentes <br> individuales y compuestos.

##### <u>Flyweight</u>: Sugiere separar todos los datos comunes a varios objetos, en un objeto <br> separado denominado objeto Flyweight.

##### <u>De comportamiento</u>: Los patrones de comportamiento están relacionados con los algoritmos <br> y con la asignación de responsabilidades entre los objetos. Estos no describen solo patrones de clases<br> y de objetos, sino que describen los   patrones de cómo estos se comunican.
