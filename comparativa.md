# Datos:
## Palabra del día: Compañero. Propietario: abc0072abc. Empresa: 12 Academia de idiomas "Speak Up"

# Licencias y modelos

Diferencia entre Software Libre (FSF), Código Abierto (OSI) y Propietario

El Software Libre(FSF), se centra en las libertades que tienen los usuarios. Estas libertades son poder utilizar el programa para cualquier finalidad, estudiar cómo funciona, modificarlo y distribuir copias o versiones modificadas.

El Código Abierto(Open Source), también permite acceder al código fuente y modificarlo, pero su enfoque está más relacionado con la forma de desarrollar y distribuir el software. La idea es que el código pueda ser revisado, mejorado y compartido por diferentes personas o comunidades.

El Software Propietario tiene el código fuente cerrado y normalmente se necesita una licencia para poder utilizarlo. El desarrollo y las modificaciones dependen de la empresa que lo crea. A cambio, ofrecen soporte técnico profesional, garantías y servicios adicionales.

¿Por qué "libre" no significa "gratuito"?

La palabra "libre" hace referencia a la libertad del usuario y no al precio. Un programa de software libre puede ser gratuito, pero también se puede cobrar por él o por determinados servicios relacionados.

Por ejemplo, una empresa puede utilizar un programa libre sin pagar por la licencia, pero tener que pagar a un técnico para instalarlo, configurarlo, adaptarlo o darle mantenimiento.

Community frente a Enterprise

La edición Community suele ser la versión más abierta y con menos costes de licencia. Permite utilizar las funciones que incluye y, al estar basada en software libre, ofrece más posibilidades de modificar o adaptar el código.

La edición Enterprise es una versión comercial que añade funcionalidades y servicios que no están disponibles en la Community. Por tanto, normalmente implica un coste de licencia o suscripción, pero puede incluir más herramientas y soporte profesional.

# Fichas técnicas

## ERP libre: Odoo Community

- Licencia exacta:
GNU LGPLv3 (GNU Lesser General Public License versión 3).

- Versión vigente:
Odoo 19.0.

- Lenguaje del servidor:
Python 3.10 o superior.

- SGBD compatibles:
PostgreSQL 13 o superior.

- Modalidad:
Puede instalarse localmente, tanto desde código fuente como mediante paquetes para Linux y Windows. También existe la opción de utilizar Odoo online.

- Módulos principales:

CRM
Ventas
Contabilidad y facturación
Inventario
Fabricación
Compras
Recursos Humanos
Marketing
Proyectos
Punto de venta
Sitios web y comercio electrónico

- Requisitos principales:

Python 3.10 o superior.
PostgreSQL 13 o superior.
Dependencias de Python incluidas en requirements.txt.
En Windows se requieren las herramientas de compilación de C++ de Visual Studio para determinadas dependencias.
Para la instalación mediante paquetes se necesita un servidor PostgreSQL.

https://www.odoo.com/documentation/19.0/es/applications.html

## ERP propietario: Microsoft Dynamics 365

Licencia exacta:
Es software propietario/comercial de Microsoft, utilizado mediante las condiciones de licencia y suscripción de Dynamics 365.

Versión vigente:
Dynamics 365 es un producto que recibe actualizaciones continuas, por lo que no funciona como un programa con una única versión fija.

Lenguaje del servidor:
No está especificado públicamente por Microsoft como un único lenguaje de servidor para la versión cloud de Dynamics 365. Por tanto, no sería correcto poner un lenguaje concreto como requisito del producto.

SGBD compatibles:
En la versión cloud, el usuario no instala ni administra directamente el SGBD. Dynamics 365 utiliza la infraestructura de Microsoft y la plataforma Dataverse.

Modalidad:
Principalmente nube, aunque existen componentes y versiones on-premises de Dynamics 365 Customer Engagement. 

Módulos principales:
Dentro de Dynamics 365 existen aplicaciones como:

Sales
Customer Service
Field Service
Finance
Supply Chain Management
Commerce
Human Resources
Project Operations
Customer Insights

Requisitos principales:
Para la versión cloud, se necesita principalmente:

Una licencia/suscripción de Dynamics 365.
Cuenta y entorno de Microsoft/Power Platform.
Navegador y conexión a Internet.

https://learn.microsoft.com/es-es/dynamics365/
https://learn.microsoft.com/es-es/dynamics365/customerengagement/on-premises/deploy/software-requirements-for-microsoft-dynamics-365-server?view=op-9-1


## CRM libre: SuiteCRM

Licencia exacta:
GNU AGPLv3 (GNU Affero General Public License versión 3).

