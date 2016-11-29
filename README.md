                          UTILIZAR ALGUNAS TECNOLOGÍAS DISRUPTIVAS EN TI PARA EL DESARROLLO DE UNA SOLUCIÓN INFORMÁTICA.


                                                        TECNOLOGÍAS DISRUPTIVAS EN TI
                                                                   UNIDAD II






                                                                GRUPO: 214001_4




                                                            PRESENTADO AL DOCENTE:
                                                           Roberto Mauricio Cárdenas





                                                UNIVERSIDAD NACIONAL ABIERTA Y A DISTANCIA – UNAD
                                              MAESTRIA EN GESTIÓN DE LA TECNOLOGIA DE LA INFORMACÓN
                                                              NOVIEMBRE DE  2016




                                                             TABLA DE CONTENIDO

        1.	INVESTIGAR
        a.	¿Qué es Git?	
        b. ¿Qué es Github?	
        2.	EXPLICAR LOS SIGUIENTES COMANDOS EN SUS PROPIAS PALABRAS.	
        Computación en la nube	
        3.	INVESTIGAR.	
        a.	¿Qué significan las siglas IaaS, PaaS, y SaaS? Explique las diferencias con ejemplos prácticos.	
        b.	¿Qué es Heroku?	
        4.	REGISTRARSE EN LA PLATAFORMA DE HEROKU Y DESCARGAR HEROKU TOOLBET PARA DESARROLLAR APLICACIONES.	
        Herramientas de Software	
        5.	¿QUÉ ES NODE.JS?,  ¿CUÁL ES SU IMPORTANCIA HOY?, ¿POR QUÉ MUCHAS EMPRESAS EN MUNDO USAN NODE.JS?	
        6.	¿QUÉ ES EXPRESSJS? DE OTROS EJEMPLOS	
        7.	¿QUÉ SON LOS WEBSOCKETS?, ¿QUE ES SOCKET.IO?	
        Social media	
        8.	INVESTIGAR	
        a.	¿Qué es Twitter Streaming API? Dar un ejemplo de su uso en productos comerciales o por parte de alguna empresa	
        b. ¿Cómo podría una empresa colombiana usar el Twitter Streaming API?	
        9.	DISEÑE UN PROYECTO QUE USE EL TWITTER API, Y QUE AÑADA VALOR AL NEGOCIO DE UNA EMPRESA EN EL CONTEXTO COLOMBIANO. ESTA               PREGUNTA DEBERÁ CONTENER UNA MOTIVACIÓN DESDE EL PUNTO DE VISTA DE NEGOCIO Y UN DISEÑO HOLÍSTICO DE LA SOLUCIÓN DE TI.	
        10.	REGISTRARSE PARA CREAR UNA APLICACIÓN QUE USE EL TWITTER STREAMING API. GENERAR LAS DIFERENTES CLAVES DE AUTH2 PARA PODER           USAR EL API.	
        11.	CLONE EL PROYECTO HTTPS://GITHUB.COM/UNADTDTI/LABORATORIO-PRACTICO.GIT, Y SIGA LAS INSTRUCCIONES EN EL ARCHIVO README.               DESPUÉS DE TERMINAR LAS MODIFICACIONES, DESPLIEGUE LA APLICACIÓN WEB EN HEROKU, E INCLUYA LA URL DE LA APLICACIÓN                       CORRIENDO
        
  GIT
Es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente. Wikipedia
Git es un sistema distribuido de control de código fuente o SCM (en inglés Source Code Management).  Es decir Git nos proporciona las herramientas para desarrollar un trabajo en equipo de manera inteligente y rápida y por trabajo nos referimos a algún software o página que implique código el cual necesitemos hacerlo con un grupo de personas.

Algunas de las características más importantes de Git son: 

	Rapidez en la gestión de ramas, debido a que Git nos dice que un cambio será fusionado mucho más frecuentemente de lo que se escribe originalmente.

	Gestión distribuida; Los cambios se importan como ramas adicionales y pueden ser fusionados de la misma manera como se hace en la rama local.

	Gestión eficiente de proyectos grandes.

	Realmacenamiento periódico en paquetes.


GITHUB

GitHub es una plataforma de desarrollo colaborativo de software para alojar proyectos utilizando el sistema de control de versiones Git.
GitHub aloja tu repositorio de código y te brinda herramientas muy útiles para el trabajo en equipo, dentro de un proyecto.
Además de eso, puedes contribuir a mejorar el software de los demás. Para poder alcanzar esta meta, GitHub provee de funcionalidades para hacer un fork y solicitar pulls.
En la actualidad, GitHub es mucho más que un servicio de alojamiento de código. 
El código se almacena de forma pública, aunque también se puede hacer de forma privada, creando una cuenta de pago. 






