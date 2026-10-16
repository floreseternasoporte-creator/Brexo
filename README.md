# Brexo — Mensajería

App de mensajería separada de **Drex**: entra con tu misma cuenta de Drex y
sigue tus chats, grupos e historial. Misma base de datos, mismo login.

- **Login**: el mismo de Drex (Amazon Cognito, pool `drex-users`).
- **Datos**: la misma tabla DynamoDB `drex-kv` — tus mensajes e historial
  están ahí, sin migrar nada.
- **Funciones**: bandeja de chats, mensajes directos, grupos, fotos, archivos,
  GIFs, notas de voz, respuestas, reenvío, fijados, mensajes temporales,
  temas de chat, confirmaciones de lectura, presencia.

Despliegue: GitHub Pages (rama `main`).
