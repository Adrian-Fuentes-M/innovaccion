# Acordeón Conceptos de Azure
Integrantes del reto:
* Adrián Fuentes Mendoza.
* Jaime Daniel Gallegos Garza.

## ¿Qué es la nube?

La definición de la nube puede parecer poco clara, pero, básicamente, es un término que se utiliza para describir una red mundial de servidores, cada uno con una función única. La nube no es una entidad física, sino una red enorme de servidores remotos de todo el mundo que están conectados para funcionar como un único ecosistema. Estos servidores están diseñados para almacenar y administrar datos, ejecutar aplicaciones o entregar contenido o servicios, como streaming de vídeos, correo web, software de ofimática o medios sociales. En lugar de acceder a archivos y datos desde un equipo personal o local, accede a ellos en línea desde cualquier dispositivo conectado a Internet, es decir, la información está disponible dondequiera que vaya y siempre que la necesite.

## ¿Qué es Azure? 

La plataforma Azure está compuesta por más de 200 productos y servicios en la nube diseñados para ayudarle a dar vida a nuevas soluciones que permitan resolver las dificultades actuales y crear el futuro. Cree, ejecute y administre aplicaciones en varias nubes, en el entorno local y en el perímetro, con las herramientas y los marcos que prefiera.


## Tipos de nubes en Azure

|Tipo de nube|Descripción|
|----|----|
|Nube Privada|Los recursos informáticos son utilizados exclusivamente por usuarios de una empresa u organización. Una nube privada se puede ubicar físicamente en el centro de datos in situ de su organización. También puede ser alojado por un proveedor de servicios externo.
|Nube Publica|Los servicios se ofrecen a través de internet público y están disponibles para cualquier persona que quiera comprarlos. Los recursos en la nube como servidores y almacenamiento son propiedad y son operados por un proveedor de servicios en la nube de terceros y se entregan a través de Internet.
|Nube Híbrida|Este entorno informático combina una nube pública y una nube privada al permitir que los datos y las aplicaciones se compartan entre ellos.|

