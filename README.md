# MaquinaPlanos 🛠️

Diseña planos de máquinas con ayuda de Gemini AI. Una web interactiva donde la inteligencia artificial te guía con preguntas para generar las piezas de tu máquina, que luego puedes arrastrar a un lienzo de planos.

## ✨ Características

- 🤖 **Chat con Gemini AI** — hace hasta 20 preguntas para entender tu máquina
- 📦 **Generación de piezas** — Gemini genera automáticamente los componentes
- 🖱️ **Drag & Drop** — arrastra las piezas al lienzo para construir el plano
- 📐 **Lienzo técnico** — cuadrícula estilo blueprint, con coordenadas en tiempo real
- 📋 **Exportar** — descarga el plano en JSON o SVG
- 🎨 **Diseño moderno** — interfaz oscura y colorida

## 🚀 Cómo usarlo en GitHub Pages

### 1. Crea el repositorio

```bash
# En GitHub, crea un nuevo repositorio llamado: dise-adoradeplanos
# Luego clónalo localmente:
git clone https://github.com/wanabisen/dise-adoradeplanos.git
cd dise-adoradeplanos
```

### 2. Añade los archivos

Copia el archivo `index.html` en la raíz del repositorio.

```bash
cp index.html dise-adoradeplanos/
cd dise-adoradeplanos
git add .
git commit -m "🚀 Primera versión de MaquinaPlanos"
git push origin main
```

### 3. Activa GitHub Pages

1. Ve a tu repositorio en GitHub
2. `Settings` → `Pages`
3. En **Source**, selecciona `main` branch y carpeta `/root`
4. Guarda. En 1-2 minutos estará en: `https://wanabisen.github.io/dise-adoradeplanos`

## 🔑 API Key de Gemini

1. Ve a [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Crea una API Key gratuita
3. Pégala en la web cuando la abras

> **Nota:** La API Key nunca se guarda en el servidor. Solo se usa en tu navegador para llamar directamente a la API de Google.

## 🛠️ Tecnologías

- HTML5 / CSS3 / JavaScript Vanilla
- Google Gemini 2.0 Flash API
- Sin frameworks ni dependencias externas (excepto Google Fonts)

## 📄 Licencia

MIT — úsalo libremente.
