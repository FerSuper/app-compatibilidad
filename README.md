# ConectaIA

Nexo humano con IA. No es un CV literal, no es una red social tradicional y no es un marketplace.

## Arquitectura

- Frontend estático/PWA en este repositorio.
- Supabase para Auth, PostgreSQL y RLS.
- ChatGPT será el cerebro de búsqueda y compatibilidad mediante una integración/API posterior.
- La aplicación no almacena conversaciones de ChatGPT.
- Sin ventas, precios, presupuestos ni chat interno.

## Ejecutar en Codespaces

```bash
npm start
```

Abrir el puerto 3000.

## Backend

Proyecto Supabase: ConectaIA.

La clave incluida en el frontend es una **publishable key** de cliente y la seguridad real se aplica mediante RLS. No se debe incluir ninguna secret/service-role key en este repositorio.