EXPLICAR LOS SIGUIENTES COMANDOS EN SUS PROPIAS PALABRAS


1.	GIT CLONE: Obtener una copia de un repositorio de un archivo.

2.	GIT PULL: hace que tu rama local está actualizada con la versión remota o cambio más reciente.

3.	GIT PUSH: envían datos de los repositorios remotos, cuando necesitan compartir cosas.

4.	GIT CHECKOUT: Crea o restaura ramas  de los archivos del árbol de trabajo.

5.	GIT ADD: Comando usado para agregar cambios a los archivos nuevos o modificados con el índice. 

6.	GIT CHECKOUT -B "NOMBRE": definimos una nueva rama llamada nombre.

7.	GIT COMMIT -AM"PRIMER COMMIT": Confirmar los cambios en el repositorio.

8.	GIT PULL REBASE: Comando usado para reorganizar dos ramas, seleccionando los cambios de una rama y aplicándolos sobre otra.

9.	GIT STASH: Guarda provisionalmente.

10.	GIT STASH POP: Aplicar  nuevos cambios almacenados temporalmente en un stash.

11.	GIT RESET: Deshacer cambios.
 
12.	GIT CHERRY-PICK: mueve un “commit” de una rama a otra del proyecto.

3.	INVESTIGAR.
	
a.	¿Qué significan las siglas IaaS, PaaS, y SaaS? Explique las diferencias con ejemplos prácticos.	

 

INFRAESTRUCTURE-AS-A-SERVICE (IAAS)

El concepto de Infraestructura como Servicio (IaaS, Infrastructure as a Service) es uno de los tres modelos fundamentales en el campo del cloud computing, junto con el de Plataforma como Servicio (PaaS, Platform as a Service) y el de Software como Servicio (SaaS, Software as a Service). Al igual que todos los servicios cloud, IaaS proporciona acceso a recursos informáticos situados en un entorno virtualizado, la"nube" (cloud), a través de una conexión pública, que suele ser internet. En el caso de IaaS, los recursos informáticos ofrecidos consisten, en particular, en hardware virtualizado, o, en otras palabras, infraestructura de procesamiento. La definición de IaaS abarca aspectos como el espacio en servidores virtuales, conexiones de red, ancho de banda, direcciones IP y balanceadores de carga.


PLATAFORMA COMO SERVICIO (PAAS)

Plataforma como servicio permite a los usuarios crear aplicaciones de software utilizando herramientas suministradas por el proveedor. servicios PaaS pueden consistir en rasgos pre configurados que los clientes pueden suscribirse; que pueden optar por incluir las características que satisfacen sus necesidades y descartar aquellas que no lo hacen. En consecuencia, los paquetes pueden variar de ofrecer marcos simples de apuntar y hacer clic donde no se requiere experiencia de alojamiento lado del cliente para el suministro de las opciones de infraestructura para el desarrollo avanzado.

SAAS O SOFTWARE COMO SERVICIO 

Describe cualquier servicio en la nube, donde los consumidores pueden acceder a las aplicaciones de software en internet. Las aplicaciones se alojan en "la nube" y se pueden utilizar para una amplia gama de tareas para los individuos y las organizaciones. Google, Twitter, Facebook y Flickr son todos ejemplos de SaaS, los usuarios pueden acceder a los servicios a través de cualquier dispositivo habilitado para Internet. Los usuarios de empresas son capaces de utilizar las aplicaciones para una variedad de necesidades, incluyendo contabilidad y facturación, seguimiento de las ventas, la planificación, la supervisión del rendimiento y de las comunicaciones (incluyendo webmail y mensajería instantánea).






CUADRO DE DIFERENCIAS LAS  IAAS, PAAS, Y SAAS


IAAS	PAAS	SAAS
	Escalabilidad
	Sin necesidad de invertir en hardware.
	Modelo de tarificación similar al de los suministros públicos como la luz o el gas.
	Independencia de la localización.
	Seguridad física en los centros de datos.
	No hay puntos únicos de fallo.		Ellos no tienen que invertir en infraestructura física.
	Hace posible el desarrollo de 'no expertos'.
	Flexibilidad.
	Adaptabilidad.
	Los equipos en distintos lugares pueden trabajar juntos.
	Seguridad.		No hay costes adicionales de hardware.
	Sin costes iniciales de instalación.
	Pagar por lo que usa.
	El uso es escalable.
	Las actualizaciones se realizan automáticamente.
	Compatibilidad con los dispositivos de la Cruz.
	Accesible desde cualquier lugar.
	Las aplicaciones pueden ser personalizados y whitelabelled.





