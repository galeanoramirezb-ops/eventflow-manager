# EventFlow Manager · SIGEV — Mockup web

Mockup navegable (sin base de datos) del **Sistema Inteligente de Gestión de Eventos y Aforo (SIGEV)**, proyecto formativo del programa Tecnología en Análisis y Desarrollo de Software (ADSO), ficha 3413974, SENA CIES Regional Huila.

## Pantallas incluidas

| Sección | Requerimiento | Qué muestra |
|---|---|---|
| Inicio | — | Presentación del sistema, módulos y blindaje contra ingeniería social |
| Registro | RF1, RF2, RF3 | Formulario con consentimiento Ley 1581 de 2012 |
| Dashboard aforo | RF7, RF9, RF10 | Ocupación en vivo, alertas al 80 % y bloqueo al 100 % |
| Mi ticket QR | RF6 | Ticket con código QR que rota cada 30 segundos |
| Validador | RF8, RF13 | Terminal de puerta con respuesta visual, sonora y háptica |
| Auditoría | RF12 | Bitácora forense con hashes encadenados |
| Equipo | — | Arquitectura de cuatro capas y equipo |
| Contacto | — | Formulario de contacto funcional (FormSubmit), mapa de Google y enlaces directos |

Los datos del sistema son simulados con JavaScript en el navegador; no hay backend ni base de datos. El formulario de **Contacto** sí envía los mensajes al correo del equipo mediante [FormSubmit](https://formsubmit.co).

## Recursos multimedia

- Video de demostración (`video/demo-eventflow.mp4`)
- Galería de capturas en versión escritorio y móvil (`img/`, formato WebP optimizado)
- Mapa de Google con la ubicación del SENA CIES en Neiva
- Enlaces directos al SENA, W3C (WCAG), SIC y OWASP

## URL pública

https://galeanoramirezb-ops.github.io/eventflow-manager/

## Cómo verlo

Abre `index.html` en cualquier navegador, o publícalo con **GitHub Pages**:
*Settings → Pages → Branch: `main` / root → Save*.

## Accesibilidad

- Botón de **alto contraste** para uso en exteriores
- Navegación completa por teclado y enlace “Saltar al contenido”
- Botones táctiles de 48 px o más
- Respeta `prefers-reduced-motion`

## Equipo

- Brenda Carolina Galeano Ramírez — Diseño UI/UX y frontend
- Andrés Felipe Castro Bedoya — QA y backend

SENA · ADSO 3413974 · 2026
