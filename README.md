# 🎼 SibeliusGUB

> Conversor de partituras **MusicXML → PDF** para coros (SATB), 100% en el navegador.

Herramienta web ligera que toma un archivo `.musicxml` o `.xml`, lo renderiza como partitura coral usando [OpenSheetMusicDisplay](https://opensheetmusicdisplay.org/) y permite descargar el resultado como un PDF multipágina. Todo el procesamiento ocurre **en el cliente** — ningún archivo se sube a un servidor.

![Privacidad primera](https://img.shields.io/badge/procesamiento-100%25%20cliente-blue)
![Sin servidor](https://img.shields.io/badge/backend-no%20requerido-green)

## ✨ Características

- **Drag & Drop** — Arrastra tu archivo MusicXML o selecciónalo con un clic.
- **Renderizado en el navegador** — OpenSheetMusicDisplay dibuja la partitura con formato compacto coral.
- **Exportación a PDF** — Genera un PDF multipágina (una página por sistema de canvas) con jsPDF.
- **Privacidad total** — Los archivos nunca salen del dispositivo del usuario.
- **Tema oscuro** — Interfaz moderna con glassmorphism.

## 🚀 Uso

```bash
# 1. Instalar dependencias
npm install

# 2. Iniciar servidor de desarrollo
npm run dev

# 3. Build de producción
npm run build
```

Abre el navegador, arrastra un archivo `.musicxml` y haz clic en **Descargar PDF**.

## 🛠️ Stack técnico

| Herramienta | Rol |
|---|---|
| **Vite** | Bundler y servidor de desarrollo |
| **OpenSheetMusicDisplay (OSMD)** | Renderizado de partituras MusicXML |
| **jsPDF** | Generación del PDF de salida |

## 🎯 Caso de uso

Pensado para directores de coro y editores musicales que necesitan generar partituras SATB en PDF a partir de archivos MusicXML de forma rápida y sin instalar software, garantizando que el material musical no se comparte con terceros.

## 📄 Licencia

MIT
