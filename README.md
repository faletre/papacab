# PapáCab VIP 🚗

Una PWA satírica de Uber/Cabify para que tu familia te pida trayectos con humor.

## Características

- **PWA completa**: Instalable en iOS y Android con pantalla completa
- **5 pantallas interactivas**: Selección de trayecto, tarifas con humor, búsqueda animada, pago y valoración
- **Tema oscuro premium**: Estética tipo Uber Black
- **Mobile-first**: Diseño optimizado para móviles
- **Integración WhatsApp**: Envía la solicitud directamente a tu teléfono
- **Archivo único HTML autosuficiente**: No requiere Node.js ni instalación de dependencias

## Uso

Simplemente abre `index.html` en tu navegador. No requiere instalación ni servidor.

Para probar la PWA:
1. Abre `index.html` en tu navegador móvil
2. En iOS: Toca "Compartir" → "Añadir a pantalla de inicio"
3. En Android: Toca el menú del navegador → "Instalar app" o "Añadir a pantalla de inicio"

## Configuración del número de WhatsApp

En `index.html`, busca la línea:
```javascript
const whatsappUrl = `https://wa.me/34XXXXXXXXX?text=${encodeURIComponent(whatsappMessage)}`;
```

Reemplaza `34XXXXXXXXX` con tu número de teléfono (incluyendo el código de país).

## Iconos PWA

Los iconos están en `icon-192.png` y `icon-512.png`. Reemplázalos con tus propios iconos para personalizar la app.

## Tecnologías

- HTML5
- Tailwind CSS (vía CDN)
- JavaScript vainilla
- PWA con manifest.json
