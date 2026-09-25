# FUMIGACIÓN CDE
Informe de Planificación, Estructuración Comercial y Tecnológica
Este documento presenta la reestructuración y optimización de los procesos operativos, comerciales y
tecnológicos para el proyecto de Fumigación CDE, detallando el flujo de trabajo desde la captación del
cliente hasta la ejecución del servicio y fidelización.
### 1. Ecosistema Digital y Comercialización (Landing Page)
COMPONENTE DETALLES Y REQUERIMIENTOS
Landing Page 
Página de aterrizaje explicativa. Debe detallar claramente qué es la empresa,
qué servicios ofrece y presentar los Planes Fijos de manera intuitiva.
Pasarela de Pago
Integración directa desde la Landing hacia la pasarela de pagos de Bancard.
En una primera etapa, se implementarán pagos con tarjeta 1x1, con miras a
expandir opciones a futuro.
Clientes Ocasionales
Incorporación de botones de acción rápida para WhatsApp y un botón
destacado en la barra de navegación (nav). El bot se encargará de realizar
seguimiento proactivo (recordatorios).
### 2. Flujo Operativo: Aplicación del Técnico y CRM
PASO ACCIONES Y AUTOMATIZACIONES
1. Solicitud El cliente realiza una solicitud de inspección gratuita.
2. Ingreso al
CRM
La solicitud genera un formulario de inspección en el CRM. El Bot automatizado
escribe inmediatamente al prospecto. Se registra telemetría basándose en el tipo
de hogar.
3. Inspección en
Sitio
El técnico utiliza un Checklist Digital. Es de carácter obligatorio adjuntar 1 foto
por cada punto clave revisado (Total: 8 fotografías obligatorias).
4. Generación
de Informe
La app del técnico genera el informe de inspección. El técnico asocia los planes
recomendados y el sistema vincula esta inspección a la ficha del cliente,
archivando el documento e informando por e-mail.

---

PASO ACCIONES Y AUTOMATIZACIONES
5. Aprobación 
Obligatorio: Ningún trabajo podrá ser iniciado sin la firma digital o física del
responsable. Al finalizar este proceso, se reactiva el seguimiento del bot.
### 3. Módulo Corporativo (Clientes B2B / Empresas)
FUNCIONALIDAD
B2B 
DESCRIPCIÓN DEL PROCESO
Levantamiento 
El técnico realiza y levanta un informe detallado y especializado para la
infraestructura empresarial.
Presupuestación 
Generación de un documento revisado con presupuesto a medida (estado "A
Cotizar").
Envío
Automatizado
Función integrada para enviar el presupuesto corporativo directamente a los
tomadores de decisión de la empresa.
### 4. Estructura de Planes y Suscripciones (Tags)
PLAN / ETIQUETA CARACTERÍSTICAS PRINCIPALES
Aegis (Suscripción
Anual)
Plan único, de máxima categoría. El concepto es "Vender tiempo y facilidad".
Otorga prioridad absoluta, un certificado VIP y cuenta con un enlace directo
de pago de membresía. Nota: Cambiar la etiqueta original a "Suscripción
Anual".
Plan 1 (Escudo) Plan de protección estándar.
Plan 2 (Country) Enfocado a grandes extensiones, condominios o barrios cerrados.
Plan 3 (Business) 
Segmentado para negocios. Permite calendarios programados con
frecuencias: Mensual, Bimestral o Trimestral.
Ocasional Servicios puntuales sin compromiso de recurrencia inmediata.

---

### 5. Inteligencia Artificial, Bots y Agendamiento
El sistema debe mantener un orden estricto, asociando los servicios a cada orden generada y utilizando
un Bot Reagendador Automático bajo las siguientes reglas de negocio:
PARÁMETRO REGLA DE NEGOCIO / CONFIGURACIÓN
Control de Duplicados 
El Bot debe advertir e impedir que se agende un pedido sobre otro en la
misma franja horaria. Sistema de cruce de disponibilidad de horarios.
Tiempos de Servicio 
Cálculo automático: 20 minutos de traslado + 2 horas netas de trabajo
por cada servicio.
Grilla de Horarios
08:00 AM 10:00 AM 12:00 PM 14:00 PM 16:00 PM
* Flexibilidad horaria especial aplicable únicamente para negocios/locales
comerciales.
Seguimiento "Durante
y Después"
Implementación de un sistema de obtención de datos (Fetch) para
seguimiento post-servicio.
### 6. Sistema de Fidelización y Referidos (Alianzas)
ESTRATEGIA IMPLEMENTACIÓN TÉCNICA
Códigos Únicos 
Cada cliente tendrá un código irrepetible. Formato: 2 iniciales (Nombre/
Apellido) + Número aleatorio (Ej: LE3055).
Material Promocional 
Generación automática de imágenes pre-hechas (mediante HTML) que
incluyan el código del referido y un Código QR escaneable.
Automatización de Bots 
El Bot estará capacitado para leer y procesar los códigos de referidos
enviados por los clientes.
Gestión y Alianzas
Creación de la categoría "Socio" en el creador de contactos.
Implementación de un sistema de alianzas con empresas para otorgar
beneficios mutuos. Uso de Pixel para métricas.