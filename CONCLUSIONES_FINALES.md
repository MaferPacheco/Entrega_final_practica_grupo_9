# ENTREGA FINAL PRUEBA PRÁCTICA

**INTEGRANTES GRUPO 9**

🔹Jonathan Alvarez 

🔹Juan Arias

🔹Fernanda Pacheco

🔹Jairo Siza


## CLASE 1: INTRODUCCIÓN A LAS APLICACIONES WEB, APIS, GIT, GITHUB Y CONTENEDORES. 

En un primer momento, se abordó el tema de la red mundial de servidores conocida como Cloud o computación en la nube, destacando que cada proveedor cuenta con funciones específicas, como es el caso de AWS, Palo Alto, Cloudflare, entre otros. Se generó un debate enriquecedor acerca de las posibles formas de implementar servicios en la nube y se planteó la posibilidad de utilizar un modelo híbrido, el cual combina servicios contratados en la nube con soluciones propias desarrolladas en nuestro entorno SaaS (Software as a Service).

Uno de los aspectos fundamentales de estas infraestructuras de nube es el proceso de virtualización, el cual permite aprovechar los recursos de un mismo servidor físico para crear múltiples sistemas operativos de manera independiente. Existen diferentes tipos de virtualización, cada uno con características específicas. Entre ellos destacan los contenedores, que permiten una mejor distribución y aprovechamiento de recursos a nivel de sistemas operativos. Entre sus principales ventajas se encuentran la reducción de costos, la alta escalabilidad y la disponibilidad confiable de los servicios. No obstante, es importante considerar ciertos riesgos, como la posible exposición de datos sensibles y la alta dependencia de los proveedores de servicios en la nube.

Así mismo, se trabajó sobre la plataforma GitHub, una herramienta de software libre que facilita el control de versiones, el seguimiento de cambios y la colaboración en proyectos de desarrollo de software y gestión de archivos. Se utilizaron diversos comandos como pull, push y branch, los cuales permiten interactuar con la plataforma de manera eficiente. Es importante destacar las buenas prácticas recomendadas, como evitar subir a los repositorios públicos información sensible, tales como claves API, contraseñas, certificados o archivos de configuración .env.
Por otra parte, se revisaron conceptos clave sobre el desarrollo de aplicaciones web, diferenciando entre Frontend, que corresponde a la parte visual e interactiva con el usuario, y Backend, que corresponde a la lógica interna del sistema y los procesos que no son visibles para el usuario final. Se explicó la comunicación entre ambas partes mediante protocolos HTTP/HTTPS, haciendo uso de métodos como GET y PUT, y las respuestas que se pueden obtener en formatos como .csv, .xlsx o .JSON.

Adicionalmente, se profundizó en las APIs REST, las cuales permiten la comunicación entre cliente y servidor a través de solicitudes HTTP/S. Se utilizaron herramientas como Postman, la cual facilita el trabajo de pruebas y gestión de peticiones de manera práctica y eficiente.
Finalmente, se exploraron diversas herramientas de seguridad informática, tales como Wireshark, que permite el análisis y monitoreo del tráfico de red y sus paquetes; Nikto, un escáner de vulnerabilidades en servidores web; Burp Suite, una suite de herramientas para realizar pruebas de seguridad en aplicaciones web; y PortSwigger, una plataforma que ofrece laboratorios y cursos gratuitos enfocados en ciberseguridad, orientados a redes, aplicaciones y protección de datos.

En resumen, se abordaron conceptos fundamentales de tecnologías actuales como computación en la nube, virtualización, control de versiones, desarrollo web y ciberseguridad. Cada tema permitió conocer herramientas prácticas y buenas prácticas aplicables en entornos reales. Este aprendizaje integral fortalece las competencias necesarias para desarrollar, gestionar y proteger infraestructuras tecnológicas modernas, garantizando un mejor desempeño en el área de tecnología y ciberseguridad informática.


## CLASE 2: HERRAMIENTAS PARA ANÁLISIS DE DATOS. 

En la segunda clase se abordaron diversos temas en el ámbito del análisis y gestión de datos, dando una visión sobre cómo extraer la información en diferentes etapas del proceso. Uno de los temas tratados fue la minería de datos, que se centra en descubrir patrones, relaciones y comportamientos ocultos dentro de grandes volúmenes de información. A través de técnicas como la clasificación, el agrupamiento y la detección de reglas de asociación. Se utilizaron herramientas y lenguajes como Python conjuntamente con bibliotecas.

Posteriormente, se estudió el tema de scraping de datos, una técnica utilizada para extraer información de páginas web de forma automática. Esta habilidad es particularmente útil cuando los datos no están disponibles en bases de datos estructuradas o en formatos descargables, se aprendió a desarrollar scripts en Python empleando librerías como BeautifulSoup para extraer contenido HTML, así como las buenas prácticas para evitar sobrecargar servidores o infringir los términos de uso de los sitios.

