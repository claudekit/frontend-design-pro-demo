# Frontend Design Pro Demo

A comprehensive showcase of 11 modern frontend design aesthetics with master prompts, signature effects, and production-ready code.

## Live Demo

**[View Demo](https://claudekit.github.io/frontend-design-pro-demo/)**

## 11 Aesthetic Directions

| # | Style | Key Characteristics |
|---|-------|---------------------|
| 01 | **Minimalism & Swiss Style** | Rigorous grid systems, massive typography, asymmetric magazine layout |
| 02 | **Neumorphism** | Extruded elements, multiple drop shadows, "pressed in" buttons |
| 03 | **Glassmorphism** | Animated mesh gradients, frosted glass cards, backdrop-filter blur |
| 04 | **Brutalism** | Thick 3-4px borders, hard drop shadows, masonry/broken grid |
| 05 | **Claymorphism** | Inflated 3D clay, marshmallow shapes, candy pastels |
| 06 | **Aurora / Mesh Gradient** | Slow-moving breathing blobs, floating glass overlays |
| 07 | **Retro-Futurism / Cyberpunk** | Aggressive neon, CRT scanlines, HUD elements, glitch effects |
| 08 | **3D Hyperrealism** | Realistic textures, cinematic lighting, physics-based motion |
| 09 | **Vibrant Block / Maximalist** | Solid clashing RGB blocks, thick borders, snap hover effects |
| 10 | **Dark OLED Luxury** | Absolute black + Gold accents, spotlight cursor, gold foil gradients |
| 11 | **Organic / Biomorphic** | "Living Earth" palette, morphing blobs, wavy dividers |

## Installation (Claude Code Plugin)

Install as a Claude Code plugin to get the `frontend-design-pro` skill:

```bash
# From GitHub
claude /plugin install vibery-studio/frontend-design-pro-demo

# Or from local directory
claude /plugin install /path/to/frontend-design-pro-demo
```

Once installed, Claude will automatically use the skill when building frontend interfaces.

### Plugin Structure

```
frontend-design-pro-demo/
├── .claude-plugin/
│   └── plugin.json     # Plugin metadata
└── skills/
    └── frontend-design-pro/
        └── SKILL.md    # Skill definition
```

## Usage

Example prompt:
```markdown
use frontend-design-pro to create a frontend interface for <project-name> with <aesthetic-direction> style.
```
That's it!

## Project Structure

```
frontend-design-pro-demo/
├── .claude-plugin/     # Claude Code plugin config
├── skills/             # Plugin skills
├── demos-v01/          # Version 1 demos
├── demos-v02/          # Version 2 demos (latest)
│   ├── index.html      # Main showcase page
│   ├── 01-minimalism-swiss.html
│   ├── 02-neumorphism.html
│   ├── 03-glassmorphism.html
│   ├── 04-brutalism.html
│   ├── 05-claymorphism.html
│   ├── 06-aurora-mesh-gradient.html
│   ├── 07-retro-futurism-cyberpunk.html
│   ├── 08-3d-hyperrealism.html
│   ├── 09-vibrant-block-maximalist.html
│   ├── 10-dark-oled-luxury.html
│   ├── 11-organic-biomorphic.html
│   └── screenshots/    # Preview images
└── README.md
```

## Features

- Pure HTML/CSS implementations (no frameworks required)
- Master prompts for each aesthetic direction
- Color palettes and signature effects
- Responsive design
- Production-ready code

## Usage

Each demo includes a "Master Prompt" section that describes the key characteristics and techniques used. Use these prompts as a reference when creating your own designs in that aesthetic style.

## License

MIT

## Credit

**Powered by [ClaudeKit](https://claudekit.cc)**

**I've been spending 7+ months to dig into every aspect of Claude Code so you don't have to.**

[![ClaudeKit Agent Skills](https://github.com/mrgoonie/claudekit-skills/blob/main/claudekit.png?raw=true)](https://claudekit.cc)

I've basically been sharing everything I learned about Claude Code on this Substack: [https://faafospecialist.substack.com/](https://faafospecialist.substack.com/)

So if you find this collection useful, please consider supporting my product at [ClaudeKit.cc](https://claudekit.cc).

Thanks so much! 🥰
*[Duy /zuey/](https://x.com/goon_nguyen)*