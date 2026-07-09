# 🎨 Steam Grid Studio

Generate custom Steam library artwork — grids, hero banners & logos — for your games in seconds.

Steam Grid Studio is a Python tool that creates custom Steam library artwork — capsule grids, hero banners, and logos — for any game in your library. Pick a style template (retro CRT, minimal, neon, vaporwave, pixel art), point it at a game, and get ready-to-use Steam-sized assets without touching Photoshop or GIMP.

Pairs well with [Steam-Startup-Movies](https://github.com/MRJeffyy/Steam-Startup-Movies) if you're into fully customizing your Steam Big Picture experience.

## ✨ Features

- 🖼️ Generate all standard Steam asset sizes (capsule grid, hero banner, logo)
- 🎭 5 built-in style templates (retro CRT, minimal, neon, vaporwave, pixel art)
- 🖱️ Simple GUI available, or a fast CLI for no-fuss scripting
- 🧩 Works with any game name
- 🛠️ Easy to extend with your own custom templates

## 📦 Installation
git clone https://github.com/MRJeffyy/Steam-Grid-Studio.git
cd Steam-Grid-Studio
pip install -r requirements.txt

## 🚀 Usage

### CLI
python steamgrid.py --game "Half-Life 2" --style retro

| Flag | Description |
|------|-------------|
| `--game` | Name of the game |
| `--style` | Style template to use (`retro`, `minimal`, `neon`, `vaporwave`, `pixel`) |
| `--output` | Output folder (default: `./output`) |

### GUI

Prefer clicking over typing commands? Run:
python steamgrid_gui.py

This opens a simple window where you can type the game name, pick a style from a dropdown, choose an output folder, and hit **Generate**.

## 🖌️ Style Templates

- **Retro** — CRT scanlines, glitch, and chromatic aberration
- **Minimal** — Clean, flat design with an accent line
- **Neon** — Vibrant synthwave glow with horizon lines
- **Vaporwave** — Sunset gradient, glowing sun, and perspective grid
- **Pixel** — Chunky 8-bit checkerboard background with hard-shadow text

## 📁 Output Sizes

| Asset | Size |
|-------|------|
| Grid Capsule | 600x900 |
| Hero Banner | 1920x620 |
| Logo | 1280x720 |

## 🤝 Contributing

Contributions, ideas, and new style templates are welcome! Feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
