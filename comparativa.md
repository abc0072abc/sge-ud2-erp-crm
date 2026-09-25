# 1. Datos:

**Palabra del día:** Compañero
**Propietario:** abc0072abc
**Empresa:** 12 Academia de idiomas "Speak Up"

# 2 .Licencias y modelos

## Diferencia entre Software Libre (FSF), Código Abierto (OSI) y Propietario

El **Software Libre(FSF)**, se centra en las libertades que tienen los usuarios. Estas libertades son poder utilizar el programa para cualquier finalidad, estudiar cómo funciona, modificarlo y distribuir copias o versiones modificadas.

El **Código Abierto(Open Source)**, también permite acceder al código fuente y modificarlo, pero su enfoque está más relacionado con la forma de desarrollar y distribuir el software. La idea es que el código pueda ser revisado, mejorado y compartido por diferentes personas o comunidades.

El **Software Propietario** tiene el código fuente cerrado y normalmente se necesita una licencia para poder utilizarlo. El desarrollo y las modificaciones dependen de la empresa que lo crea. A cambio, ofrecen soporte técnico profesional, garantías y servicios adicionales.

# ¿Por qué "libre" no significa "gratuito"?

La palabra **"libre"** hace referencia a la libertad del usuario y no al precio. Un programa de software libre puede ser gratuito, pero también se puede cobrar por él o por determinados servicios relacionados.

Por ejemplo, una empresa puede utilizar un programa libre sin pagar por la licencia, pero tener que pagar a un técnico para instalarlo, configurarlo, adaptarlo o darle mantenimiento.

## Community frente a Enterprise

La edición **Community** suele ser la versión más abierta y con menos costes de licencia. Permite utilizar las funciones que incluye y, al estar basada en software libre, ofrece más posibilidades de modificar o adaptar el código.

La edición **Enterprise** es una versión comercial que añade funcionalidades y servicios que no están disponibles en la Community. Por tanto, normalmente implica un coste de licencia o suscripción, pero puede incluir más herramientas y soporte profesional.

# 3 .Fichas técnicas

## ERP libre: Odoo Community

- **Licencia exacta:** GNU LGPLv3 (GNU Lesser General Public License versión 3).
- **Versión vigente:** Odoo 19.0.
- **Lenguaje del servidor:** Python 3.10 o superior.
- **SGBD compatibles:** PostgreSQL 13 o superior.
- **Modalidad:** Puede instalarse localmente, tanto desde código fuente como mediante paquetes para Linux y Windows. También existe la opción de utilizar Odoo Online.

### Módulos principales
- CRM
- Ventas
- Contabilidad y facturación
- Inventario
- Fabricación
- Compras
- Recursos Humanos
- Marketing
- Proyectos
- Punto de venta
- Sitios web y comercio electrónico

### Requisitos principales
- Python 3.10 o superior.
- PostgreSQL 13 o superior.
- Dependencias de Python incluidas en `requirements.txt`.
- En Windows se requieren las herramientas de compilación de C++ de Visual Studio para determinadas dependencias.
- Para la instalación mediante paquetes se necesita un servidor PostgreSQL.

**Fuente oficial:**  
https://www.odoo.com/documentation/19.0/es/applications.html

## ERP propietario: Microsoft Dynamics 365

- **Licencia exacta:** Es software propietario/comercial de Microsoft, utilizado mediante las condiciones de licencia y suscripción de Dynamics 365.
- **Versión vigente:** Dynamics 365 es un producto que recibe actualizaciones continuas, por lo que no funciona como un programa con una única versión fija.
- **Lenguaje del servidor:** No está especificado públicamente por Microsoft como un único lenguaje de servidor para la versión cloud de Dynamics 365. Por tanto, no sería correcto poner un lenguaje concreto como requisito del producto.
- **SGBD compatibles:** En la versión cloud, el usuario no instala ni administra directamente el SGBD. Dynamics 365 utiliza la infraestructura de Microsoft y la plataforma Dataverse.
- **Modalidad:** Principalmente nube, aunque existen componentes y versiones *on-premises* de Dynamics 365 Customer Engagement.

### Módulos principales
- Sales
- Customer Service
- Field Service
- Finance
- Supply Chain Management
- Commerce
- Human Resources
- Project Operations
- Customer Insights

### Requisitos principales
- Una licencia o suscripción de Dynamics 365.
- Cuenta y entorno de Microsoft/Power Platform.
- Navegador y conexión a Internet.

**Fuentes oficiales:**
https://learn.microsoft.com/es-es/dynamics365/
https://learn.microsoft.com/es-es/dynamics365/customerengagement/on-premises/deploy/software-requirements-for-microsoft-dynamics-365-server?view=op-9-1


## CRM libre: SuiteCRM

- **Licencia exacta:** GNU AGPLv3 (GNU Affero General Public License versión 3).
- **Versión vigente:** SuiteCRM 8.10.x.
- **Lenguaje del servidor:** PHP 8.2, 8.3 o 8.4 en SuiteCRM 8.10.x.
- **SGBD compatibles:** MariaDB 10.6, 10.11, 11.4 y 11.8; MySQL 8.0 y 8.4.
- **Modalidad:** Principalmente instalación local/on-premise, ya que se puede descargar el paquete de SuiteCRM e instalarlo en un servidor web propio. También existen servicios de hosting ofrecidos por el ecosistema de SuiteCRM.

