# Dashboard — Gestión de contenido (v2)

Dashboard de gestión de contenido para Instagram, construido para una profesional independiente del área del bienestar. Es el espacio donde planifica su estrategia mensual, organiza stories y carruseles por semana, registra ideas y frases, lleva un calendario de publicaciones y arma su moodboard de marca.

Esta es la **versión 2**: una reescritura completa de la herramienta original (que era un único archivo HTML) en una app moderna de React, manteniendo toda la funcionalidad pero con una arquitectura más sólida y una experiencia más fluida.

## Contexto

Proyecto **freelance**. La versión publicada acá es una demo **anonimizada** — el nombre de la profesional, su marca y todos los contenidos fueron reemplazados por datos ficticios para proteger la privacidad del proyecto original.

## Secciones

- **Inicio** — saludo por hora del día, frase rotativa, métricas rápidas (posts del mes, borradores, stories de la semana, ideas en proceso), próxima publicación y foco semanal.
- **Estrategia** — plan temático del mes, stories organizadas por semana y día, banco de encuestas y carruseles.
- **Contenido** — biblioteca de publicaciones con filtros por categoría, formato y estado.
- **Ideas** — frases, reflexiones, referencias visuales, temas futuros y un pipeline kanban.
- **Calendario** — vista mensual de publicaciones y stories.
- **Moodboard** — paleta de marca y referencias visuales.

## Decisiones de diseño

- **Paleta suave de rosa, verde y beige** y tipografías serif + sans para acompañar el mundo del bienestar.
- **Greeting por hora del día** y frase rotativa: pequeños detalles que humanizan la herramienta.
- **Organización por semanas** (S1–S4): refleja cómo la clienta piensa su contenido mes a mes.
- **Edición optimista**: los cambios se ven al instante.

## Stack

- **React** (Vite) + **React Router** para la navegación entre secciones.
- **Tailwind CSS** para los estilos y **Framer Motion** para las transiciones.
- En el proyecto real: **Firebase Firestore** y **Storage** para persistencia y sync en tiempo real.

## Sobre esta demo

Esta build es estática y **no se conecta a ningún backend**: arranca con datos ficticios y guarda los cambios en el `localStorage` del navegador, así cada visitante tiene su propia copia editable. No expone datos ni credenciales del proyecto real.

El acceso real está protegido con un PIN privado. Para que se pueda explorar, en la demo el PIN es público: **`1234`** (también se muestra en la pantalla de ingreso).

---

Parte del [portfolio de dashboards](../README.md) de [Emilse Bergamin](https://www.linkedin.com/in/emilsebergamin).
