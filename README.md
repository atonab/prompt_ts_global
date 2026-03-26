<div align="center">

# 🌍 Prompt TS - Base de Datos Global

*El repositorio central de la comunidad para almacenar y compartir los mejores prompts de Inteligencia Artificial.*

</div>

---

## 👋 ¡Bienvenido a la Comunidad!

Este repositorio actúa como la **Base de Datos Global** para el ecosistema *Prompt TS*. Si estás utilizando tu propia instancia de la Wiki y has creado un prompt excepcional que crees que puede ayudar a otros (ya sea para desarrollo web, copys de marketing, o generación de imágenes), ¡este es el lugar para compartirlo!

Todos los prompts aprobados aquí se sincronizarán automáticamente en la carpeta `comunidad/` de todas las Wikis conectadas alrededor del mundo.

---

## 🛠️ ¿Cómo contribuir?

Para mantener la calidad y el orden del sistema, utilizamos el flujo estándar de GitHub (Fork & Pull Request). Sigue estos pasos:

1. **Haz un Fork** de este repositorio (`prompt_ts_global`).
2. **Crea tu archivo `.md`** siguiendo estrictamente la plantilla oficial (ver abajo).
3. **Guarda tu archivo** dentro de la carpeta categórica que mejor corresponda (ej. `imagenes/`, `marketing/`, `desarrollo/`). Si tu categoría no existe, puedes proponer crearla.
4. **Haz un Commit** con un mensaje descriptivo (ej. `feat: añade prompt para mockups estilo cyberpunk`).
5. **Abre un Pull Request (PR)** hacia la rama `main` de este repositorio original.

---

## 📝 Reglas de Formato (Plantilla Obligatoria)

Para que el buscador, las etiquetas y el motor de la Wiki funcionen correctamente, **todos los aportes deben seguir exactamente esta estructura**. Copia este bloque base para crear tu archivo:

```markdown
---
tags:
  - etiqueta1
  - etiqueta2
---
# [Nombre Corto y Descriptivo]

**Descripción:**
- *[Explica qué problema resuelve este prompt en una o dos líneas]*
---
**Modelo Recomendado:**
- [Ej. Claude 3.5 Sonnet, GPT-4o, Midjourney v6, Gemini]
---

## 📋 Variables a preparar
- `[VARIABLE_1]`: [Explicación de qué dato reemplazar aquí]

---

## 🚀 Prompt

` ` `text
Actúa como un [ROL]. Necesito que me ayudes a [OBJETIVO].

Contexto:
[VARIABLE_1]
` ` `