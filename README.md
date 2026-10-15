# Maison Gourmet · Landing page

Landing de Maison Gourmet (banquetes y eventos en Bogotá), con cotizador conectado a Firebase.

## Estructura
- `prototipos/viaje.html` — experiencia inmersiva en partículas (WebGL / Three.js): fuego → ingredientes → emplatado → la mesa → Bogotá → cotizador con el plato en vivo.
- `public/index.html` — primera versión clásica de la landing (diseño claro, sin 3D).
- `public/firebase-config.js` — configuración pública del proyecto Firebase `maison-gourmet-aebfc`.
- `.firebaserc` — proyecto Firebase por defecto.

## Datos en Firestore
- `solicitudes/{id}` — evento y producción (lo que se envía a proveedores, sin comida ni datos del cliente).
- `solicitudes/{id}/privado/menu` — menú elegido y valores.
- `solicitudes/{id}/privado/cliente` — nombre, WhatsApp, correo y autorización de datos (Ley 1581 de 2012).

## Pendiente
- Unir el viaje en `public/index.html` con preguntas frecuentes, SEO y versión sin animaciones.
- Menú y precios reales (los actuales son de ejemplo), número de WhatsApp y política de datos.
- Reglas de seguridad de Firestore y despliegue en Firebase Hosting.
