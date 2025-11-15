# Guía práctica de ChatGPT con Quarto

Este proyecto es un **libro digital construido con [Quarto](https://quarto.org/)** enfocado en el uso práctico, ético y profesional de ChatGPT como copiloto de inteligencia artificial.

El objetivo es que docentes, estudiantes, investigadores y profesionales de la computación puedan **usar ChatGPT de forma estratégica**, no solo como un buscador, sino como una **extensión de su forma de pensar y trabajar**.

---

## 🎯 Objetivos del libro

- Explicar **qué es ChatGPT** y cómo funciona en lenguaje accesible.
- Enseñar el **arte del prompting**: cómo formular instrucciones claras y efectivas.
- Presentar **casos de uso por rol** (docencia, investigación, desarrollo, productividad).
- Proponer **buenas prácticas éticas**, de privacidad y honestidad académica.
- Ofrecer **plantillas y talleres prácticos** para integrar ChatGPT en el trabajo diario.

---

## 📂 Estructura del proyecto

Este repositorio sigue la estructura típica de un libro Quarto:

- `_quarto.yml`  
  Archivo de configuración principal del libro (título, autor, capítulos, formato, etc.).

- Archivos `.qmd`  
  Cada capítulo se define en un archivo Quarto Markdown, por ejemplo:
  - `prefacio.qmd`
  - `01-introduccion.qmd`
  - `02-que-es-chatgpt.qmd`
  - `03-configuracion-basica.qmd`
  - etc.

- Carpeta `_site/` (generada)  
  Contendrá la versión renderizada del libro (HTML). **No debería versionarse** en Git.

---

## 🛠 Requisitos

Para trabajar con este proyecto necesitas:

- [Quarto](https://quarto.org/docs/get-started/) instalado.
- Git (para control de versiones).
- Opcional:
  - R, Python o VS Code/RStudio si quieres integrar código o usar editores avanzados.

Puedes verificar que Quarto está instalado con:

```bash
quarto --version
