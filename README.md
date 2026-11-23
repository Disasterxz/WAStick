<p align="center">
  <img src="assets/icon.png" width="150" alt="Logo de WAStick" />
</p>

<h1 align="center">WAStick</h1>

<p align="center">
  <b>Crea tus propios stickers para WhatsApp desde tu teléfono Android.</b><br/>
  Quita el fondo automáticamente · Stickers individuales o paquetes · Respaldos · Actualizaciones desde GitHub
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-12%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android 12+" />
  <img src="https://img.shields.io/badge/versión-1.1.0-25D366?style=for-the-badge" alt="Versión 1.1.0" />
  <img src="https://img.shields.io/badge/tamaño-~9%20MB-007AFF?style=for-the-badge" alt="Tamaño ~9 MB" />
  <img src="https://img.shields.io/badge/licencia-personal-8E8E93?style=for-the-badge" alt="Uso personal" />
</p>

---

## ✨ ¿Qué es WAStick?

WAStick es una app para **crear stickers para WhatsApp** directamente desde tu celular:

- 🖼️ **Imágenes** (JPG, PNG, WebP) → sticker estático de 512×512 con transparencia.
- 🎞️ **GIF y WebP animados** → sticker animado (hasta 4 s, ≤ 500 KB, como exige WhatsApp).
- 🎬 **Videos cortos** → sticker animado.
- ✂️ **Quitar fondo automáticamente** con IA (segmentación de sujeto de ML Kit).
- 🤍 **Borde blanco** opcional, como los stickers de WhatsApp.
- 📦 **Paquetes** de 3 a 30 stickers, o un **sticker individual**.
- 📤 **Enviar a WhatsApp** (y WhatsApp Business) con un toque.
- 💾 **Respaldos** completos en `.zip` para exportar o restaurar tus paquetes.
- 🔄 **Se actualiza solo**: al abrir la app revisa si hay una versión nueva en este repositorio.

> WAStick **no** modifica WhatsApp ni accede a tus chats. Solo entrega a WhatsApp los paquetes que tú creas.

---

## 🎨 Diseño

Interfaz **glassmorphism** inspirada en iOS: fondos con manchas de color desenfocadas, tarjetas translúcidas con brillo en el borde y colores de WhatsApp (verde `#25D366`) con acentos azul iOS (`#5AC8FA`) y rosa (`#FF2D92`). Sigue el **modo claro / oscuro** de tu sistema.

---

## 🚀 Instalación

1. Ve a **[Releases](../../releases)** y descarga `app-release.apk` de la versión más reciente.
2. Ábrelo en tu Android. Si tu sistema lo pide, permite **instalar apps de origen desconocido** para tu navegador o gestor de archivos.
3. Acepta la instalación. La app se abre sola al terminar.

**Requisitos:** Android 12 o superior. Para quitar fondos automáticamente se usan los servicios de Google Play (ya vienen en casi todos los teléfonos).

---

## 📖 Cómo se usa

| Paso | Qué haces |
|---|---|
| 1 | Toca **Nuevo** y elige **Paquete de stickers** o **Sticker individual**. |
| 2 | Toca **Agregar stickers** y elige imágenes, GIF, WebP animado o videos de tu almacenamiento. |
| 3 | Toca un sticker para cambiar su **emoji** o eliminarlo. |
| 4 | Toca **Volver a enviar a WhatsApp**: te pide el **nombre del paquete** y el **publicador**, y luego abre WhatsApp para añadirlo. |

Para respaldar: **Ajustes → Exportar respaldo**. Para restaurar: **Ajustes → Importar respaldo** (reemplaza los paquetes actuales).

---

## ⚙️ Personalización

Dentro de la app puedes ajustar:

- **Publicador por defecto** (se usa al crear nuevos paquetes).
- **Quitar fondo automáticamente** — activado o desactivado por defecto.
- **Borde blanco por defecto** — activado o desactivado por defecto.
- **Emoji por sticker** — WhatsApp lo usa para buscar tus stickers.

---

## 🧩 Límites de WhatsApp que respeta WAStick

| Regla | Valor |
|---|---|
| Tamaño del sticker | 512 × 512 px |
| Sticker estático | ≤ 100 KB (WebP) |
| Sticker animado | ≤ 500 KB, ≤ 10 s |
| Icono de bandeja | 96 × 96 px, ≤ 50 KB |
| Stickers por paquete | 3 a 30 |
| Mezclar estáticos y animados | No permitido |

---

## 🔄 Actualizaciones

WAStick consulta la **última release** de este repositorio al abrirse. Si hay una versión más nueva, te ofrece descargarla e instalarla. Cada versión publicada aquí incluye su APK firmado. La firma es la misma en todas las versiones, así que se instalan **encima** sin perder tus paquetes.

---

## 🗺️ Historial de versiones

| Versión | Novedades |
|---|---|
| **1.1.0** | Icono y logo nuevos · GIF/WebP/video animados · Nombre y autor solo al enviar a WhatsApp · "Volver a enviar a WhatsApp" · Actualizaciones desde GitHub |
| 1.0.0 | Primera versión: paquetes, stickers estáticos, quitar fondo, respaldos, envío a WhatsApp |

---

## 🔒 Privacidad

- Tus imágenes se procesan **en tu teléfono**. No se suben a ningún servidor de WAStick.
- La app solo se conecta a internet para revisar actualizaciones en GitHub y para descargar los modelos de Google Play services que usa el quitado de fondo.

---

<p align="center">
  <sub>Hecho para que tus stickers se vean bien en WhatsApp · WAStick 1.1.0</sub>
</p>