HEROKU

Heroku es una plataforma como servicio de computación en la Nube que soporta distintos lenguajes de programación.
Heroku es propiedad de Salesforce.com.1 Heroku, es una de las primeras plataformas de computación en la nube, que fue desarrollada desde junio de 2007, con el objetivo de soportar solamente el lenguaje de programación Ruby, pero posteriormente se ha extendido el soporte a Java, Node.js, Scala, Clojure y Python y (no documentado) PHP. La base del sistema operativo es Debian o, en la nueva plataforma, el sistema basado en Debian Ubuntu.






REGISTRARSE EN LA PLATAFORMA DE HEROKU Y DESCARGAR HEROKU TOOLBET PARA DESARROLLAR APLICACIONES


 








HERRAMIENTAS DE SOFTWARE

¿Qué es Node.js?,  ¿Cuál es su importancia hoy?, ¿Por qué muchas empresas en mundo usan Node.js?

Node.js
Node es un intérprete Javascript del lado del servidor que cambia la noción de cómo debería trabajar un servidor. Su meta es permitir a un programador construir aplicaciones altamente escalables y escribir código que maneje decenas de miles de conexiones simultáneas en una sólo una máquina física. 

Cuál es su importancia hoy

Node.JS es una plataforma reciente y que ha sufrido muchos cambios a lo largo de su creación. De hecho, en el momento de escribir este artículo aún no se ha presentado la release 1.0, por lo que muchos desarrolladores la han tomado en cuenta con cierta distancia. Actualmente se encuentra a disposición la versión 0.8.15.

Inicialmente, es cierto que ha sufrido bastantes modificaciones, un tanto radicales, en su API, lo que ha obligado a diversos profesionales que apostaron por Node desde un principio a reciclar sus conocimientos rápidamente y rehacer su código en alguna ocasión. Sin embargo, desde hace tiempo han adquirido el compromiso desde NodeJS a no cambiar el API y continuar con la misma arquitectura, realizando solo cambios a nivel interno.

Esto nos hace entender que es un buen momento para aprender NodeJS sin temor a que lo que aprendamos acabe rápidamente en desuso.


POR QUÉ MUCHAS EMPRESAS EN MUNDO USAN NODE.JS

Existen varios ejemplos de éxito de empresas que usan NodeJS. El que lleva la delantera puede ser LinkedIn, que es una red social para  búsqueda de empleos y mantener contacto entre profesionales. Esto a beneficiado enormemente a LinkedIn pues de 30 servidores lo ha reducido a 3, sin duda un ahorro importante.


Usado por su rendimiento y escalabilidad. NodeJS es veloz esto es de gran importancia para las aplicaciones que tienen gran afluencia de usuarios.

Permite la manipulaciones de datos de forma sencilla sin un gran cantidad de cálculos.

A diferencia de PHP, sin querer hacerle mala fama a este lenguaje de programación,  maneja miles de conexiones simultáneas en una misma máquina.

Es un buen momento de aprender NodeJS pues el API de esta no va a cambiar, continuará con la misma arquitectura. Así que no hay temor de que lo que aprendamos quede, después de un tiempo, desfasado.

Actualmente existen varios proyectos que tienen interés en el uso de NodeJS lo que demuestra que esta plataforma de desarrollo está alcanzado un buen grado de madurez. Algunos ejemplos de proyectos, basados en Node e  interesados en NodeJS son: Meteor JS, Grunt, Yeomar, etc.


EXPRESSJS

Express es sin duda el framework más conocido de node.js, es una extensión del poderoso connect y está inspirado en sinatra, además es robusto, rápido, flexible, simple…

Sin duda el éxito de express radica en lo sencillo que es usarlo, y además abarca un sin número de aspectos que muchos desconocen pero son necesarios

Express.js está basado en Connect, que es un framework extensible de manejo de servidores HTTP, el cual provee plugins de alto rendimiento conocidos como middleware.

Middleware es un software que asiste a una aplicación para interactuar o comunicarse con otras aplicaciones, software, redes, hardware y/o sistemas operativos

