# Curso basico con Big Data
![postgre_instal_](src/1.webp)
- [IniciandoConBigData](#IniciandoConBigData)
- [Cloud Computing en proyectos de BigData](#CloudComnputingEnProyectos)
- [Introducción al manejo de datos en Cloud](#IntroducciónalmanejodedatosenCloud)
- [Datos Cloud](#DatoCloud)
- [¿Qué nube debería utilizar en mi proyecto de Big Data?](#QueNubeUtilizar)
- [Arquitecturas Lambda](#ArquitecturaLambda)
- [Arquitectura Kappa](#ArquitecturaKappa)
- [Arquitectura Batch](#ArquitecturaBatch)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)
- [](#)

## IniciandoConBigData
- Big Data es un campo orientado al análisis, procesamiento y almacenamiento de grandes cantidades de información que permite mejorar el valor de tu negocio. Utilizando la información mediante este esquema podemos detectar puntos de optimización en diferentes áreas.
- Los proveedores de servicios de nube son empresas que instalan nubes públicas, gestionan nubes privadas u ofrecen elementos de cloud computing (también llamados servicios de cloud computing) según se soliciten, lo cual incluye las Infraestructuras como servicio (IaaS), las Plataformas como servicio (PaaS)
- Infraestructura como servicio (IaaS) se refiere a los servicios en línea que proporcionan un alto-nivel de APIs utilizadas para indireccionar detalles a bajo nivel de infraestructura como recursos de informática física, ubicación, dato partitioning, scaling, seguridad, copia de seguridad etc.

- Servicio basado en plataforma es una categoría de servicios de computación en la nube que permite a los clientes aprovisionar, instanciar, ejecutar y administrar un paquete modular que comprende una plataforma informática y uno o más aplicaciones, sin la complejidad de construir y mantener la infraestructura típicamente asociada con el desarrollo y lanzamiento de la(s) aplicación(es); y para permitir que los desarrolladores creen, desarrollen y empaqueten dichos paquetes de software .

- Actualmente encontramos diferentes proveedores de Cloud computing con soporte de Big Data, compitiendo entre sí por atraer la mayor cantidad de clientes a sus nubes, destacando Amazon Web Services por sus múltiples servicios para manejo de grandes cantidades de información.

- En este curso aprenderás:

¿Cómo tomar data desde el origen para llevarla a Cloud?
¿Cómo transformar la data?
¿Cómo visualizar la data?
¿Cómo proteger los datos?
Tomando en cuenta tres aspectos importantes:

Automatizar todos los procesos.
Orquestar las distintas tareas.
Involucrar un buen nivel de seguridad sobre nuestros datos.
- Antes de comenzar este curso te sugerimos tomar previamente los cursos de :

Amazon Web Services
Cloud Computing
Storage en AWS
Base de datos en AWS

## CloudComnputingEnProyectos
- vas a aprender a:
   - Cómo tomar data desde el origen para llevarla a Cloud.
   - Cómo transformar la data.
   - Cómo visualizar la data.
   - Tomando en cuenta tres aspectos importantes:

Automatizar todos los procesos.
Orquestar las distintas tareas.
Involucrar un buen nivel de seguridad sobre nuestros datos.
## IntroducciónalmanejodedatosenCloud
- Cunado trabajas en la nube puedes tener un crecimiento escalable"cloud provider", puedes manejar:
  - Cantidad:Nos soportan estas cantidades de datos
             - MetaByte
             - GygaByte
             - TeraByte
             - PentaByte
             - HexaByte
  - Escalabilidad: Crecimiento por demanda, escalabilidad de acuerdo a la cantidad de informacion
  - Automatizacion: Procesos automatizados
  - Eficiencia: Recursos facilmente y al alcande de todos
  ejemplo: nos deben cobrarnos por el uso que se consumo
  - Ahorro: Reduccion de costo de proyectos
  - Flexibilidad: Existen diferentes cloud providers como: GoogleCloudPlatform,Azure, alivaba y hay diferentes tipos de configuracion.
  "se va poder migrar a donde tu quieres rapidamente"

## DatoCloud
Hay algunos puntos importantes que debemos tener en cuenta al momento de manejar nuestra data en un servicio en la nube:

- Debemos seleccionar el servicio que mejor se ajuste a nuestras necesidades de almacenamiento.
- Lo primero que debemos hacer es extraer de otras fuentes la información que vamos a necesitar.
- Debemos validar nuestra información, verificar que sea consistente.
- Verificar los tipos de datos que vamos a extraer.
- Al momento de realizar pruebas a nuestra información debemos utilizar un subset de la data.
- pasos:
  - Extraccion: Extraer y llevarle al mundo cloud
  - Ingesta:Ella envia informacion al cloud y en cloud nosotros reciviremos la informacion y pasaremos a procesarla
  - Validacion de la informacion: Grantizar la consistencia de los datos.
  - Verificaion: Verificar bien el tipo de datos
  - Test:Los test se corren sobre un porcentaje de data para garantizar el proceso que involucra.

## QueNubeUtilizar
Actualmente el mercado de Cloud Computing tiene varios actores compitiendo entre sí por atraer la mayor cantidad de clientes a sus nubes, encontramos Múltiples opciones como: Amazon Web Services, Azure, Alibaba Cloud, Google Cloud Platform, Oracle Cloud, Rackspace, Digital Ocean y Softlayer entre muchas otras.

- Dentro de esta variedad de proveedores muchas veces es complejo tomar decisiones de cuál utilizar, el criterio para esta decisión puede estar dado por diferentes factores como:

  - 1. Costo: Valor de los servicios que serán utilizados en el proyecto.
  - 2. Tipo de pricing: Por demanda (por hora, minuto o segundo), subasta, reservado.
  - 3. Servicios: Variedad de servicios provistos por el cloud provider. ¿Cuál servicio se ajusta mejor a mis necesidades?
  - 4. Ubicación: Distribución de las regiones/zonas donde el cloud provider preste servicios por temas de latencia y experiencia usuario esto puede ser decisivo.
  - 5. Niveles de Servicio: Consultar la documentación por servicio y los niveles ofrecidos de disponibilidad.
  - 6. Soporte: Tipos de soporte, costo, tiempos de respuesta y nivel de soporte (basic, business, enterprise).
  - 7. Estudios de mercado: Revisar los diferentes estudios de mercado, por ejemplo: el cuadrante mágico de Gartner, en los cuales se evalúan en diferentes aspectos los servicios provistos.
  - 8. Documentación: Consultar la documentación de los cloud provider, muchas veces no es muy clara o está incompleta referente a sus servicios.
  ![ComunLosCloudProviders](src/2.webp)

Después de revisar las diferentes opciones que proveen los cloud providers encontramos variedad en servicios de acuerdo a su funcionalidad, otras nubes como Azure, Softlayer, Alibaba también cuentan con servicios orientados al procesamiento de datos, sin embargo dentro de su ecosistema no es tan completo el set de servicios, por tal motivo siempre que pensemos en proyectos de BigData los mejores cloud provider serán AWS y GCP que estudiaras en este curso.

## ArquitecturaLambda
Diseñanda para ser escalable:

- Tiene una gran robustez, puede procesar una alta cantidad de datos. Está compuesta por tres capas:

  - Batch: En esta capa vamos a procesar toda la información almacenada con anterioridad, desde el día anterior hasta meses.
  - Serve: Dentro de esta capa es posible visualizar la data procesada de la capa batch.
  - Speed: Conforme llega la data se va a ir procesando.
 ![ComunLosCloudProviders](src/3.png)

 ## ArquitecturaKappa
 Fue presentada por Jay Krepsen en el 2014 como una evolución de la arquitectura lambda. Elimina la capa batch haciendo que todo se procese en tiempo real.

- La arquitectura Kappa sigue los siguientes pilares:

  - Todo es un stream.
  - Información de origen no modificada.
  - Solo un flujo de procesamiento.
  - Capaz de reprocesar.
  Ejemplo: ver en tiempo real cuantos usuarios estan en la aplicacion y tomar buenas decisiones mas rapida y el comportamiento que tienen los usuarios.
   ![ComunLosCloudProviders](src/4.png)
## ArquitecturaBatch

Es una parte especifica de la arquitectura lamba es importante ver ya que necesitamos saber como funiona en el batch:
![ComunLosCloudProviders](src/5.png)
https://www.paradigmadigital.com/techbiz/de-lambda-a-kappa-evolucion-de-las-arquitecturas-big-data/
