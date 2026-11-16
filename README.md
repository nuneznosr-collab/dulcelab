# DulceLab Navidad — sitio estático

## Subir a GitHub
1. Descomprime `DulceLab_Navidad_GitHub.zip` en tu computadora.
2. Abre tu repositorio de GitHub.
3. Pulsa **Add file → Upload files**.
4. Arrastra los archivos y carpetas que están dentro de `DulceLab_Navidad_2026` (no subas el ZIP como único archivo).
5. Pulsa **Commit changes**.

## Configurar Render
Crea un **Static Site** conectado al repositorio:
- Build Command: `echo "Build correcto"` (o déjalo vacío si Render lo permite).
- Publish Directory: `.`
- No necesita Python, `requirements.txt` ni Start Command.

Si ya creaste un Web Service, crea un nuevo Static Site; un Web Service espera un proceso de servidor y no es el tipo correcto para estos archivos estáticos.

## Configurar WhatsApp
Abre `script.js` y localiza al inicio:
```js
const CONFIG={whatsapp:'',currency:'S/'};
```
Coloca el número comercial completo en formato internacional, solo dígitos y sin `+`, espacios ni guiones. Ejemplo de formato: `51XXXXXXXXX`. No inventes ni uses un número hasta confirmar que es el número oficial de DulceLab.

El formulario prepara un mensaje y abre WhatsApp; el cliente debe pulsar Enviar. El sitio no confirma automáticamente el pedido.

## Importante
- Los precios son los precios iniciales de maqueta indicados en el documento del proyecto.
- El delivery queda por coordinar.
- Las imágenes de producto secundarias son visuales referenciales; reemplázalas por fotografías reales de cada kit cuando estén disponibles.
- El logotipo oficial no estaba adjunto en este envío. El encabezado usa un distintivo tipográfico provisional; reemplázalo por el archivo original cuando lo compartas, sin redibujarlo.
- Las recetas exactas, alérgenos, cantidades de producción y conservación no se inventan; deben completarse con las fichas técnicas reales.