EJEMPLOS

Koa.js: es un framework de aplicaciones web mínimos y flexibles Node.js que proporciona un robusto conjunto de características para la web y aplicaciones móviles. Es un framework de código abierto desarrollado y mantenido por los creaters de Express.js, el más popular marco nodo web.

Total.js: Es un framework de servidor para Node.js, escrito en JavaScript puro, similar a laravel de PHP o Python Django o ASP.NET MVC.
Plataforma total es una colección de bibliotecas y las mejores prácticas para la creación de aplicaciones web ricas. La plataforma contiene herramientas para el lado del servidor y la codificación del lado del cliente.


SailJs: Es un excelente framework para hacer aplicaciones en tiempo real, con un sistema de acceso a base de datos basado en ORM y con la filosofía de Ruby on Rails.

SocketStream: Pensado para crear aplicaciones que manejen datos en tiempo real, muy fácil de configurar y utilizar además puede ser usado con otros frameworks como Express.

ActionHero: Creado para desarrollar API Servers, reusable y con la capacidad de ser integrado con sistemas clouster, si lo que buscas es crear un API profesional esta es tu opción.


LOS WEBSOCKETS

WebSocket es una tecnología que proporciona un canal de comunicación bidireccional y full-duplex sobre un único socket TCP. Está diseñada para ser implementada en navegadores y servidores web, pero puede utilizarse por cualquier aplicación cliente/servidor. La API de WebSocket está siendo normalizada por el W3C, mientras que el protocolo WebSocket ya fue normalizado por la IETF como el RFC 6455. Debido a que las conexiones TCP comunes sobre puertos diferentes al 80 son habitualmente bloqueadas por los administradores de redes, el uso de esta tecnología proporcionaría una solución a este tipo de limitaciones proveyendo una funcionalidad similar a la apertura de varias conexiones en distintos puertos, pero multiplexando diferentes servicios WebSocket sobre un único puerto TCP (a costa de una pequeña sobrecarga del protocolo)..
En el lado del cliente, WebSocket está ya implementado en Mozilla Firefox 8, Google Chrome 4 y Safari 5, así como la versión móvil de Safari en el iOS 4.2.1 y en Internet Explorer 10.2.  

SOCKET.IO

Socket.io es una librería que nos permite manejar eventos en tiempo real mediante una conexión TCP y todo ello en JavaScript. Es realmente potente y podemos hacer todo tipo de aplicaciones en tiempo real. Hay muchos ejemplos de chat (que puede ser lo más llamativo) por ahí. Pero yo quiero hacer algo mucho más sencillo, para que comprender su funcionamiento lleve el menor tiempo posible.

Social Media

8.	INVESTIGAR
	
a.	¿Qué es Twitter Streaming API? Dar un ejemplo de su uso en productos comerciales o por parte de alguna empresa	

