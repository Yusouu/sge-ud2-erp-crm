# Comparativa de ERP y CRM: Libres y Propietarios

## 1. Datos
**Propietario (Usuario GitHub):** Yusouu
**Empresa asignada:** Sonrisas Dental (Clínica dental / sanitaria, 2 sedes, 10 empleados)
**Palabra del día:** Amistad

## 2. Licencias y Modelos

### Software Libre (Free Software Foundation)
El software libre garantiza que los usuarios tienen la libertad de ejecutar,copiar,distribuir,cambiar y mejorar el software basándose en las cuatro libertades esenciales.

### Código Abierto (según la OSI - Open Source Initiative)
Tiene el enfoque centrado en el desarrollo colaborativo y la disponibilidad técnica del código fuente para su inspección y modificación gracias a licencias aprobadas.

### Software Propietario
Software de código cerrado donde el propietario impone restricciones al usuario sobre el uso, modificación, distribución y acceso al código fuente.

### Por qué libre no significa "gratuito"
Aunque la licencia de uso no cueste dinero, implantar software libre en una empresa como Sonrisas Dental genera costes importantes en instalación,adaptación de flujos de trabajo,soporte técnico externo,alojamiento en la nube y formación del personal.

### Edición Community frente a Enterprise
**Community:** Versión libre y gratuita orientada a la comunidad,sin soporte técnico oficial garantizado del fabricante.
**Enterprise:** Versión de pago con soporte directo (SLA),actualizaciones estables y características corporativas bastante avanzadas.

## 3. Fichas Técnicas de Productos

Para realizar esta comparativa orientada a las necesidades de Sonrisas Dental,he seleccionado cuatro herramientas clave en el mercado actual:dos opciones de código libre y dos propietarias (dividienddo entre ERP y CRM).

