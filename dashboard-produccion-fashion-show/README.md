# Dashboard — Producción de desfile (fashion show)

Dashboard de producción para organizar un desfile de moda en Nueva York, construido para una marca de upcycling de alta costura. Es la herramienta donde el equipo creativo coordina cada detalle del show — desde la colección y el moodboard hasta el presupuesto, el cronograma y el soundtrack — accesible desde cualquier dispositivo.

## Contexto

Proyecto **freelance**. La versión publicada acá es una demo **anonimizada** — el nombre de la marca, los datos del equipo, los contactos y todos los contenidos fueron reemplazados por datos ficticios para proteger la privacidad del proyecto original.

## Secciones (10)

- **Inicio** — saludo, cuenta regresiva al show y resumen de tareas.
- **Info general** — nombre, fecha, venue, horario, cantidad de looks y duración.
- **Moodboard / Referencias** — tableros visuales con imágenes, tags y notas de inspiración.
- **Colección** — grilla de prendas con foto, categoría, notas y estado "listo".
- **Looks** — armado de looks en proceso / terminados, reordenables.
- **Timeline** — cronograma de producción.
- **Equipo** — contactos de producción (rol, teléfono, email, IG).
- **Links útiles** — repositorio de links por tipo.
- **Música** — soundtrack del show con links a plataformas.
- **Presupuesto** — gastos por categoría con subtotales y total general.
- **Proceso creativo** y **Notas** — texto libre y anotaciones rápidas.

Incluye **toggle ES/EN**, exportación a imagen/PDF por sección y export/import de un backup JSON.

## Decisiones de diseño

- **Mobile-first**: el equipo lo usa desde el teléfono en pleno backstage.
- **Roles**: en producción, distingue entre "owner" (acceso total) y "colaborador" (vista acotada).
- **Identidad cálida** (cremas, terracota, naranja) acorde a la marca.

## Stack

- **Single-file HTML5 + CSS + JavaScript vanilla** (sin framework ni build).
- En el proyecto real: **Firebase Firestore + Storage** para sync en tiempo real y **autenticación** (Google / email).

## Sobre esta demo

Esta versión **no se conecta a ningún backend**: se le quitó Firebase y las credenciales. Arranca con datos ficticios y guarda los cambios en el `localStorage` del navegador, así cada visitante tiene su propia copia editable.

Se mantiene la **pantalla de login** (es parte del producto), pero en la demo cualquier acción —"Continuar con Google" o cualquier email/contraseña— entra directo al dashboard con los datos de ejemplo.

---

Parte del [portfolio de dashboards](../README.md) de [Emilse Bergamin](https://www.linkedin.com/in/emilsebergamin).
