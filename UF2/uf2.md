# Ejercicios UF2

## EC2.1 ¿IT u OT?

| Nº | Sistema | IT | OT | Mix |
|---|---|:---:|:---:|:---:|
| 1 | Servidor de correo corporativo (Microsoft 365) | X | | |
| 2 | SCADA de una planta química que controla válvulas y sensores | | X | |
| 3 | ERP en la nube que gestiona pedidos y facturación | X | | |
| 4 | PLC que gobierna una cadena de montaje | | X | |
| 5 | Plataforma de tickets de soporte (Jira, Zendesk) | X | | |
| 6 | Sistema MES que conecta el PLC con el ERP | | | X |
| 7 | Software de copias de seguridad de los servidores | X | | |
| 8 | Sistema de control de accesos de un edificio (tarjetas) | | X | |

## EC2.2 Departamentos IT de una empresa

**Empresa de referencia:** empresa de servicios informáticos (ejemplo).

| Área / Departamento | ¿Qué gestiona? | ¿Por qué es entorno IT? |
|---|---|---|
| Soporte técnico | Incidencias de ordenadores y programas. | Trabaja con equipos y sistemas informáticos. |
| Desarrollo de software | Creación y mantenimiento de aplicaciones. | Desarrolla programas que procesan información. |
| Sistemas y redes | Servidores, redes y conexiones. | Mantiene la infraestructura informática de la empresa. |

## EC2.3 Tecnología de negocio vs. de planta

| Tecnología | Negocio | Planta |
|---|:---:|:---:|
| ERP (SAP, Oracle, etc.) | X | |
| SCADA / HMI | | X |
| CRM (Salesforce, HubSpot) | X | |
| MES (Manufacturing Execution System) | | X |
| E-commerce (PrestaShop, Shopify) | X | |
| PLC / PAC | | X |
| BI / Data Warehouse | X | |
| Robots colaborativos (cobots) | | X |

## EC2.4 Qué hace que IT y OT se parezcan y se diferencien

| Aspecto | IT | OT |
|---|---|---|
| Coincidencia 1 | Utiliza tecnología informática. | También utiliza tecnología informática. |
| Coincidencia 2 | Necesita medidas de seguridad. | También necesita medidas de seguridad. |
| Coincidencia 3 | Ayuda a mejorar el funcionamiento de la empresa. | También ayuda a mejorar el funcionamiento de la empresa. |
| Diferencia 1 | Gestiona datos e información. | Controla máquinas y procesos físicos. |
| Diferencia 2 | Se usa sobre todo en oficinas y gestión empresarial. | Se usa sobre todo en fábricas e instalaciones. |
| Diferencia 3 | Da mucha importancia a la confidencialidad de los datos. | Da mucha importancia a la seguridad física y a no detener los procesos. |

## EC2.5 Convergencia IT-OT de una consultora IT

### 1. ¿Cuál es el entorno IT de BIT Consultores? ¿Y el entorno OT del cliente?

El entorno IT incluye los ordenadores, las redes y la plataforma en la nube que usan los técnicos de BIT. El entorno OT incluye las máquinas, la línea de producción y los sistemas físicos que se supervisan en las instalaciones del cliente.

### 2. ¿Qué sistema hace de puente entre los dos entornos?

Los sensores IoT conectados a la plataforma en la nube permiten recoger datos del entorno OT y mostrarlos en el entorno IT.

### 3. ¿Qué tecnología permite ver el estado de la línea de producción a 500 km?

El Internet de las Cosas (IoT), junto con la conexión a Internet y la plataforma en la nube, permite consultar los datos a distancia y en tiempo real.

### 4. ¿Qué ventajas tiene para el cliente industrial?

Puede detectar problemas antes de que haya averías, reducir paradas de producción y ahorrar tiempo y dinero en desplazamientos y mantenimiento.

### 5. ¿Qué riesgo nuevo introduce esta conexión?

Aumenta el riesgo de ciberataques: alguien podría intentar acceder a los sistemas industriales mediante la conexión remota.

## EC2.6 Ventajas de una digitalización de extremo a extremo

| Ámbito | Ventaja | Justificación (1-2 frases) |
|---|---|---|
| Producción | Mejor control de la actividad | La integración con el MES permite conocer datos de producción y relacionarlos con el inventario. |
| Inventario | Menos errores de stock | El SaaS permite actualizar y consultar las existencias sin depender de anotaciones manuales. |
| Mantenimiento y soporte | Detección rápida de incidencias | El NOC supervisa los sistemas las 24 horas y puede avisar cuando aparece un problema. |
| Clientes | Acceso más cómodo al servicio | Al ser un SaaS, las pymes pueden utilizar la aplicación por Internet y consultar su inventario. |
| Empresa | Servicio más completo | DeltaCode pasa de vender horas de programación a ofrecer una solución integrada con soporte continuo. |

## EC2.7 Riesgos de conectar OT a Internet

**Caso:** una planta de packaging conecta directamente su SCADA a Internet para permitir mantenimiento remoto.

| Riesgo | Medida de mitigación |
|---|---|
| Acceso no autorizado al SCADA | Evitar exponerlo directamente a Internet; usar acceso remoto seguro mediante VPN y autenticación multifactor. |
| Ataques que paren la producción | Separar la red industrial de la red de oficina y limitar las conexiones permitidas. |
| Cambios maliciosos en parámetros de las máquinas | Dar permisos mínimos a cada usuario y registrar los cambios realizados. |
| Fallos o vulnerabilidades del software | Mantener los sistemas actualizados con pruebas y ventanas de mantenimiento planificadas. |
| Pérdida de datos o configuraciones por un incidente | Hacer copias de seguridad y comprobar que se pueden restaurar. |
