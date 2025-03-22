# Los sistemas inteligentes
---

En este documento, se han buscado 3 aplicaciones que utilizan inteligencia artificial que a mi juicio me parecen interesantes y útiles para nuestro día a día.
Además, también veremos que hacen que estas aplicaciones formen partes de un sistema inteligente nombrando las características que cumple y las que les faltaría por cumplir.

## Aplicaciones que usan IA

### Otter -> Procesamiento de lenguaje natural

Puedes entrar en la página web oficial si haces click [aquí](https://otter.ai/)

Otter es una aplicación que te ayuda a recoger apuntes, hacer un resumen y preguntarle sobre cualquier reunión que hayas tenido en Zoom, Google Meet o Microsoft Teams.

La razón por la que he escogido esta aplicación es porque me parece muy interesante las funciones que trae cómo:
- Chatbot para responder las preguntas sobre el meet.
- Un resumen sobre el meet que has tenido.
- Un historial con los diálogos transcritos para que tu puedas revisar.

#### Características que cumple

- *Posee una capacidad sensorial:* El sistema es capaz de reconocer las voces e incluso distinguirlas entre los distintos participantes del meeting.
- *Memoria y aprendizaje:* Almacena las transcripciones y utiliza algoritmos de aprendizaje atuomático para mejorar la precisión con el tiempo. 
- *Procesamiento de lenguaje natural:* Es capaz de interpretar y convertir la voz humana a texto, llegandose a adaptar a distintos acentos y contextos.

#### Características que no cumple

- *Conceptualización:* Debido a que no es capaz de conocer conceptos complejos simplemente se limita a reconocer las voces y hacer una transcripción.
- *Reglas de acentuación y autonomía:* La función de la aplicación es transcribir por lo que no toma decisiones autónomas.

---

### Windsurf editor -> Desarrollo de software y automatización con IA

Puedes entrar en la página web oficial si haces click [aquí](https://codeium.com/windsurf).

Estoy seguro de que muchos de ustedes ya conoceis el IDE *cursor* ([ver aquí](https://www.cursor.com/en)), si bien al principio pensaba que se trataba de lo mismo, un simple fork de Visual Studio con IA, este IDE va un paso más allá, es el primer **agentic IDE**

Hay 3 ideas principales que distinguen este IDE:
- Conocimiento
- Tools 
- Acciones Humanas

¿Qué quiere decir todo esto? Por ejemplo, si le pedimos que genere un docstring, el sistema necesita verificar todo nuestro codigo en cascada (revisa que una función de nuestro código afecte a otros archivos del mismo), identifica que hacen esos tests y contextualmente genera ese docstring.

Además este método en cascada tiene acceso a tools como: List directory, grep, Edit file y Add file lo que lo permite ser independiente. 
Pero no sólo se queda ahí, sino que puede ir más allá siendo capaz de generar comandos que pueden ser ejecutados por ejemplo:
- Ser capaz de reconocer que en mi requeriments.txt me hace falta alguna dependencia
- actualizar la versión de python que estas usando para el proyecto

**EL HUMANO VERIFICA QUE LA ACCIÓN SE TOME, POR LO QUE NO LO HACE DE FORMA INDEPENDIENTE**

Para terminar, quería comentar otra funcionalidad que utiliza este método en casacada. Al tener acceso a todo nuestro repositorio, el sistema nos permite lanzar el localhost en el propio IDE siendo capaz de "ver" los componentes que se muestran en pantallas y tu como usuario puedes seleccionar los componentes y pedir que te los modifique y lo hará teniendo en cuenta el contexto de la aplicación.

Cabe destacar que también tiene **MCP** con Github, puppeteer, PostgreSQL entre otros.

#### Características que cumple

- *Capacidad sensorial y contextual* Windsurf es capaz de "ver" el código en cascada y también integrar dependencias necesarias del  repositorio.å©
- *Memoria y conocimiento* El sistema almacena el código y su estructura lo que le permite "recordar" el contexto en futuras integraciones
- *Conceptualización* Es capaz de entender el contexto del código y sus relaciones.

#### Características que no cumple

- *Aprendizaje* No está "aprendiendo" como tal sino que analiza el repositorio y genera las respuestas en base a la información que tiene, además no toma decisiones por sí solo ya que necesita intervención humana para aprobar los cambios.
- *Sistematización* Aunque opera de forma integrada dentro del entorno del desarrollo de software, su aplicabilidad está restringida a ese dominio y no abarca la complejidad de un sistema inteligente “completo” que pueda interactuar y aprender de múltiples entornos de manera global.
---

### Goblin tools -> Asistente personal con IA y productividad

Puedes entrar en la página web oficial si haces click [aquí](https://goblin.tools/).

Esta aplicación la he elegido porque me parece una buena forma de incentivar a las personas a que muchas veces no hace falta pensar en algo muy complejo para desarrollar una aplicación por ejemplo para nuestro portfolio.

Goblin tools es una aplicación que tiene varias "aplicaiones" o "tools" que si las separamos una a una son simples pero al tener varias conseguimos que parezca complejo cuando realmente no lo es y cualquiera de nosotros lo podriamos realizar de forma "sencilla".

Las opciones que trae son: 
- *Magic ToDo:* Un gestor de tareas que con IA te permite generar las subtareas y generar el tiempo estimado que tardarias en realizarlas.
- *Formalizer:* Útil para poner varias ideas que tengas en mente o comunicar algo y que el el modelo de lenguaje te lo "arregle" o "embellezca" sin perder el mensaje principal
- *Judge:* Analiza una conversación y es capaz de decirte que sentimientos hay y además generar una respuesta apropieada al contexto
- *Professor* Un pequeño profesor virtual que te devuelve una explicación al problema con un ejemplo
- *Consultan:t* Analiza los pros y las contras de algún tema además de una pequeña conclusión
- *Estimator:* Estima el timpo que tardarías en realizar una tarea
- *Compiler:* Convierte tus ideas en tareas
- *Chef:* Es capaz de generarte una comida con los pasos a seguir en base a tu contexto (edad, peso, dieta, tiempo)

#### Características que cumple

- *Procesamiento:* Cada herramienta utiliza procesamiento de lenguaje natural y análisis de datos para interpretar solicitudes y la aplicación procesa y adapta la información según el contexto.
- *Memoria y conocimiento contextual:* Algunas funciones (como Magic ToDo o Compiler) capturan y utilizan información contextual del usuario para generar subtareas.
- *Reglas de actuación:* Cada tool aplica reglas predefinidas basadas en modelos de IA (por ejemplo, Judge para analizar sentimientos o Estimator para calcular tiempos), lo que permite la generación de respuestas o acciones específicas según el input recibido.

#### Características que cumple
- *Contextualización:* Aunque puede refinar y reorganizar información, no desarrolla conceptos abstractos ni realiza una interpretación profunda de los datos.
- *Aprendizaje autonómo:* La aplicación se basa en modelos preentrenados.
- *Sistematización:* Si bien la integración modular crea la ilusión de complejidad, no posee un sistema centralizado que abarque todas las capacidades de un sistema inteligente.

