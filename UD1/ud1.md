[Volver al índice general](../README.md)

# UD1 – Análisis del entorno y detección de necesidades tecnológicas

- [ ] **1. Análisis del sector tecnológico**

![sevillatechpark](/UD1/img/techpark.png)

## Sector Tecnologico en Sevilla

Hace unos años, la industria tecnologica en sevilla no terminaba de explotar su potencial, pero a partir del 2020 hasta hoy dia no ha parado de crecer, lo podemos ver reflejado en una de las zonas que producen una parte de la riqueza de sevilla el [Sevilla Tech Park](https://sevillatechpark.es).

 Teniendo en cuenta el [informe](/UD1/documentos/sevillatechpark.pdf) del año 2024, el Sevilla Tech Park generó unos 5.513 Millones de euros, lo que equivale al 11.2% del PIB de la provincia de Sevilla, acogió a 575 entidades que proporcionaban 31000 empleos.
 Dentro de esta entidad la mayor parte de las empresas y empleados pertenecen al sector de las tecnologias avanzadas, que a su vez dentro de ellas, el sector con mas impacto es el sector de Telecomunicaciones e Informatica, suponiendo el 32% de estas.
 Los datos del sector son bastante notables, siendo 94 empresas especializadas solamente en las TIC que generan 995 Millones de euros al año y contando con 11.967 empleados. 

## Demanda de empleo y especializacion
 En el año 2024, aumentaron los empleados con certificacion de tecnico superior, siendo el 19% de los empleados. Este cambio refleja una tendencia creciente por parte de las entidades a incorporar perfiles procedentes de formación profesional.


- [ ] **2. Selección de la empresa o contexto de trabajo**

## Analisis de la Empresa
 
 La empresa que voy a seleccionar es [GMV](https://www.gmv.com/es-es), una empresa multinacional dedicada a la ingenieria y tecnologia.
 Su actividad se divise en 4 puntos:
 - Espacio:  Son lideres mundiales en centros de control de satelites , defensa planetaria y navegación por satelite.
 - Defensa y Seguridad: Desarrollan sistemas de vigilancia de fronteras, ciberdefensa militar y simulacion para las fuerzas armadas.
 - Sistemas Inteligentes de Transporte: Crean tecnologias que gestionan flotas de autobuses y trenes.
 - Sanidad y Ciberseguridad: Potentes divisiones en telemedicina, big data sanitario y proteccion de infraestructuras contra ciberataques.

## Como se organiza
 GMV no es una empresa unica, es un grupo empresarial, que tiene varias filiales especializadas en los campos comentados anteriormente:
 
 - GMV Aerospace and Defense S.A.U: Se encarga de todos los contratos aeroespaciales y de defensa.
 - GMV Soluciones Globales Internet S.A.U: Enfocada en ciberseguridad, banca, transformacion digital y servicios TIC.
 - GMV Sistemas S.A.U: Centrada en el sector de transporte e industria automotriz
 

### Papel de la informatica y los Sistemas en su dia a dia
En GMV es el producto final, la ingenieria de software y los sistemas son el corazon de todo lo que hacen:

- Software: Desarrollan software para maquinas fisicas críticas como satelites, por lo que el codigo debe ser ultraseguro y sin fallos.
- Ciberseguridad: Los sistemas se diseñan con un esquema de seguridad robusto asumiendo todos los riesgos que puedan tener.
- Infraestructura Híbridad: Usan nubes privadas y públicas para procesar cantidades masivas de datos

- [ ] **3. Identificación de necesidades tecnológicas**

## Planteamiento del proyecto

Teniendo en  cuenta que GMV es una empresa a nivel mundial no necesita ningun proyecto para solucionar problemas básicos, son mas bien necesidades de alta necesidad como la escalabilidad o mejorar la eficiencia de los procesos. Por eso detectaremos sus necesidades principales como empresa:

- Gestón de entornos de simulación crítica: Usan un software muy pesado, si ejecutan esto en unos ordenadores simples de oficina, al depender de la potencia de ese equipo, puede ser lento e inseguro que el servidor mueva terabytes de datos a estos equipos.
- Protección absoluta de los datos y seguridad híbrida: Al trabajar con información confidencial, no se pueden permitir ningun fallo en la seguridad de esta. Además con el aumento del teletrabajo, el uso de vpns convencionales puede ser un fallo fatal de seguridad.
- Orden en los entornos de desarrollo: Se deben mantener todos los dispositivos actualizados con los mismos parches de seguridad, librerias y compiladores. Un fallo de una maquina en concreto puede ser una gran perdida de tiempo.


Para gestionar cada uno de estos procesos, crearemos las soluciones propias:

- Crearemos una granja de servidores a los que los usuarios de la empresa accedan y tengan directamente una gran potencia que proviene de los servidores.
-  Implementaremos verificación en dos pasos para que los usuarios de la empresa accedan a la potencia del servidor e insertaremos una micro-segmentacion de la red, con un firewall que no permita al usuario mas que acceder a la aplicacion que le sea necesaria para trabajar y encriptaremos todo el trafico.
-  Crearemos imagenes dispositivos generales para los perfiles que usen las maquinas y asi siempre poder insertar maquinas donde y cuando queramos sin necesidad de desperdiciar tiempo en configurar individualmente cada dispositivo.

- [ ] **4. Oportunidades y viabilidad del proyecto**

 Estas propuestas cumplen con las necesidades de una empresa de la magnitud de GMV, Ademas se podria aplicar en cualquier en esta empresa y en cualquiera que tenga problemas parecidos con la gestion de informacion y el control de acceso.. Tambien soluciona los problemas de creacion de imagenes generales que      cualquier empresa puede necesitar para crear maquinas de manera rápida y sin necesidad de preocuparse.
 
 Aporta beneficios como la 100% seguridad de que los datos no salen del centro de datos, reduces el tiempo de soporte en incidencias individuales, ahorras en hardware ya que no necesitas un equipo potente para cada uno de los empleados solo el servidor potente.

- [ ] **5. Obligaciones legales y normativas**

 Al gestionar usuarios y contraseñas el proyecto esta sujeto al Reglamenteo General de proteccion de datos Europeo (RGPD) y a la Ley Orgánica de Protección de Datos Personales y Garantía de los Derechos Digitales (LOPDGDD)

- En el Art. 32 RGPD la ley obliga a aplicar medidas tecnicas para garantizar un nivel apropiado al riesgo. Esto se cumple ya que el tráfico estara cifrado.

- Ley de Servicios de la Sociedad de la Información y de Comercio Electrónico (La Ley 34/2002   LSSI-CE), es la normativa española que regula las actividades en Internet, estableciendo el marco legal para los servicios digitales.

- ENS (RD 311/2022), Al GMV trabajar con la administración pública y Defensa, sus sistemas deben certificarse en el esquema nacional de Seguridad.

- Licencias de Software, Necesitaria las licencias de windows (por volumen) para los sistemas de los empleados.

- Al proponer un sistema de teletrabajo, Ley de trabajo a distancia (Ley 10/2021)

- [ ] **6. Guion inicial del proyecto**
#### Nombre: Despliegue de infraestructura segura con arquitectura Zero Trust para entornos críticos

#### Datos de la empresa: GMV, Sevillatechpark (Cartuja), Desarrollo de sistemas, software y tecnmologias espaciales.

#### Deteccion de necesidades: Mejorar la potencia de los equipos, Seguridad de los datos, facilitar implementacion de perfiles en los dispositivos.

#### Propuesta de proyecto: Arquitectura de acceso, seguridad perimetral y gestion de sistemas.

#### Conclusión: Al implementar este proyecto en la empresa la empresa obtendra: Seguridad total, Agilidad Operatica y eficiencia. 

## Enlaces a recursos de la unidad

- [Documentos de la unidad](./documentos/)
- [Diagramas e imágenes](./img/)

  ## Bibliografía / Webgrafía 
- Sitio web oficial: [Enlace](https://www.gmv.com/es-es)

