# Portfolio — Dashboards

Colección de dashboards construidos para clientes reales del mundo creativo (música, moda, bienestar). Todas las versiones publicadas acá están **anonimizadas** — nombres, datos y links fueron reemplazados para proteger la privacidad de los clientes.

El objetivo de este portfolio es mostrar el enfoque de producto, la arquitectura de la información, la estética y la resolución técnica detrás de cada proyecto.

## Contexto

Soy Product & Project Manager con background en diseño. Estos dashboards los construí como parte de mi práctica freelance de automatización y desarrollo web, algunos de manera independiente y otros en colaboración con **XIX Consultoría de Artistas**.

Cada proyecto tuvo un objetivo claro: ordenar información compleja, facilitar la toma de decisiones del cliente, y convertir un proceso creativo caótico en un espacio visual navegable.

## Proyectos incluidos

| Proyecto | Tipo | Contexto | Demo |
|----------|------|----------|------|
| [dashboard-lanzamiento-musical](./dashboard-lanzamiento-musical/) | Lanzamiento de álbum | XIX Consultoría | [Ver demo](https://emilsebergamin-cloud.github.io/portfolio-dashboards/dashboard-lanzamiento-musical/) |
| [dashboard-estrategia-artista](./dashboard-estrategia-artista/) | Plan estratégico de artista | XIX Consultoría | [Ver demo](https://emilsebergamin-cloud.github.io/portfolio-dashboards/dashboard-estrategia-artista/) |
| [dashboard-gestion-contenido](./dashboard-gestion-clientes/) | Gestión de contenido (v2) | Freelance | [Ver demo](https://emilsebergamin-cloud.github.io/portfolio-dashboards/dashboard-gestion-clientes/) |

## Stack

La mayoría de los dashboards están construidos como **single-file HTML** con CSS y JS embebidos. Algunos incorporan Firebase para persistencia en tiempo real, otros usan `localStorage` para edición local. La decisión de mantenerlos como archivo único fue deliberada: hace que sean portables, fáciles de deployar, y simples de mantener para clientes no técnicos.

El más reciente ([gestión de contenido v2](./dashboard-gestion-clientes/)) es una reescritura en **React + Vite + Tailwind**, publicada como build estática: muestra el salto de una herramienta de archivo único a una app con arquitectura de componentes.

## Autoría

Construidos por **Emilse Bergamin**.

[LinkedIn](https://www.linkedin.com/in/emilsebergamin) · [Bibl·AI](https://biblai.app)