### Módulos principales
- Contactos
- Cuentas
- Clientes potenciales (leads)
- Oportunidades
- Ventas
- Casos
- Documentos
- Calendario
- Informes
- Flujos de trabajo
- Gestión de usuarios
- Campañas y marketing

### Requisitos principales
- Sistema compatible con PHP.
- PHP 8.2, 8.3 o 8.4.
- Servidor web Apache 2.4.
- MariaDB 10.6/10.11/11.4/11.8 o MySQL 8.0/8.4.
- Para desarrollo también se indican Angular CLI, Node.js y Yarn.
- Es necesario configurar PHP y los módulos PHP requeridos.

**Fuentes oficiales:**
https://docs.suitecrm.com/8.x/admin/licensing/
https://docs.suitecrm.com/es/community/supported-versions/
https://docs.suitecrm.com/es/8.x/admin/compatibility-matrix/
https://docs.suitecrm.com/8.x/admin/installation-guide/downloading-installing/

## CRM propietario: Salesforce

- **Licencia exacta:** Licencia comercial por suscripción, según la edición contratada.
- **Versión vigente:** Salesforce funciona como servicio cloud con actualizaciones continuas, por lo que no tiene una única versión instalable.
- **Lenguaje del servidor:** Para desarrollar lógica en el servidor se utiliza Apex.
- **SGBD compatibles:** No se especifica un SGBD instalable compatible, porque Salesforce es un servicio cloud y el cliente no instala ni administra directamente la base de datos.
- **Modalidad:** Nube (SaaS).

### Módulos principales
- Gestión de clientes potenciales
- Cuentas
- Contactos
- Oportunidades
- Gestión del pipeline de ventas
- Previsiones de ventas
- Informes y dashboards
- Automatización de procesos
- Gestión de actividades
- Marketing y atención al cliente
- IA/Agentforce

### Requisitos principales
- Conexión a Internet.
- Navegador compatible.
- JavaScript y cookies activados.
- TLS 1.2 o 1.3.
- Versiones actuales de Chrome, Firefox, Edge o Safari.

**Fuentes oficiales:**
https://help.salesforce.com/s/articleView?id=platform.code_about.htm&language=es&type=5
https://help.salesforce.com/s/articleView?id=xcloud.getstart_browser_recommendations.htm&type=5

# 4 .Fe de erratas del tema

## Oracle ERP Cloud

**Diapositiva 8**

La frase **"Considerado el mejor según estudios actuales"** es demasiado general porque no indica qué estudio, de qué año ni qué criterios se han utilizado.

Actualmente Oracle ofrece **Oracle Fusion Cloud ERP**, que sigue siendo una plataforma ERP en la nube y recibe actualizaciones continuas.

Por tanto, sería más correcto decir:

> "Oracle Fusion Cloud ERP es una solución ERP en la nube y ha recibido reconocimientos en diferentes estudios de analistas."

**Fuente:**
https://www.oracle.com/es/corporate/analyst-reports/applications/

## Versión de Odoo

**Diapositiva 7**

La presentación indica que la versión de Odoo es la **15**, pero este dato está desactualizado.

Actualmente la versión de referencia es **Odoo 19**, publicada en septiembre de 2025.

**Fuente:**
https://www.odoo.com/es/odoo-19-release-notes

# 5 .Matriz de decisión y recomendación

Para elegir una solución para **Speak Up**, se han comparado **Odoo Community, SuiteCRM y Microsoft Dynamics 365** según 7 criterios.

Los pesos se han elegido teniendo en cuenta que es una academia pequeña y que necesita principalmente centralizar la información de los alumnos.

## Justificación

- **Odoo Community:** obtiene una puntuación alta porque tiene un coste de licencia reducido, muchas funcionalidades y permite centralizar la información de la academia.
- **SuiteCRM:** destaca por la gestión de contactos y seguimiento de alumnos y por tener poca dependencia de un proveedor.
- **Microsoft Dynamics 365:** tiene muchas funcionalidades, buen soporte y capacidad de crecimiento, pero su coste y la dependencia de Microsoft son mayores.

## Resultado

| Solución | Total ponderado |
|---|---:|
| **Odoo Community** | **4,55 / 5** |
| **SuiteCRM** | **4,15 / 5** |
| **Dynamics 365** | **3,45 / 5** |

## Recomendación y riesgos

Se propone **Odoo Community** para Speak Up porque ofrece un buen equilibrio entre coste, funcionalidades y capacidad de adaptación a una academia pequeña.

Los principales riesgos son:

- **Coste total:** instalación, configuración y mantenimiento.
- **Soporte:** puede ser necesario contar con soporte técnico externo.
- **Dependencia:** posible dependencia de la empresa encargada del mantenimiento.
- **Migración futura:** puede ser necesario adaptar los datos si en el futuro se cambia de sistema.

Para reducir estos riesgos se deberían realizar **copias de seguridad** y mantener los datos y la configuración bien documentados.