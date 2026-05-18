# Manual de Explotación bajo Norma ISO/IEC/IEEE 26514
## 1. **Introducción y Arquitectura:** 
La empresa andaluza de servicios tecnológicos "WillmanTech S.L." acaba de finalizar la implantación de su infraestructura ERP/CRM para optimizar sus flujos de ventas y facturación. El sistema está desplegado en un entorno dockerizado y requiere que el equipo de desarrollo (DAM/DAW) realice la puesta en producción de tres elementos críticos de explotación. Las tareas a realizar en este proyecto son:
<ul>
  <li>Personalización del diseño de sus facturas de clientes mediante la manipulación de plantillas basadas en lenguajes de marcas lógicos. </li>
  <li>Habilitación de un pipeline de interoperabilidad y exportación de sus transacciones comerciales hacia sistemas externos utilizando formatos estructurados estandarizados. </li>
  <li>Redacción de un Manual Técnico de Explotación que garantice la sostenibilidad operativa y el correcto traspaso de conocimiento siguiendo la normativa internacional de ingeniería de software. </li>
</ul>

Como desarrolladores programaremos, estructuraremos y documentaremos estas tres soluciones técnicas para asegurar el correcto funcionamiento del sistema informático de la empresa. 

## 2. **Guía de Instalación y Reinstalación:** 
Pasos detallados para levantar el entorno desde cero, indicando variables de entorno necesarias y dependencias del SGBD.  

## 3. **Seguridad y Control de Acceso:** 
Configuración de roles (administrador, contable, comercial), políticas de contraseñas y privilegios sobre la información.  

## 4. **Procedimiento de Backup y Restauración:** 
Detalle del comando para respaldar la base de datos relacional y los almacenes de datos asociados.  

## 5. **Flujo Operativo de Facturación e Informes:** 
Explicación paso a paso de cómo un usuario genera una factura en la interfaz y cómo el sistema renderiza el informe final a PDF (explicando de manera didáctica el pipeline HTML \-\> wkhtmltopdf \-\> PDF).

