# Dashboard — Gestión de Clientes

Dashboard construido para una profesional independiente del área de bienestar que trabaja con clientes de forma individual. Pensado como espacio de gestión del día a día: agenda, clientes activos, seguimiento de sesiones, moodboard y notas.

## Contexto

Proyecto **freelance**. La versión publicada acá es una demo **anonimizada** — el nombre de la profesional, los datos de sus clientes, los registros de sesiones y los contactos fueron reemplazados por datos ficticios para proteger la privacidad del proyecto original.

## Problema que resolvía

Profesionales independientes (coaches, terapeutas, consultoras) suelen gestionar su práctica entre agendas de papel, chats, Google Calendar y planillas sueltas. La información fragmentada hace que pierdan contexto entre sesiones, olviden detalles del cliente, o no vean patrones en su propia práctica.

El dashboard consolida agenda, fichas de clientes, historial de sesiones y espacio creativo (moodboard con quotes rotativos) en un solo lugar. La idea: que abrir el dashboard a la mañana sea suficiente para saber cómo va el día.

## Decisiones de diseño

- **Paleta suave con rosa, verde y beige**: acompaña el mundo del bienestar sin caer en cliché.
- **Moodboard con quotes rotativos**: aporta un momento de pausa cuando la profesional abre el dashboard.
- **Greeting por hora del día**: pequeño detalle que humaniza la herramienta.
- **Kanban para gestión de clientes**: visualización más intuitiva que una lista para ver el estado de cada relación.
- **Firebase Firestore para persistencia**: permite actualizar información desde múltiples dispositivos sincronizada.

## Stack

- HTML + CSS + JavaScript vanilla, un solo archivo.
- Firebase Firestore para persistencia en tiempo real.
- html2pdf.js para exportar fichas a PDF.

## Cómo verlo

Abrir `index.html` en cualquier navegador. Esta versión demo usa datos ficticios embebidos.

---

Parte del [portfolio de dashboards](../README.md) de [Emilse Bergamin](https://www.linkedin.com/in/emilsebergamin).