El Streaming API proporciona un subset de tweets en casi tiempo real. Se establece una conexión permanente por usuario con los servidores de Twitter y mediante una petición http  se recibe un flujo continuo de tweets en formato json.  Se puede obtener una muestra aleatoria (statuses/sample), un filtrado (statuses/filter) por palabras claves o por usuarios. Sin embargo, los métodos más interesantes cómo obtener todo el caudal de tweets (statuses/firehose) o sólo los tweets que tienen enlaces (statuses/links) o los tweets con retweets (statuses/retweet) “Is not a generally available resource” :-( El Search API suministra los tweets con una profundidad en el tiempo de 7 días que se ajustan a la query solicitada. Es posible filtrar por, cliente utilizado, lenguaje y localización.

En el Streaming API el flujo es continuo y la velocidad de recepción de tweets tendrá fluctuaciones que dependerán del ancho de banda de los dos extremos de la conexión y la sobrecarga de los servidores de Twitter. Actualmente estoy haciendo medidas en dos servidores y publicaré los resultados tan pronto como estén disponibles. En el Search API y en el REST API existe una limitación de 150 peticiones a la hora por usuario o por IP si la llamada no está autenticada. Es importante saber cómo realizar la  paginación de las  peticiones de una manera óptima para sacarle el  máximo partido.

Ejemplo del uso comercial del api de Twitter Streaming

	Inspiración para reportajes: ¿De qué se está hablando en Twitter? ¿Cuáles son los
trending topics del momento? En la tweetósfera se pueden encontrar tendencias sobre las que se puede profundizar e investigar.
	Twittervistas: Twitter permite hacer entrevistas de una forma no invasiva. Uno es entrevistado casi sin darse cuenta, sin que sea algo oneroso. Puedo dar fe de ello porque fui objeto de una de las primeras twittervistas en español. Las ventajas: brevedad en preguntas y respuestas, accesibilidad y asincronía (una entrevista puede durar varias horas sin interrumpir las actividades del entrevistado).
	Verificación de información: A través de Twitter puedes preguntar a tus seguidores sobre la precisión de un dato o contrastar informaciones. La tweetosfera es una masa de conocimiento agregado.
	Noticias urgentes (breaking news): La rapidez de Twitter hace que sea uno de los mejores medios de alerta temprana sobre noticias que están ocurriendo en el momento, en las que la fuente original muchas veces no es un medio de comunicación sino un ciudadano común y corriente.
	Crowdsourcing: También se puede recurrir a Twitter para recabar información que si uno tuviera que buscar por sí mismo tardaría mucho tiempo. Por ejemplo, puedes preguntar a tus seguidores qué opinan sobre cierta medida del gobierno, y usar esas reacciones para escribir un reportaje sobre qué opina la gente sobre tal medida. Twitter es lo más parecido a hacer periodismo de calle, sin salir a la calle.





b.	¿Cómo podría una empresa colombiana usar el Twitter Streaming API?

Entre las compañías que Twitter cita como ejemplos a seguir tenemos a Zappos, Etsy, Pocket Gems, Reuters, ESPN, Esri, Tiny Prints y Feeding America. Los estudios de caso incluyen integraciones inteligentes de los botones de Twitter, de sus características móviles y más. Entre los detalles técnicos se rescatan algunos buenos consejos y sugerencias generales de colaboración.

Uno de los casos más interesantes es el de Reuters, que utilizó Twitter para convertir a los asistentes del World Economic Forums en periodistas ciudadanos. El prestigioso medio de comunicación ha construido una “pared de medios” que Reuters podría utilizar en las conferencias, convenciones políticas, eventos deportivos y otros eventos. En la conferencia en Davos, se capturaron todas las fotos y videos que se tweetearon, permitiendo a sus usuarios ver versiones en alta resolución de los videos y fotos en línea.”

Twitter promete agregar en el futuro más ejemplos que muestran usos interesantes y de alto impacto de su plataforma”. Los ochos casos de éxito pueden leerse completos desde la plataforma de desarrolladores. Allí verán más datos y consejos de buenas prácticas.



DISEÑE UN PROYECTO QUE USE EL TWITTER API, Y QUE AÑADA VALOR AL NEGOCIO DE UNA EMPRESA EN EL CONTEXTO COLOMBIANO. 

Los seguidores son increíblemente valiosos para tu empresa. Cuando una persona decide seguirte en Twitter, no solo verá tus Tweets sino que también es probable que se convierta en cliente y defensora de tu marca.

Al utilizar Twitter api en @proyecto_acueducto, añade valor a la empresa ya que facilita a la misma a mostrarse como empresa, es decir su trabajo, sus procesos, avances y metas aún más sus dificultades, al crear un proyecto con la empresa de acueducto en Colombia donde el usuario pueda observar en la web todos estos elementos anteriormente mencionados será mayor y mejor el flujo de información para el mejoramiento de los servicios y procesos relacionado con la empresa.












REGISTRARSE PARA CREAR UNA APLICACIÓN QUE USE EL TWITTER STREAMING API. GENERAR LAS DIFERENTES CLAVES DE AUTH2 PARA PODER USAR EL API.

    

CLONE EL PROYECTO HTTPS://GITHUB.COM/UNADTDTI/LABORATORIO-PRACTICO.GIT, Y SIGA LAS INSTRUCCIONES EN EL ARCHIVO README. DESPUÉS DE TERMINAR LAS MODIFICACIONES, DESPLIEGUE LA APLICACIÓN WEB EN HEROKU, E INCLUYA LA URL DE LA APLICACIÓN CORRIENDO

https://tecnologiacolaborativa2.herokuapp.com/

 







REFERENCIAS


•	http://wpmallorca.com/2013/02/12/pero-que-es-github/
•	https://codigofacilito.com/articulos/que-es-git
•	http://conociendogithub.readthedocs.io/en/latest/data/introduccion/
•	http://wpmallorca.com/2013/02/12/pero-que-es-github/
•	https://www.ibm.com/developerworks/ssa/opensource/library/os-nodejs/
•	https://es.wikipedia.org/wiki/WebSocket




 