![nubes](https://www.nephosit.com/wp-content/uploads/2018/04/shutterstock_699701563-1200x800.jpg)
## Modelos de servicio en la nube

- Iaas (Infrestructura como servicio)
- Paas (Plataforma como servicio)
- Saas (Software como servicio)

|Modelo de Servicio|Descripción|
|---|---|
|IaaS|Este modelo de servicio en la nube es el más cercano a la administración de servidores físicos. Un proveedor en la nube mantiene el hardware actualizado, pero el mantenimiento del sistema operativo y la configuración de red se dejan en el inquilino de la nube. Por ejemplo, las máquinas virtuales de Azure son dispositivos informáticos virtuales totalmente operativos que se ejecutan en los centros de datos de Microsoft.|
|Paas|Este modelo de servicio en la nube es un entorno de hospedaje administrado. El proveedor de nube administra las máquinas virtuales y los recursos de red y el inquilino en la nube implementa sus aplicaciones en el entorno de hospedaje administrado. Por ejemplo, Azure App Services proporciona un entorno de hospedaje administrado donde los desarrolladores pueden cargar sus aplicaciones web sin tener que lidiar con los requisitos físicos de hardware y software.|
|Saas|En este modelo de servicio en la nube, el proveedor en la nube administra todos los aspectos del entorno de aplicaciones, como máquinas virtuales, recursos de red, almacenamiento de datos y aplicaciones. El inquilino en la nube solo necesita proporcionar sus datos a la aplicación administrada por el proveedor de nube.|


![modelos](https://www.stackscale.com/wp-content/uploads/2020/04/modelos-servicios-cloud-iaas-paas-saas-stackscale.jpg)



---


# CapEx



<!--weas nuevas mias xd -->
<h2 style="color:#EC7C26;"> Servicios de Azure </h2>

![servicios](https://docs.microsoft.com/en-gb/learn/azure-fundamentals/intro-to-azure-fundamentals/media/azure-services.png)


---

<h2 style="color:#EC7C26;"> DevOps </h2>

DevOps reúne a personas, procesos y tecnología mediante la automatización de la entrega de software para proporcionar valor continuo a sus usuarios. Con Azure DevOps, puede crear canalizaciones de compilación y versión que proporcionen integración continua, entrega e implementación para las aplicaciones. Puede integrar repositorios y pruebas de aplicaciones, realizar la supervisión de aplicaciones y trabajar con artefactos de compilación. También puede trabajar con y trabajar en elementos de trabajo pendiente para el seguimiento, automatizar la implementación de infraestructura e integrar una gama de herramientas y servicios de terceros como Jenkins y Chef.

|Servicio|Descripción|
|----|----|
|Azure DevOps|Utilice herramientas de colaboración de desarrollo como canalizaciones de alto rendimiento, repositorios Git privados gratuitos, placas Kanban configurables y extensas pruebas de carga automatizadas y basadas en la nube.|
|Laboratorios Azure DevTest|Cree rápidamente entornos Windows y Linux bajo demanda para probar o degradar aplicaciones directamente desde canalizaciones de implementación.|

![devops](https://4.bp.blogspot.com/-3s1TcynsAIs/XEQYj4JtHdI/AAAAAAAABOI/N3eWPmf1w9cQSO_b2xppsudhuB6IAQBOQCLcBGAs/s1600/devops.png)

---

<h2 style="color:#EC7C26;"> IoT </h2>

Azure Internet of Things (IoT) es una colección de servicios en la nube administrados por Microsoft que conectan, supervisan y controlan miles de millones de activos de IoT. En términos más sencillos, una solución de IoT se compone de uno o varios dispositivos IoT que se comunican con uno o varios servicios back-end alojados en la nube.

Un dispositivo IoT se compone típicamente de una placa de circuito con sensores conectados que utilizan WiFi para conectarse a Internet. por ejemplo:

- Un sensor de presión en una bomba de aceite remota.
- Sensores de temperatura y humedad en una unidad de aire acondicionado.
- Acelerómetro en ascensor.
- Sensores de presencia en una habitación.

![iot](https://www.whizitservices.com/wp-content/uploads/2020/02/Image-IOT.jpg)

---
<h2 style="color:#EC7C26;"> IA </h2>

La IA, en el contexto de la computación en la nube, se basa en una amplia gama de servicios, cuyo núcleo es el aprendizaje automático. El aprendizaje automático es una técnica de ciencia de datos que permite a las computadoras usar datos existentes para predecir comportamientos, resultados y tendencias futuros. Con el aprendizaje automático, las computadoras aprenden sin ser programadas explícitamente.

|Servicio|Descripción|
|----|----|
|Servicio de aprendizaje automático de Azure|Entorno basado en la nube que puede usar para desarrollar, entrenar, probar, implementar, administrar y realizar un seguimiento de los modelos de aprendizaje automático. Puede generar automáticamente un modelo y ajustarlo automáticamente por usted. Le permitirá comenzar a entrenar en su máquina local y, a continuación, escalar horizontalmente a la nube.|
|Azure ML Studio|Área de trabajo visual colaborativa donde puede crear, probar e implementar soluciones de aprendizaje automático mediante algoritmos de aprendizaje automático precompilado y módulos de control de datos.|

![ia](https://icloudseven.com/wp-content/uploads/2019/02/inteligencia-artificial-implementacion-i-cloud-seven-blog.jpg)

---

<h2 style="color:#EC7C26;"> Big Data</h2>

Los datos vienen en todos los formatos y tamaños. Cuando hablamos de big data, nos referimos a grandes volúmenes de datos. Los datos de sistemas meteorológicos, sistemas de comunicaciones, investigación genómica, plataformas de imágenes y muchos otros escenarios generan cientos de gigabytes de datos. Esta cantidad de datos dificulta el análisis y la toma de decisiones. A menudo es tan grande que las formas tradicionales de procesamiento y análisis ya no son apropiadas.

|Servicio|Descripción|
|----|----|
|Analisis de Synapse de Azure|Ejecute análisis a gran escala mediante un almacenamiento de datos empresarial basado en la nube que aproveche el procesamiento paralelo masivo para ejecutar consultas complejas rápidamente a través de petabytes de datos.|
|Azure HDInsight|Procese cantidades masivas de datos con clústeres administrados de clústeres de Hadoop en la nube.|
|Azure Databricks|Integre este servicio colaborativo de análisis basado en Apache Spark con otros servicios de big data en Azure.|

![bigdata](https://th.bing.com/th/id/R32c5545642e45bfda720d8f1a648e91c?rik=XPXysd5EG1TTpw&pid=ImgRaw)
<!--weas nuevas mias xd -->







