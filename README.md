# I. Generación del Informe Dinámico (QWeb XML) 
Diseñaremos y programaremos la estructura XML de una plantilla de informe de factura personalizada para "WillmanTech S.L." utilizando la sintaxis de QWeb (motor de plantillas de ERPs modernos).

# II. Interoperabilidad de Datos (Extracción JSON/XML) 
Para permitir que las facturas de "WillmanTech S.L." se incorporen a la plataforma de la Agencia Tributaria o se sincronicen con sistemas contables externos de manera asíncrona, debemos definir las estructuras de intercambio de datos en los siguientes dos ficheros:
<ul>
  <li>**invoice_export.json:** El archivo contendrá un array estructurado con la información de una factura de ejemplo recuperada dinámicamente mediante una consulta al ERP. Deberá contener campos relacionales anidados (ID de cliente, nombre, email, líneas de producto, precios y base imponible). </li>
  <li>**invoice_ubl.xml:** Contrendrá un fragmento de factura electrónica simplificado que cumpla con las especificaciones del estándar internacional UBL (Universal Business Language), incluyendo obligatoriamente los namespaces de componentes agregados (cac) y componentes básicos (cbc), así como el ID de personalización europeo compatible con la red PEPPOL. </li>
</ul>

# III. Manual de Explotación bajo Norma ISO/IEC/IEEE 26514
## 3.1. **Introducción y Arquitectura:** 
La empresa andaluza de servicios tecnológicos "WillmanTech S.L." acaba de finalizar la implantación de su infraestructura ERP/CRM para optimizar sus flujos de ventas y facturación. El sistema está desplegado en un entorno dockerizado y requiere que el equipo de desarrollo (DAM/DAW) realice la puesta en producción de tres elementos críticos de explotación. Las tareas a realizar en este proyecto son:
<ul>
  <li>Personalización del diseño de sus facturas de clientes mediante la manipulación de plantillas basadas en lenguajes de marcas lógicos. </li>
  <li>Habilitación de un pipeline de interoperabilidad y exportación de sus transacciones comerciales hacia sistemas externos utilizando formatos estructurados estandarizados. </li>
  <li>Redacción de un Manual Técnico de Explotación que garantice la sostenibilidad operativa y el correcto traspaso de conocimiento siguiendo la normativa internacional de ingeniería de software. </li>
</ul>

Como desarrolladores programaremos, estructuraremos y documentaremos estas tres soluciones técnicas para asegurar el correcto funcionamiento del sistema informático de la empresa. 

## 3.2. **Guía de Instalación y Reinstalación:** 
Pasos detallados para levantar el entorno desde cero, indicando variables de entorno necesarias y dependencias del SGBD.  

## 3.3. **Seguridad y Control de Acceso:** 
Configuración de roles (administrador, contable, comercial), políticas de contraseñas y privilegios sobre la información.  

## 3.4. **Procedimiento de Backup y Restauración:** 
Detalle del comando para respaldar la base de datos relacional y los almacenes de datos asociados.  

## 3.5. **Flujo Operativo de Facturación e Informes:** 
Explicación paso a paso de cómo un usuario genera una factura en la interfaz y cómo el sistema renderiza el informe final a PDF (explicando de manera didáctica el pipeline HTML \-\> wkhtmltopdf \-\> PDF).

# IV. Uso de IA:

# V. Referencias:
