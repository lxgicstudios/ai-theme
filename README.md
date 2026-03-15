# ai-theme

[![npm version](https://img.shields.io/npm/v/ai-theme.svg)](https://www.npmjs.com/package/ai-theme)
[![npm downloads](https://img.shields.io/npm/dm/ai-theme.svg)](https://www.npmjs.com/package/ai-theme)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-theme)](https://github.com/lxgic-studios/ai-theme/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Generate a complete design system from your brand colors. Gets you a full color palette, typography scale, spacing, shadows, and more.

## Install

```bash
npm install -g ai-theme
```

## Usage

```bash
npx ai-theme "#FF4500" "#1A1A2E"
# Generates CSS custom properties

npx ai-theme "#FF4500" "#1A1A2E" -f tailwind
# Generates tailwind.config.js theme extension

npx ai-theme "#FF4500" "#1A1A2E" -f json -o tokens.json
# Saves design tokens as JSON
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## Options

- `-f, --format <type>` - Output format: css, tailwind, json (default: css)
- `-o, --output <path>` - Save to file

## License

MIT


---

Built by [LXGIC Studios](https://github.com/LXGIC-Studios)

🔗 [GitHub](https://github.com/LXGIC-Studios) · [Twitter](https://x.com/lxgicstudios)

💡 Want more free tools like this? We have 100+ on our GitHub: [github.com/lxgicstudios](https://github.com/lxgicstudios)
