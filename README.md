# Lavadero Booking MVP

Aplicación web para reserva de turnos de un lavadero de autos.

## Objetivo
Permitir que un cliente vea servicios, precios y horarios disponibles, y pueda reservar un turno desde una web responsive.  
El administrador puede visualizar y gestionar las reservas desde el celular.

## Stack
- React + Vite
- Tailwind CSS
- Supabase
- Netlify

## Funcionalidades fase 1
- Visualización de servicios y precios
- Reserva de turnos
- Confirmación de reserva
- Panel administrador básico
- Link a WhatsApp con mensaje prearmado

## Estructura
- `src/`: frontend
- `supabase/`: esquema SQL y seeds
- `netlify.toml`: configuración de deploy

## Variables de entorno
Crear un archivo `.env.local` con:

```env
VITE_SUPABASE_URL=tu_url
VITE_SUPABASE_PUBLISHABLE_KEY=tu_publishable_key

## Scripts
```bash
npm install
npm run dev
npm run build