Otro punto del curso a destacar fue el estudio de bases de datos, tanto relacionales como no relacionales. Se trabajó con sistemas gestores como MySQL, PostgreSQL y SQL Server, aprendiendo a diseñar bases de datos eficientes mediante modelos, normalización de datos y uso de claves primarias y foráneas para mantener la integridad referencial. También se dominó el uso del lenguaje SQL para realizar consultas, manipulación de datos. 

Se exploraron los procesos ETL (Extract, Transform, Load), esenciales para la integración y preparación de datos provenientes de múltiples fuentes. Se aprendió a extraer información desde archivos, bases de datos, transformarla aplicando limpieza, normalización, validación y enriquecimiento, y luego cargarla en un repositorio central, como un data warehouse para el análisis. Estos procesos se implementaron tanto con herramientas como Python utilizando bibliotecas como Pandas.

En conclusión, la clase permitió adquirir una comprensión del ciclo completo del manejo de datos, desde su obtención y almacenamiento hasta su análisis y transformación en información útil. La combinación de minería de datos, scraping, manejo de bases de datos y procesos ETL proporcionó un conjunto de habilidades técnicas y analíticas fundamentales para afrontar los retos actuales en la gestión de información, preparación de reportes, toma de decisiones y desarrollo de proyectos de ciencia de datos.


## CLASE 3: HERRAMIENTAS PARA PRESENTACIÓN DE DATOS.

Durante esta clase nos enfocamos en realizar un proceso completo de tratamiento de datos utilizando un archivo en formato CSV que contenía información sobre correos electrónicos, principalmente relacionados con posibles casos de phishing. El primer paso fue importar el dataset a nuestro entorno de trabajo. Para esto, fue necesario ajustar algunos detalles como el tipo de codificación y el separador del archivo, ya que no venía en el formato más común. Una vez que logramos cargar los datos correctamente, pudimos visualizar su estructura general y empezar a trabajar con ellos.

A continuación, llevamos a cabo un preprocesamiento de los datos. Este paso fue muy importante, ya que nos permitió limpiar el dataset para asegurarnos de que fuera consistente y útil para el análisis. Revisamos si existían valores nulos, errores en los formatos, y se corrigieron algunas columnas que no estaban bien estructuradas. También se organizaron mejor los campos para que reflejaran claramente la información que íbamos a estudiar, facilitando así el análisis posterior.

Una vez que los datos estuvieron limpios, pasamos a explorarlos con más profundidad. Esto nos permitió conocer mejor su contenido, identificar características que se repetían y empezar a entender cómo se comportaban los distintos tipos de correos electrónicos. Gracias a esto, fue posible observar ciertos patrones que podrían estar relacionados con correos legítimos o con correos sospechosos de ser phishing.

Con esa información, procedimos a crear visualizaciones gráficas para mostrar de forma clara y visual los resultados del análisis. Usamos gráficos de barras, histogramas, mapas de calor, entre otros, para representar diferentes aspectos del dataset. Estas visualizaciones nos ayudaron a detectar relaciones entre las variables y a comunicar mejor nuestros hallazgos.

Finalmente, como parte del ejercicio práctico, seleccionamos los primeros registros del dataset ya procesado y los insertamos en una base de datos PostgreSQL. Esta base se encontraba dentro de un entorno de desarrollo llamado devcontainer, que nos permitió simular un entorno profesional de trabajo. Esta última parte fue clave, ya que no solo nos enfocamos en el análisis, sino también en el almacenamiento de datos, como se hace normalmente en un proyecto real.

En general, esta clase fue muy completa, ya que nos permitió aplicar distintas etapas del procesamiento de datos: desde la importación y limpieza, hasta la visualización y la integración con una base de datos. Todo esto nos ayudó a reforzar habilidades esenciales en el análisis de datos, utilizando herramientas modernas y buenas prácticas que se aplican en el mundo real.


## Colaboradores de Clase1

<a href="https://github.com/JonathanAlvarezW">
  <img src="https://avatars.githubusercontent.com/u/203370867?v=4" width="100" height="100" style="border-radius: 50%; object-fit: cover;" />
</a>
<a href="https://github.com/Pirinolas">
  <img src="https://avatars.githubusercontent.com/u/203370598?v=4" width="100" height="100" style="border-radius: 50%; object-fit: cover;" />
</a>
<a href="https://github.com/MaferPacheco">
  <img src="https://avatars.githubusercontent.com/u/203370720?v=4" width="100" height="100" style="border-radius: 50%; object-fit: cover;" />
</a>
<a href="https://github.com/JoelSiza">
  <img src="https://avatars.githubusercontent.com/u/203370601?v=4" width="100" height="100" style="border-radius: 50%; object-fit: cover;" />
</a>
