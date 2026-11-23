<p align="center">
  <img src="assets/icon.png" width="150" alt="Logo de WAStick" />
</p>

<h1 align="center">WAStick</h1>

<p align="center">
  <b>Crea tus propios stickers para WhatsApp desde tu telÃ©fono Android.</b><br/>
  Quita el fondo automÃ¡ticamente Â· Stickers individuales o paquetes Â· Respaldos Â· Actualizaciones desde GitHub
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-12%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android 12+" />
  <img src="https://img.shields.io/badge/versiÃ³n-1.1.0-25D366?style=for-the-badge" alt="VersiÃ³n 1.1.0" />
  <img src="https://img.shields.io/badge/tamaÃ±o-~9%20MB-007AFF?style=for-the-badge" alt="TamaÃ±o ~9 MB" />
  <img src="https://img.shields.io/badge/licencia-personal-8E8E93?style=for-the-badge" alt="Uso personal" />
</p>

---

## âœ¨ Â¿QuÃ© es WAStick?

WAStick es una app para **crear stickers para WhatsApp** directamente desde tu celular:

- ðŸ–¼ï¸ **ImÃ¡genes** (JPG, PNG, WebP) â†’ sticker estÃ¡tico de 512Ã—512 con transparencia.
- ðŸŽžï¸ **GIF y WebP animados** â†’ sticker animado (hasta 4 s, â‰¤ 500 KB, como exige WhatsApp).
- ðŸŽ¬ **Videos cortos** â†’ sticker animado.
- âœ‚ï¸ **Quitar fondo automÃ¡ticamente** con IA (segmentaciÃ³n de sujeto de ML Kit).
- ðŸ¤ **Borde blanco** opcional, como los stickers de WhatsApp.
- ðŸ“¦ **Paquetes** de 3 a 30 stickers, o un **sticker individual**.
- ðŸ“¤ **Enviar a WhatsApp** (y WhatsApp Business) con un toque.
- ðŸ’¾ **Respaldos** completos en `.zip` para exportar o restaurar tus paquetes.
- ðŸ”„ **Se actualiza solo**: al abrir la app revisa si hay una versiÃ³n nueva en este repositorio.

> WAStick **no** modifica WhatsApp ni accede a tus chats. Solo entrega a WhatsApp los paquetes que tÃº creas.

---

## ðŸŽ¨ DiseÃ±o

Interfaz **glassmorphism** inspirada en iOS: fondos con manchas de color desenfocadas, tarjetas translÃºcidas con brillo en el borde y colores de WhatsApp (verde `#25D366`) con acentos azul iOS (`#5AC8FA`) y rosa (`#FF2D92`). Sigue el **modo claro / oscuro** de tu sistema.

---

## ðŸš€ InstalaciÃ³n

1. Ve a **[Releases](../../releases)** y descarga `app-release.apk` de la versiÃ³n mÃ¡s reciente.
2. Ãbrelo en tu Android. Si tu sistema lo pide, permite **instalar apps de origen desconocido** para tu navegador o gestor de archivos.
3. Acepta la instalaciÃ³n. La app se abre sola al terminar.

**Requisitos:** Android 12 o superior. Para quitar fondos automÃ¡ticamente se usan los servicios de Google Play (ya vienen en casi todos los telÃ©fonos).

---

## ðŸ“– CÃ³mo se usa

| Paso | QuÃ© haces |
|---|---|
| 1 | Toca **Nuevo** y elige **Paquete de stickers** o **Sticker individual**. |
| 2 | Toca **Agregar stickers** y elige imÃ¡genes, GIF, WebP animado o videos de tu almacenamiento. |
| 3 | Toca un sticker para cambiar su **emoji** o eliminarlo. |
| 4 | Toca **Volver a enviar a WhatsApp**: te pide el **nombre del paquete** y el **publicador**, y luego abre WhatsApp para aÃ±adirlo. |

Para respaldar: **Ajustes â†’ Exportar respaldo**. Para restaurar: **Ajustes â†’ Importar respaldo** (reemplaza los paquetes actuales).

---

## âš™ï¸ PersonalizaciÃ³n

Dentro de la app puedes ajustar:

- **Publicador por defecto** (se usa al crear nuevos paquetes).
- **Quitar fondo automÃ¡ticamente** â€” activado o desactivado por defecto.
- **Borde blanco por defecto** â€” activado o desactivado por defecto.
- **Emoji por sticker** â€” WhatsApp lo usa para buscar tus stickers.

---

## ðŸ§© LÃ­mites de WhatsApp que respeta WAStick

| Regla | Valor |
|---|---|
| TamaÃ±o del sticker | 512 Ã— 512 px |
| Sticker estÃ¡tico | â‰¤ 100 KB (WebP) |
| Sticker animado | â‰¤ 500 KB, â‰¤ 10 s |
| Icono de bandeja | 96 Ã— 96 px, â‰¤ 50 KB |
| Stickers por paquete | 3 a 30 |
| Mezclar estÃ¡ticos y animados | No permitido |

---

## ðŸ”„ Actualizaciones

WAStick consulta la **Ãºltima release** de este repositorio al abrirse. Si hay una versiÃ³n mÃ¡s nueva, te ofrece descargarla e instalarla. Cada versiÃ³n publicada aquÃ­ incluye su APK firmado. La firma es la misma en todas las versiones, asÃ­ que se instalan **encima** sin perder tus paquetes.

---

## ðŸ—ºï¸ Historial de versiones

| VersiÃ³n | Novedades |
|---|---|
| **1.1.4** | Medios estáticos y animados en el mismo paquete · Se quitó la opción de sticker individual |
| 1.1.3 | Corrección del cierre al cargar GIF/WebP/video animados (nuevo codificador sin código nativo, APK más ligero) |
| 1.1.2 | Actualización con barra de progreso y aviso de versión al día · Corrección de crash con GIF/WebP animados · Reenvío a WhatsApp con aviso de paquete ya cargado |
| 1.1.1 | Ajustes rediseñados · Buscar actualizaciones desde la app · Creador visible |
| 1.1.0 | Icono y logo nuevos Â· GIF/WebP/video animados Â· Nombre y autor solo al enviar a WhatsApp Â· "Volver a enviar a WhatsApp" Â· Actualizaciones desde GitHub |
| 1.0.0 | Primera versiÃ³n: paquetes, stickers estÃ¡ticos, quitar fondo, respaldos, envÃ­o a WhatsApp |

---

## ðŸ”’ Privacidad

- Tus imÃ¡genes se procesan **en tu telÃ©fono**. No se suben a ningÃºn servidor de WAStick.
- La app solo se conecta a internet para revisar actualizaciones en GitHub y para descargar los modelos de Google Play services que usa el quitado de fondo.

---

<p align="center">
  <sub>Hecho para que tus stickers se vean bien en WhatsApp Â· WAStick 1.1.4</sub>
</p>




