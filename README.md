# Menárguez-IA Platform — Resumen

Constructor de landings con IA (estilo emergent/bolt):

- Chat → JSON (PageSpec) → renderer propio.
- Flujo de reservas **/book** con correo (Resend).
- Estilos unificados (oscuro + acento), precios en EUR y secciones reutilizables.

## 🧠 Descripción

Un constructor de páginas con IA: el usuario describe la página en el chat y la plataforma:

1. Envía el prompt a OpenAI.
2. Recibe una especificación JSON fuerte (PageSpec).
3. Renderiza la página con un renderer propio manteniendo diseño consistente.

## ✨ ¿Qué incluye ahora?

- JSON PageSpec + renderer determinista → mismo look & feel.
- Secciones: hero, features, pricing (EUR), testimonials, custom.
- Flujo de reservas **/book** (correo con Resend).
- CTA que sale del iframe con `target="_top"`.
- Identidad visual Menárguez-IA (tema oscuro + acento).

## 🔧 Pila

- Next.js 14 + TypeScript.
- OpenAI API (PageSpec).
- Resend (correo en reservas).
- Automatizaciones: Make / Bash.

## 🗺️ Roadmap inmediato

- UX de **/book** (validaciones, mensajes).
- Secciones FAQ, comparativas, timeline.
- Histórico de versiones (Supabase) + export HTML.
- Ajuste fino de tipografías/colores a guía Menárguez-IA.

---

Made with ❤️ by Ignacio Menárguez · Menarguez-IA Solutions.
