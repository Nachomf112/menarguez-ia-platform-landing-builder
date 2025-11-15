# Menárguez-IA Platform — Generador de landings con IA

Plataforma propia para generar páginas de venta con IA (inspirada en Emergent/Bolt), pensada para mi forma de trabajar y para mis clientes.

- Chat → JSON (PageSpec) → renderer propio.
- Flujo de reservas **/book** con envío de correo (Resend).
- Estilos unificados (tema oscuro + acento), precios en EUR y secciones reutilizables.

---

## 🧠 Descripción

Un constructor de páginas con IA: el usuario describe la landing en el chat y la plataforma se encarga del resto:

1. Envía el prompt a OpenAI.
2. Recibe una especificación JSON fuerte (PageSpec) con toda la estructura.
3. Renderiza la página con un renderer propio manteniendo un diseño consistente.

La idea es poder pasar **de idea a landing funcional en minutos**, manteniendo siempre la identidad visual de Menárguez-IA y preparada para conectar con automatizaciones (Make, chatbots, campañas de email, etc.).

---

## ✨ ¿Qué incluye ahora?

- JSON PageSpec + renderer determinista → mismo look & feel en todas las landings.
- Secciones listas para usar: hero, features, pricing (EUR), testimonials, custom.
- Flujo de reservas **/book** con correo transaccional (Resend).
- CTA que sale del iframe con `target="_top"` para integrarse en otras webs.
- Identidad visual Menárguez-IA (tema oscuro + acento).

---

## 🔧 Pila tecnológica

- **Next.js 14** + **TypeScript**.
- **OpenAI API** (generación de PageSpec).
- **Resend** (correo en reservas / book).
- Automatizaciones con **Make** y scripts en **Bash**.

---

## 🧭 Roadmap inmediato

- Mejorar UX de **/book** (validaciones, mensajes y feedback de error).
- Añadir secciones: FAQ, comparativas de planes, timeline de servicio.
- Histórico de versiones (Supabase) + export de la landing a HTML estático.
- Ajuste fino de tipografías/colores alineado con la guía Menárguez-IA.

---

Made with ❤️ by Ignacio Menárguez · Menarguez-IA Solutions.