### 1. ERP Libre: Odoo Community
-**Licencia exacta:** GNU Lesser General Public License v3
-**Versión vigente:** Odoo 18 Community.
-**Lenguaje del servidor:** Python.
-**SGBD compatibles:** PostgreSQL.
-**Modalidad:** Instalación local en un servidor propio o despliegue en nube privada.
-**Módulos principales:** Contabilidad básica, gestión de compras,inventario de material, facturacion y módulos adicionales de agenda medica instalables desde su tienda de apps.
-**Requisitos técnicos:** Servidor con SO Linux como ubuntu server,intérprete de Python 3.10 o superior,base de datos PostgreSQL 14+ y un mínimo de 4 GB de RAM para que vaya fluido.
**Fuente oficial:** [Web oficial de Odoo](https://www.odoo.com/)

### 2. ERP Propietario: Microsoft Dynamics 365
**Licencia exacta:** Software Propietario / Licenciamiento comercial en la nube con suscripción mensual por usuario.
**Versión vigente:** Microsoft Dynamics 365 Business Central.
**Lenguaje del servidor:** (lenguaje propietario de desarrollo sobre infraestructura de Microsoft).
**SGBD compatibles:** Microsoft SQL Server (gestionado de forma nativa y transparente en la nube de Azure).
**Modalidad:** 100% Cloud (SaaS)
**Módulos principales:** Gestión financiera y contable, gestión de ventas, compras, operaciones de almacén y atención al cliente.
**Requisitos técnicos:** No requiere servidores locales en las sedes de la clínica. el acceso se realiza mediante un navegador web actualizado o aplicación oficial conectada a internet.
**Fuente oficial:** [Portal de Microsoft Dynamics 365](https://dynamics.microsoft.com/).

### 3. CRM Libre: SuiteCRM
**Licencia exacta:** GNU Affero General Public License v3 (AGPLv3).
**Versión vigente:** SuiteCRM versión 8.x.
**Lenguaje del servidor:** PHP (versión 8.1 o superior).
**SGBD compatibles:** MySQL, MariaDB y PostgreSQL.
**Modalidad:** Instalación local (On-Premise) o alojamiento en un servidor web propio/VPS.
**Módulos principales:** Gestión de cuentas y pacientes, base de datos de contactos, registro de oportunidades o tratamientos, módulo de incidencias (casos) y campañas de recordatorios.
**Requisitos técnicos:** Servidor web compatible con Apache o Nginx, entorno PHP 8.1+, motor de base de datos MySQL/MariaDB y al menos 2 GB de RAM dedicados.
**Fuente oficial:** [Sitio web de SuiteCRM](https://suitecrm.com/)

### 4. CRM Propietario: Zoho CRM
**Licencia exacta:** Software Propietario / Licencia comercial de pago por suscripción (SaaS).
**Versión vigente:** Zoho CRM (Edición Profesional / Enterprise actual).
**Lenguaje del servidor:** Propietario (desarrollado sobre la infraestructura cloud propia de Zoho).
**SGBD compatibles:** Base de datos relacional gestionada internamente por el proveedor en su nube.
**Modalidad:** Nube (SaaS).
**Módulos principales:** Automatización de procesos de venta y atención, gestión de leads o pacientes potenciales, contactos, analíticas avanzadas y portales interactivos para clientes.
**Requisitos técnicos:** Conexión a internet estable y un navegador web moderno en los equipos de recepción y administración, además de apps oficiales para dispositivos móviles.
**Fuente oficial:** [Página oficial de Zoho CRM](https://www.zoho.com/crm/)

## 4. Fe de erratas del Tema 2

Tras revisar el contenido del pdf del tema 2 y contrastarlo con la información de mercado actual, he localizado los siguientes puntos desactualizados:

**Error 1:** 
*Qué dice el tema:* El documento menciona que Odoo cuenta con su versión actual en la versión 14
*Qué es correcto hoy:* Actualmente, Odoo se encuentra en versiones mucho más avanzadas (como Odoo 18 Community), habiendo evolucionado significativamente en su rendimiento, interfaz y compatibilidad tecnológica desde entonces.
*Fuente:* Documentación oficial y repositorio de GitHub de Odoo.

**Error 2:** 
*Qué dice el tema:* En el apartado de CRM libre se indica que SuiteCRM cuenta con una versión de código abierto 7.14.5 bajo licencia AGPL-3.0
*Qué es correcto hoy:* SuiteCRM ha evolucionado hacia la rama principal de la versión 8.x, modernizando su arquitectura modular basada en servicios web y adaptándose a entornos de desarrollo actuales en PHP 8.1+.
*Fuente:* Repositorio oficial y sitio web de SuiteCRM

## 5. Matriz de Decisión y Recomendación para Sonrisas Dental

### Justificación de criterios y pesos
Para la empresa *Sonrisas Dental* (10 profesionales, 2 sedes desconectadas, registros actuales en papel y sin departamento de informática),he seleccionado los siguientes 5 criterios:

1. **Simplicidad de despliegue sin personal informático (Peso: 25):** 
Al carecer por completo de un departamento de TI interno, la solución elegida no debe requerir la configuración de servidores físicos complejos ni mantenimientos locales avanzados. Se valora positivamente que el despliegue sea desatendido o gestionado externamente.

2. **Presupuesto y costes globales de implantación (Peso: 25):** 
Al tratarse de una clínica PYME con beneficios ajustados, un coste inicial desmedido en licencias o consultoría pondría en riesgo la viabilidad del proyecto de digitalización.

3. **Solución específica para unificar las dos sedes (Peso: 20):** 
Es el problema crítico actual de la clínica. Las dos consultas necesitan estar interconectadas en tiempo real para compartir la agenda de pacientes y evitar atender urgencias a ciegas.

4. **Digitalización de historiales clínicos y agendas (Peso: 20):** 
Es fundamental abandonar el sistema tradicional de cajones y carpetas de papel para transicionar hacia expedientes digitales seguros, rápidos y accesibles desde cualquier punto autorizado.

5. **Curva de aprendizaje para el personal sanitario (Peso: 10):** 
Los dentistas, higienistas y auxiliares necesitan una interfaz muy intuitiva y ágil, de modo que la adaptación al nuevo software no interrumpa la atención diaria a los pacientes.

### Cálculo de totales ponderados y Recomendación final
La solución recomendada para **Sonrisas Dental** es optar por una arquitectura en la nube (SaaS) o un ERP modular que centralice las dos consultas sin necesidad de infraestructura local propia.

**Análisis de riesgos asociados:**
**Coste total (TCO):** Las licencias por usuario o las cuotas mensuales de mantenimiento pueden suponer un esfuerzo financiero considerable para una clínica pequeña.
**Dependencia del proveedor (Vendor Lock-in):** Riesgo de quedar atado a un único proveedor tecnológico si se eligen plataformas en la nube propietarias y cerradas.
**Soporte técnico y mantenimiento:** Al no haber personal técnico en plantilla,cualquier caída de red o fallo en las agendas requiere contratar obligatoriamente un soporte externo.
**Migración futura de datos:** La conversion de todo el archivo físico acumulado en papel hacia el nuevo sistema digital requiere un esfuerzo inicial intensivo de digitalización y depuración de los registros