Versión vigente:
SuiteCRM 8.10.x.

Lenguaje del servidor:
PHP 8.2, 8.3 o 8.4 en SuiteCRM 8.10.x.

SGBD compatibles:
Para SuiteCRM 8.10.x:

MariaDB 10.6, 10.11, 11.4 y 11.8
MySQL 8.0 y 8.4

Modalidad:
Principalmente instalación local/on-premise, ya que se puede descargar el paquete de SuiteCRM e instalarlo en un servidor web propio. También existen servicios de hosting ofrecidos por el ecosistema de SuiteCRM.

Módulos principales:

Contactos
Cuentas
Clientes potenciales (leads)
Oportunidades
Ventas
Casos
Documentos
Calendario
Informes
Flujos de trabajo
Gestión de usuarios
Campañas y marketing

Requisitos principales:

Sistema compatible con PHP.
PHP 8.2, 8.3 o 8.4.
Servidor web Apache 2.4.
MariaDB 10.6/10.11/11.4/11.8 o MySQL 8.0/8.4.
Para desarrollo también se indican Angular CLI, Node.js y Yarn.
Es necesario configurar PHP y los módulos PHP requeridos.

https://docs.suitecrm.com/8.x/admin/licensing/
https://docs.suitecrm.com/es/community/supported-versions/
https://docs.suitecrm.com/es/8.x/admin/compatibility-matrix/
https://docs.suitecrm.com/8.x/admin/installation-guide/downloading-installing/

## CRM propietario: Salesforce

Licencia exacta:
Licencia comercial por suscripción, según la edición contratada. Salesforce ofrece diferentes ediciones y precios por usuario, como Starter, Pro Suite y otras opciones para empresas.

Versión vigente:
Salesforce funciona como servicio cloud con actualizaciones continuas, por lo que no tiene una única versión instalable equivalente a "Salesforce 19" o similar.

Lenguaje del servidor:
Para desarrollar lógica en el servidor se utiliza Apex, lenguaje propietario de Salesforce con sintaxis parecida a Java. 

SGBD compatibles:
No se especifica un SGBD instalable compatible, porque Salesforce es un servicio cloud y el cliente no instala ni administra directamente la base de datos. Salesforce gestiona la infraestructura y el almacenamiento de datos de la plataforma.

Modalidad:
Nube (SaaS). Se utiliza mediante Internet desde navegador y también dispone de aplicación móvil. Salesforce indica que se puede acceder y actualizar el CRM desde diferentes dispositivos.

Módulos principales:

Gestión de clientes potenciales
Cuentas
Contactos
Oportunidades
Gestión del pipeline de ventas
Previsiones de ventas
Informes y dashboards
Automatización de procesos
Gestión de actividades
Marketing y atención al cliente mediante las soluciones correspondientes
IA/Agentforce

Requisitos principales:
Al ser un servicio cloud, no es necesario instalar el servidor ni un SGBD. Para utilizarlo desde un ordenador se necesita:

Conexión a Internet.
Navegador compatible.
JavaScript y cookies activados.
TLS 1.2 o 1.3.
Salesforce recomienda utilizar versiones estables actuales de Chrome, Firefox, Edge o Safari.

https://help.salesforce.com/s/articleView?id=platform.code_about.htm&language=es&type=5
https://help.salesforce.com/s/articleView?id=xcloud.getstart_browser_recommendations.htm&type=5

# Fe de erratas del tema

- Oracle ERP Cloud considerado el mejor según estudios actuales» es una afirmación demasiado general

Diapositiva 8

Qué es correcto:
La frase es demasiado general porque no indica qué estudio, de qué año ni qué criterios se han utilizado.

Actualmente Oracle ofrece Oracle Fusion Cloud ERP, que sigue siendo una plataforma ERP en la nube y recibe actualizaciones continuas. Oracle también publica informes de analistas en los que aparece reconocido en determinadas categorías, pero eso depende del estudio y de los criterios utilizados. Por ejemplo, Oracle señala que fue reconocido en Gartner Peer Insights 2026 en una categoría concreta de ERP.

Por tanto, sería más correcto decir algo como: "Oracle Fusion Cloud ERP es una solución ERP en la nube y ha recibido reconocimientos en diferentes estudios de analistas".

https://www.oracle.com/es/corporate/analyst-reports/applications/

- La versión de Odoo aparece como 15

Diapositiva 7

Qué es correcto:
Ese dato está desactualizado. Actualmente la versión de referencia es Odoo 19, publicada en septiembre de 2025. La documentación oficial de Odoo ya está en la versión 19.0.

https://www.odoo.com/es/odoo-19-release-notes


