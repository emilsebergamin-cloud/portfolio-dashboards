# Dashboard — Lanzamiento Musical

Dashboard construido para acompañar el lanzamiento de un álbum de una artista. Pensado como espacio de trabajo entre el management, la artista y los colaboradores (productores, visuales, prensa).

## Contexto

Proyecto realizado para **XIX Consultoría de Artistas**. La versión publicada acá es una demo **anonimizada** — la artista real, los títulos del álbum, las fechas y los links fueron reemplazados para proteger la privacidad del proyecto original.

## Problema que resolvía

Durante un lanzamiento de álbum, la información queda dispersa: drafts de canciones en Drive, ideas visuales en chats, cronogramas en spreadsheets sueltos, referencias en tableros privados. El management y la artista pierden tiempo buscando cosas.

El dashboard consolida todo en una vista única: álbum, visuales, cronograma, referencias, links de plataformas — todo en un solo lugar, editable, deployable y compartible con un link.

## Decisiones de diseño

- **Paleta cálida vintage**: para evocar el mood del álbum.
- **Tabs tipo folder**: estructura familiar para un manager creativo no técnico.
- **Campos editables con localStorage**: el cliente puede actualizar links directamente desde el dashboard sin tocar código.
- **Sin login ni backend**: priorizamos simplicidad de deploy sobre complejidad técnica.

## Stack

- HTML + CSS + JavaScript vanilla, un solo archivo.
- `localStorage` para persistencia local de links editables.

## Cómo verlo

Abrir `index.html` en cualquier navegador.

---

Parte del [portfolio de dashboards](../README.md) de [Emilse Bergamin](https://www.linkedin.com/in/emilsebergamin).
