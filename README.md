# Pastelería Amelia · Bot de pedidos con IA

Bot de pedidos por WhatsApp que toma el pedido en lenguaje natural, consulta
productos y disponibilidad, calcula el presupuesto y espera la aprobación de
Micaela antes de confirmar.

**Stack:** n8n Cloud · Airtable · Claude Sonnet 4.5 · WhatsApp Cloud API · Gmail · Google Calendar

## Entregables
- 📄 Documentación (diagrama, cumplimiento de la consigna y pruebas): `Proyecto_Final_IA_Automation.pdf`
- ⚙️ Flujo principal: `Bot_Pasteleria_Amelia.json`
- ⚙️ Workflow de errores: `Errores-Pastelería Amelia.json`
- 🗄️ Base de datos (solo lectura): https://airtable.com/appDpbouNHfnobXDl/shrcL7nmBGeSD48N2
- 🎬 Video demo: https://drive.google.com/file/d/11Y2y9HyugUaO_6GHGruzUCtyOWS3aQhL/view?usp=sharing 
- 🖼️ Capturas de evidencia: carpeta `capturas/`

## Importar el flujo
Importar los dos JSON en n8n, reasignar las credenciales (WhatsApp, Airtable,
Anthropic, Gmail, Google Calendar) y, en el bot, seleccionar el workflow de
errores en *Settings → Error workflow*.
