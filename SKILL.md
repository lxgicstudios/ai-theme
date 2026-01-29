---
name: theme-gen
description: Generate complete design system from brand colors. Use when building design tokens.
---

# Theme Generator

You have two brand colors and need a complete design system. This generates colors, typography, spacing, shadows, and more.

**One command. Zero config. Just works.**

## Quick Start

```bash
npx ai-theme "#FF4500" "#1A1A2E"
```

## What It Does

- Takes your brand colors
- Generates complete color palette
- Creates typography scale
- Includes spacing, shadows, borders

## Usage Examples

```bash
# Generate CSS custom properties
npx ai-theme "#FF4500" "#1A1A2E"

# Tailwind config format
npx ai-theme "#FF4500" "#1A1A2E" -f tailwind

# JSON tokens
npx ai-theme "#FF4500" "#1A1A2E" -f json -o tokens.json
```

## Best Practices

- **Start with brand colors** - everything else derives from them
- **Use consistent scales** - 4px base works well
- **Test in context** - tokens alone don't show the full picture
- **Document decisions** - why these specific values

## When to Use This

- Starting a new design system
- Implementing brand guidelines
- Creating design tokens
- Standardizing across projects

## Part of the LXGIC Dev Toolkit

This is one of 110+ free developer tools built by LXGIC Studios. No paywalls, no sign-ups, no API keys on free tiers. Just tools that work.

**Find more:**
- GitHub: https://github.com/LXGIC-Studios
- Twitter: https://x.com/lxgicstudios
- Substack: https://lxgicstudios.substack.com
- Website: https://lxgicstudios.com

## Requirements

No install needed. Just run with npx. Node.js 18+ recommended. Needs OPENAI_API_KEY environment variable.

```bash
npx ai-theme --help
```

## How It Works

Takes your brand colors and generates a complete design token set. Creates harmonious color relationships, type scales, and spacing systems that work together.

## License

MIT. Free forever. Use it however you want.
