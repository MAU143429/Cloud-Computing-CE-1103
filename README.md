# Instituto Tecnológico de Costa Rica

# Área Académica de Ingeniería en Computadores

# Investigación Cloud Computing

![](https://cdn.discordapp.com/attachments/693288242279219231/736089626644709467/lgo_tec.png)


# Algoritmos y Estructuras de Datos I 


# Profesor: Diego Noguera Mena

# Mauricio Calderón Chavarría 2019182667	

# José Antonio Espinoza 2019083698

# I Semestre 2020


# Definición e Historia sobre el Cloud Computing

El cloud computing o también conocido como la computación de la nube, es una tecnología que permite a las empresas o usuarios el almacenamiento y procesamiento de  datos por medio de internet facilitando así el acceso a los datos a través de cualquier dispositivo,  hora y lugar, debido a que no es necesario instalar nada para poder utilizarla y se puede acceder en todo momento, el término de la computación en la nube también puede conocerse como la prestación de un servicio a través de internet  por parte de un proveedor.
  
Si bien el cloud computing puede verse como un concepto algo nuevo en realidad no lo es ya que su historia se remonta  desde 1961 cuando  John McCarthy decide  apostar por la computación compartida, con la gran idea de vender el uso de memoria y espacio como un servicio público más. Luego de esto Joseph Carl Robnett Licklider en 1969 a quien también se le conoce como uno de los pioneros de la computación en la nube,  plantea la necesidad de un sistema que permitiera a varios usuarios compartir información y estar interconectados desde cualquier lugar ya que muchas empresas llegaban a necesitar consultar cantidades de datos muy grandes y recurrir a mas equipo no era una opción viable. Fue hasta la llegada del internet en 1983 cuando Joseph Carl despues de muchas investigaciones logró encontrar una manera de conectar personas utilizando la red como su principal elemento, de ahí surge Arpanet, que fue una red global de comunicación.

Después del lanzamiento de Arpanet se comenzó a expandir más el concepto de la computación en la nube, que pronto pasaría de ser un concepto a toda una realidad ya que varias empresas como Amazon, Google y AT&T decidieron comenzar un desarrollo en esta área. Fue tanto el impacto que aún se siguen disputando el papel de quien creo y contextualizó el concepto de la computación en la nube.

Ya para finales de los 90, se produjo un gran avance  en la computación en la nube debido a que se inauguró Salesforce, lo que podría considerarse que llevó a los servicios de nube al éxito y propició que muchas empresas comenzaron con el desarrollo de muchos tipos de nubes que luego fueron dando a luz a través de los años hasta lo que conocemos hoy en dia.

# Conceptos Básicos

**Virtualización**: Se puede definir como la reproducción virtual de un recurso tecnológico, como por ejemplo un dispositivo de almacenamiento, sistema operativo, plataforma de hardware o software. La virtualización es una parte fundamental de la computación en la nube ya que ella permite el buen funcionamiento de la infraestructura técnica que permite brindar servicios alojados en una nube.

**Proveedores de servicio**: Son aquellas compañías que ofrecen un servicio de alojamiento de datos a través de internet, como lo pueden ser Amazon,Google, Microsoft Azure etc.

**Aplicaciones virtuales**: Son aquellas aplicaciones, funciones o herramientas las cuales están disponibles desde la nube y el usuario que las utiliza no requiere de ningún software para poder utilizarlas ya que funcionamiento principal de estas ya se encuentra dentro de los servicios brindados por la nube.

**Big Data**: Este término agrupa una serie de técnicas para el procesamiento de grandes cantidades de datos englobando gran variedad de ideas y aproximaciones con el fin de obtener información valiosa de los datos que puedan llegar a ser útiles.

 
# Modelos de despliegue

## Cloud Privado
La nube privada es aquella en la que solamente una organización tiene acceso a los recursos de la empresa que se encuentra en la nube, es decir una empresa dispone de un entorno en el cual únicamente los colaboradores de la misma tiene acceso a la información. Se podría llegar a comparar un Cloud Privada con un DataCenter con los que cuentan ciertas empresas para el manejo de sus datos.Este modelo sin embargo puede llegar a ser demasiado caro para muchas empresas, pues si bien es cierto aportan mucha flexibilidad y adaptación con los Data Center, requiere de una inversión bastante grande tanto para la adquisición del equipo, como su posterior gestión.

## Cloud Público
Un despliegue de cloud público se caracteriza por ofrecer recursos TIC entre múltiples clientes. Para poder acceder a estos recursos el cliente debe tener conexión a Internet o bien se puede realizar mediante conexiones VPN. Es habitual que en las nubes públicas los clientes accedan  mal servicio como un cliente externo .Las nubes públicas pueden complementarse con servicios de balance, aceleración de carga y de BackUp, ha diferencia de las clouds privadas, el hecho de compartir recursos permite que el coste de el cloud baje siendo mucho más barato que un cloud privado.

## Cloud Híbrido
Un despliegue de Cloud Híbrido es una combinación entre un Cloud Privado y un Cloud Público, el cloud híbrido surge  debido a la necesidad de ciertos clientes quienes cuentan con la infraestructura y además desean aprovechar las ventajas de los servicios de un proveedor externo.Este despliegue híbrido aporta mucha agilidad y reducción sin embargo sacrifica un poco de control. Sin embargo no todo es bueno ya que el utilizar una cloud híbrida puede llegar a ser un proceso bastante complejo pues requiere una coordinación tanto de estructura propia como de otra gestionada por el otro entorno.

# Modelos de servicio

## Infraestructura como servicio IaaS.
Este modelo de servicio le proporciona a los usuarios acceso a recursos como servidores,almacenamiento y redes, para este modelo las empresas utilizan sus propias plataformas y aplicaciones en una infraestructura de proveedor de servicios.

## Plataforma como servicio SaaS
Este modelo proporciona a los usuarios un software basado en cloud de un proveedor, en la cual los usuarios tampoco tienen que instalar aplicaciones en sus computadoras para poder acceder ya que las aplicaciones residen en una red cloud que siempre está disponible y se puede acceder desde una web o una API. Mediante esto los usuarios pueden almacenar y analizar datos, además de poder colaborar.

## Software como servicio PaaS
Proporciona a los usuario un entorno en el cual se puede desarrollar, gestionar y distribuir aplicaciones, aparte de poder personalizar y probar sus propias aplicaciones. El PaaS incluye la misma infraestructura de  las IaaS pero también incluyen middleware, herramientas de desarrollo y servicios de inteligencia empresarial a parte de un gran sistema de administración de bases de datos

# Comparativa entre los tres pricipales proveedores de Cloud Computing

|| Oferta General | Posicionamiento en el Mercado | Beneficios para Desarrolladores |
|---|---|---|---|
|Amazon Web Services|Amazon Web Services ofrece al público una gran cantidad de servicios con varios enfoques. Ofrece herramientas para análisis de datos, como lo es Amazon Athena, el cual es un servicio de tipo SaaS y es implementado con SQL. Ofrece servicios de creación de aplicaciones en realidad virtual y realidad aumentada, utilizando Amazon Sumerian. Brinda el servicio de blockchain, para manejo de transacciones sin necesidad de una autoridad central, este servicio lo brindan mediante Amazon Managed Blockchain, el cual es de tipo IaaS. Amazon ofrece también, servicios de configuración, uso y escala de bases de datos en la nube mediante el servicio de Amazon RDS el cual automatiza procesos administrativos como configuración de las bases de datos, implementación de parches y creación de copias de seguridad. Amazon RDS proporciona seis motores de bases de datos, entre los que sobresalen MySQL, SQL Server y Oracle Database. Este servici de tipo PaaS ofrece darle un mayor rendimiento a los sistemas de datos para compañías. Como último ejemplo, (aunque AWS cuenta con muchos más servicios) tenemos el servicio de almacenamiento en la nube, brindado por Amazon S3. Este servicio de tipo PaaS ofrece almacenamiento y protección de cualquier cantidad de datos para diversos casos de uso, como lo son sitios web, aplicaciones móviles y análisis de Big Data.[10]|Se presenta como el mejor proveedor de servicios de nube. Registrando ganancias de 46,1 millones de dólares y presentando un crecimiento del  32% en el año 2020.[5]|AWS ofrece a los desarrolladores múltiples herramientas para la creación, mejoramiento y depuración de código. Entre estas está Amazon Corretto, con este servicio se pueden desarrollar y ejecutar aplicaciones Java en sistemas operativos conocidos, como Linux, Windows y macOS. Otro servicio que AWS ofrece a los desarrolladores es un kit de desarrollo de la nube propio de AWS, este es un marco de código open-source utilizado para modelar y manejar recursos destinados a aplicaciones en la nube con soporte para múltiples lenguajes de programación. También ofrecen el servicio de AWS Cloud9, el cual es un IDE basado en la nube que permite escribir, ejecutar y depurar código solamente desde el navegador. Por último, AWS ofrece un servicio de implementación, desarrollo y trabajo de proyectos mediante el AWS CodeStar. Este proporciona una interfaz que permite administrar el acceso a proyectos, facilita el trabajo de proyectos en grupo y busca eficiencia del trabajo de los desarrolladores, lo interesante es que incorpora un panel de administración de proyectos basado en la tecnología de Atlassian Jira Software, para ofrecer a los desarrolladores un entorno de trabajo y tareas.[10]|
| Microsoft Azure | Ofrece servicios en las tres capas de la nube (IaaS, PaaS y SaaS). En su servicio Saas permite alquilar aplicaciones y software únicamente, el manejo de servidores, datos, OS y almacenamiento son manipulados por otros administradores. Su servicio PaaS ofrece el alquiler de todo menos la aplicación, permite tener manejo de la aplicación y datos, mientras que la  nube de Microsoft se encarga de tiempos de ejecuciones, OS, middleware, networking, servidores y almacenamiento. Por último su IaaS se puede alquilar las herramientas y hardware para poder manejar datos, aplicaciones, tiempos de ejecución, middleware y OS; mientras que la nube de Microsoft se encarga de servidores, almacenamiento, networking y virtualización. La oferta de Microsoft como proveedor de servicios de la nube es muy variada. Cuenta con un mayor servicio de nube llamado Microsoft Azure, el cual es de tipo PaaS y IaaS. Es un servicio utilizado por  desarrolladores de aplicaciones utilizando herramientas propias de la empresa. Otro servicio, posiblemente las aplicaciones de creación de documentos más conocidas a nivel mundial, Microsoft Office 365. Este servicio es relativamente nuevo en el ambiente de la nube. Esta apertura lo convierte en un servicio de tipo SaaS capaz de permitir a los usuarios a que accedan a correos electrónicos, calendarios, trabajar con cualquier aplicación de Office desde cualquier lugar e inclusive aplicaciones con capacidad de crear conferencias con buena seguridad en la web[6].|Se presenta como el segundo  mejor proveedor de servicios de nube. Registrando ganancias de hasta 23,6 millones de dólares y presentando un crecimiento del  45% en el año 2020.[5]|Microsoft Azure permite flexibilidad de conexión ofreciendo una nube híbrida, la cual conecta recursos locales y en la nube. Utiliza tecnologías de código abierto para maximizar la portabilidad . Ofrece herramientas de desarrollo en la nube, como lo son Azure Portal, PowerShell y DevOps. Ofrece a los desarrolladores una nube segura para el almacenamiento y manejo de proyectos.  Ofrece herramientas y APIs propios de Azure para la creación de aplicaciones de internet y móviles. Ofrece servicios de análisis predictivo como lo es Machine Learning.[9]|
|Google Cloud Computing|Google Cloud Computing ofrece, al igual que los otros competidores, una gran cantidad de servicio con enfoques similares. Un servicio que ofrece es el de Google Compute Engine, el cual se enfoca en la utilización de máquinas virtuales alojadas en la nube. Otro servicio que ofrece es el de Google Kubernetes Engine, el cual ofrece un ambiente enfocado en el despliegue, gestión y escala de aplicaciones utilizando la infraestructura ofrecida por Google. El ambiente GKE consiste en un grupo de múltiples Computer Engines unidas formando un cluster. También ofrece el servicio de almacenamiento de datos mediante la utilización del servicio Google Cloud Storage. Ofrece servicios de traducción, text-to-speech y speech-to-text alojados en la nube. También tiene el servicio de Apigee, el cual se enfoca en un ambiente para empresas de desarrollo en el diseño, seguridad y escala de APIs. Por último, ofrecen servicios de bases de datos mediante Cloud SQL, el cual permite configurar, administrar y mantener bases de datos en Google Cloud Platform. Este servicio permite la utilización de MySQL, PostgreSQL y SQL Server para su implementación.[11]|Se presenta como el tercer mejor proveedor de servicios de nube. Registrando ganancias de 6,7 millones de dólares y presentando un crecimiento del  55% en el año 2020.[5]|Entre los beneficios y servicios que Google ofrece a los desarrolladores se encuentra Cloud Code, el cual incluye herramientas para escribir, implementar y depurar aplicaciones nativas de la nube. Proporciona extensiones para IDEs como IntelliJ y Visual Studio Code. Google también ofrece APIs y bibliotecas de cliente propias alojadas en la nube para asegurar que el desarrollador optimice al máximo la creación de un proyecto basado en el SDK de Cloud. Ofrece servicios de compilación de código, como lo es Cloud Build. Con este servicio se puede compilar software con rapidez en todos los lenguajes. Permite el trabajo en ambientes como máquinas virtuales, serverless y Kubernetes. Por último, ofrece servicios de recursos para proyectos como Cloud Deployment Manager el cual permite especificar todos los recursos necesarios para aplicaciones en un formato declarativo con el uso de yaml; utiliza plantillas de Python para parametrizar la configuración de los programas.[11]|

# Referencias
[1]. Historia del cloud computing, ¿quién lo hizo posible?. Available: https://einatec.com/historia-cloud-computing/#:~:text=El%20cloud%20computing%20es%20un,dispositivo%20con%20conexi%C3%B3n%20a%20Internet.

[2]  Conceptos Básicos de Cloud Computing – ¿Qué necesito saber?. Available: https://www.temastecnologicos.com/cloud-computing/.

[3] (1 de Noviembre de). Modelos de despliegue cloud: Cloud privado, cloud público y cloud híbrido. Available: https://nexica.com/es/blog/modelos-de-despliegue-cloud-cloud-privado-cloud-p%C3%BAblico-y-cloud-h%C3%ADbrido.

[4] . IaaS, PaaS y SaaS – Modelos de servicio de IBM Cloud. Available: https://www.ibm.com/es-es/cloud/learn/iaas-paas-saas.

[5] (July 1,). Top cloud providers in 2020: AWS, Microsoft Azure, and Google Cloud, hybrid, SaaS players. Available: https://www.zdnet.com/article/the-top-cloud-providers-of-2020-aws-microsoft-azure-google-cloud-hybrid-saas.

[6] (Oct 16,). Which are the 6 Fundamental Microsoft Cloud Services that are in Demand?. Available: https://www.simplilearn.com/6-fundamental-microsoft-cloud-services-that-are-in-demand-rar365-article.

[7] (26 de abril). Amazon Web Services. Available: https://www.ticportal.es/temas/cloud-computing/amazon-web-services.

[8] (18 de Julio). IBM Cloud (formerly IBM Bluemix and IBM SoftLayer). Available: https://searchcloudcomputing.techtarget.com/definition/IBM-Bluemix.

[9] (24 Marzo). ¿QUÉ ES MICROSOFT AZURE Y CUÁLES SON SUS BENEFICIOS?. Available: https://www.executrain.com.mx/blog/microsoft/item/que-es-microsoft-azure-y-cuales-son-sus-beneficios.

[10] (). Comience a crear con AWS hoy mismo. Available: https://aws.amazon.com/es/.

[11] (May 20,). What Google Cloud Platform is and why you’d use it. Available: https://www.zdnet.com/article/what-google-cloud-platform-is-and-why-youd-use-it/.

[12] Sloyer Jeff, "Deploying a Hello World Python Flask App in IBM Bluemix (Cloud Foundry)," vol. YouTube, 19 marzo, 2015.

[13] Parsons Chris, "Google Cloud Platform - Python Tutorial," vol. YouTube, 15 de nov, 2016.

# Link al repositorio y las aplicaciones



**Repositorio**: https://github.com/MAU143429/Investigacion-Cloud-Computing

**Links de las Aplicaciones**:
1) Aplicación "Hello" en IBM Cloud: [http://ibmsimpleapp-quick-emu-ip.mybluemix.net/](http://ibmsimpleapp-quick-emu-ip.mybluemix.net/). Desarrollada en Python, Proveedor: IBM Cloud, Alojado en IBM Cloud como: ibmsimpleapp.

2)Aplicación "" en Google Cloud Platform:

3)Aplicación "" en Microsoft Azure:

