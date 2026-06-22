# Webstarted Screen Capture — Builds

Instaladores distribuibles de **Webstarted Screen Capture**.

El código fuente es privado; este repositorio **solo aloja los binarios** publicados
como [Releases](../../releases). No contiene código.

## Descargar la última versión

| Plataforma | Descarga |
| --- | --- |
| **macOS** (Apple Silicon) | [WebstartedScreenCapture-macos.dmg](https://github.com/webstarted/webstarted-screen-capture-builds/releases/latest/download/WebstartedScreenCapture-macos.dmg) |
| **Windows** (x64) | [WebstartedScreenCapture-windows.msi](https://github.com/webstarted/webstarted-screen-capture-builds/releases/latest/download/WebstartedScreenCapture-windows.msi) |

Estos links **siempre apuntan al último release publicado** (`/releases/latest`) —
no cambian entre versiones. Son los que usa el sitio web.

## Versiones

Cada release está tagueado `vX.Y.Z` (ver [Releases](../../releases)). Un release
recién se **publica** (deja de ser draft y pasa a ser `latest`) cuando ya tiene
**el DMG y el MSI**. Hasta entonces queda en draft y `latest` sigue apuntando a la
versión anterior.

## Notas de instalación

- **macOS** — el DMG está **firmado y notarizado** (Developer ID): se abre y se
  arrastra a Aplicaciones sin advertencias de Gatekeeper.
- **Windows** — el MSI **todavía no está firmado**: SmartScreen puede mostrar
  "Windows protegió tu PC" → *Más información* → *Ejecutar de todas formas*.
