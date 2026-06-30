---
title: 'Guía rápida: Cómo integrar Tailwind CSS en Astro'
pubDate: 2026-07-05
description: 'Aprende a estilizar tu sitio web de Astro utilizando Tailwind CSS en menos de cinco minutos.'
author: 'Tu Nombre'
image:
    url: 'https://astro.build'
    alt: 'Diseño de interfaz'
tags: ["astro", "tailwind", "css"]
---

# Estiliza tu blog con Tailwind CSS

Astro hace que integrar herramientas de estilos sea ridículamente sencillo gracias a sus comandos automatizados. En esta guía te enseño cómo añadir Tailwind CSS a tu proyecto.

## Paso 1: Instalación automática

Abre tu terminal en la raíz del proyecto y ejecuta el siguiente comando:

```bash
npx astro add tailwind
```

El asistente de Astro hará todo el trabajo pesado por ti:
1. Instalará las dependencias necesarias.
2. Creará el archivo `tailwind.config.mjs`.
3. Actualizará tu archivo `astro.config.mjs` para registrar la integración.

## Paso 2: Empieza a usar las clases

¡Ya está listo! Ahora puedes usar las clases utilitarias directamente en tus archivos `.astro` o en tus componentes de Markdown:

```astro
---
// src/pages/index.astro
---
<main class="max-w-4xl mx-auto px-4 py-8">
  <h1 class="text-4xl font-bold text-indigo-600">¡Hola Tailwind!</h1>
  <p class="mt-2 text-gray-600">Mis estilos ahora son ultra rápidos de escribir.</p>
</main>
```

## Conclusión

La combinación de Astro y Tailwind CSS es una de las mejores experiencias de desarrollo actuales. Obtienes un sitio veloz con un flujo de diseño sumamente ágil.
