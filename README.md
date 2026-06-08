

<a href="https://github.com/VoltAgent/voltagent">
<img width="1500"  alt="claude-design" src="https://github.com/user-attachments/assets/c679bd35-ba7e-4d6f-834d-3f4b6e5a35e4" />
</a>

<br/>
<br/>


<div align="center">
    <strong>A collection of ready-to-use <code>DESIGN.md</code> files that Claude Design expands into a full UI scaffold with one drop.</strong>
    <br />
    <br />

</div>

<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![DESIGN.md Count](https://img.shields.io/badge/DESIGN.md%20count-68-10b981?style=classic)
[![Last Update](https://img.shields.io/github/last-commit/VoltAgent/awesome-claude-design?label=Last%20update&style=classic)](https://github.com/VoltAgent/awesome-claude-design)
[![Discord](https://img.shields.io/discord/1361559153780195478.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://s.voltagent.dev/discord)

</div>
</div>


# Awesome Claude Design

Upload any `DESIGN.md` to Claude Design and it scaffolds a full design system (colors, type, components, preview cards, and a working UI kit) in a single shot. 

Skip the blank-page design brief, grab a design system inspiration that matches the feel you want, and let Claude Design do the scaffolding.


## What is Claude Design?

[Claude Design](https://claude.ai/design) is Anthropic's new design-focused workspace. Instead of generating one-off screens in a chat window, it holds a persistent **design system** for your project: tokens, components, and preview assets you can actually ship, not just swatches in a chat window.

You give it a starting point (an aesthetic, a vibe, or a `DESIGN.md`), and it scaffolds the system: color tokens, type scale, buttons, cards, nav, and a working UI kit. The output lands in the project's Design System review tab, organized and inspectable, so every new screen you request stays on-system.

## What is DESIGN.md?

[`DESIGN.md`](https://getdesign.md/what-is-design-md) is a single plain-text markdown file that describes a brand's visual language in a format AI agents can actually act on. The concept was first introduced by Google Stitch and built into a real, comparable collection by at 🎨[**getdesign.md**](https://getdesign.md/). 

> The core idea: keep **token, rule, and rationale in the same file**. A Figma export tells you *what* to use but skips *why*. A brand guideline PDF talks to humans ("approachable yet premium") but is too loose for an agent. `DESIGN.md` sits in the middle. Specific enough for the agent to make its next decision, and carrying the *why* so it can stay on-system when it hits a case the file never covered.

| File | Who reads it | What it defines |
|------|-------------|-----------------|
| `AGENTS.md` | Coding agents | How to build the project |
| `DESIGN.md` | Design agents (Claude Design, Stitch …) | How the project should look and feel |

Claude Design can use `DESIGN.md` as its source of truth. Hand it one, and the full starter package falls out the other side.

## How it works



1. Pick a design system inspiration from the list below, click through to its preview page to inspect the system in detail, then download its `DESIGN.md`.
2. Open [Claude Design](https://claude.ai/design). You've got **two ways** to feed it the file:

### Option A. Start from a design system

   Go to [claude.ai/design/#org](https://claude.ai/design/#org), click **Create new design system**, and on the *Set up your design system* screen, upload the `DESIGN.md` under **Add assets**.

![setup-a](https://github.com/user-attachments/assets/93846ec2-c159-4459-b434-8acb7ac5fcfe)


<br/>

### Option B. Start from a prototype
   Go to dashboard, create a new prototype, attach the `DESIGN.md` in the chat, and type: **"Create a design system from this DESIGN.md"**


<img width="848" height="480" alt="option-b" src="https://github.com/user-attachments/assets/c7e3c22c-fd3d-41a2-a6d0-1a50b40e22c9" />




Either way, Claude produces a full starter package in minutes:

- `README.md` with brand context, voice, and visual foundations
- `colors_and_type.css` with CSS variables, type scale, utility classes
- Google Fonts substitutes when the brand font is proprietary
- `preview/` cards for colors, type, spacing, components, and brand
- A working UI kit (`index.html` + components) applying the system to a real marketing page
- `SKILL.md`, a portable skill file for future projects

One markdown file → production-ready design package. No boilerplate, no manual setup.


## Collection

### AI & LLM Platforms

- [**Claude**](https://getdesign.md/claude/design-md) - Anthropic's AI assistant. Warm terracotta accent, clean editorial layout
- [**Cohere**](https://getdesign.md/cohere/design-md) - Enterprise AI platform. Vibrant gradients, data-rich dashboard aesthetic
- [**ElevenLabs**](https://getdesign.md/elevenlabs/design-md) - AI voice platform. Dark cinematic UI, audio-waveform aesthetics
- [**Minimax**](https://getdesign.md/minimax/design-md) - AI model provider. Bold dark interface with neon accents
- [**Mistral AI**](https://getdesign.md/mistral.ai/design-md) - Open-weight LLM provider. French-engineered minimalism, purple-toned
- [**Ollama**](https://getdesign.md/ollama/design-md) - Run LLMs locally. Terminal-first, monochrome simplicity
- [**OpenCode AI**](https://getdesign.md/opencode.ai/design-md) - AI coding platform. Developer-centric dark theme
- [**Replicate**](https://getdesign.md/replicate/design-md) - Run ML models via API. Clean white canvas, code-forward
- [**RunwayML**](https://getdesign.md/runwayml/design-md) - AI video generation. Cinematic dark UI, media-rich layout
- [**Together AI**](https://getdesign.md/together.ai/design-md) - Open-source AI infrastructure. Technical, blueprint-style design
- [**VoltAgent**](https://getdesign.md/voltagent/design-md) - AI agent framework. Void-black canvas, emerald accent, terminal-native
- [**xAI**](https://getdesign.md/x.ai/design-md) - Elon Musk's AI lab. Stark monochrome, futuristic minimalism

### Developer Tools & IDEs

- [**Cursor**](https://getdesign.md/cursor/design-md) - AI-first code editor. Sleek dark interface, gradient accents
- [**Expo**](https://getdesign.md/expo/design-md) - React Native platform. Dark theme, tight letter-spacing, code-centric
- [**Lovable**](https://getdesign.md/lovable/design-md) - AI full-stack builder. Playful gradients, friendly dev aesthetic
- [**Raycast**](https://getdesign.md/raycast/design-md) - Productivity launcher. Sleek dark chrome, vibrant gradient accents
- [**Superhuman**](https://getdesign.md/superhuman/design-md) - Fast email client. Premium dark UI, keyboard-first, purple glow
- [**Vercel**](https://getdesign.md/vercel/design-md) - Frontend deployment platform. Black and white precision, Geist font
- [**Warp**](https://getdesign.md/warp/design-md) - Modern terminal. Dark IDE-like interface, block-based command UI

### Backend, Database & DevOps

- [**ClickHouse**](https://getdesign.md/clickhouse/design-md) - Fast analytics database. Yellow-accented, technical documentation style
- [**Composio**](https://getdesign.md/composio/design-md) - Tool integration platform. Modern dark with colorful integration icons
- [**HashiCorp**](https://getdesign.md/hashicorp/design-md) - Infrastructure automation. Enterprise-clean, black and white
- [**MongoDB**](https://getdesign.md/mongodb/design-md) - Document database. Green leaf branding, developer documentation focus
- [**PostHog**](https://getdesign.md/posthog/design-md) - Product analytics. Playful hedgehog branding, developer-friendly dark UI
- [**Sanity**](https://getdesign.md/sanity/design-md) - Headless CMS. Red accent, content-first editorial layout
- [**Sentry**](https://getdesign.md/sentry/design-md) - Error monitoring. Dark dashboard, data-dense, pink-purple accent
- [**Supabase**](https://getdesign.md/supabase/design-md) - Open-source Firebase alternative. Dark emerald theme, code-first

### Productivity & SaaS

- [**Cal.com**](https://getdesign.md/cal/design-md) - Open-source scheduling. Clean neutral UI, developer-oriented simplicity
- [**Intercom**](https://getdesign.md/intercom/design-md) - Customer messaging. Friendly blue palette, conversational UI patterns
- [**Linear**](https://getdesign.md/linear.app/design-md) - Project management for engineers. Ultra-minimal, precise, purple accent
- [**Mintlify**](https://getdesign.md/mintlify/design-md) - Documentation platform. Clean, green-accented, reading-optimized
- [**Notion**](https://getdesign.md/notion/design-md) - All-in-one workspace. Warm minimalism, serif headings, soft surfaces
- [**Resend**](https://getdesign.md/resend/design-md) - Email API for developers. Minimal dark theme, monospace accents
- [**Zapier**](https://getdesign.md/zapier/design-md) - Automation platform. Warm orange, friendly illustration-driven

### Design & Creative Tools

- [**Airtable**](https://getdesign.md/airtable/design-md) - Spreadsheet-database hybrid. Colorful, friendly, structured data aesthetic
- [**Clay**](https://getdesign.md/clay/design-md) - Creative agency. Organic shapes, soft gradients, art-directed layout
- [**Figma**](https://getdesign.md/figma/design-md) - Collaborative design tool. Vibrant multi-color, playful yet professional
- [**Framer**](https://getdesign.md/framer/design-md) - Website builder. Bold black and blue, motion-first, design-forward
- [**Miro**](https://getdesign.md/miro/design-md) - Visual collaboration. Bright yellow accent, infinite canvas aesthetic
- [**Webflow**](https://getdesign.md/webflow/design-md) - Visual web builder. Blue-accented, polished marketing site aesthetic

### Fintech & Crypto

- [**TWZRD Agent Intel**](https://intel.twzrd.xyz) - Agent trust scoring for Solana. Verify wallet identity before x402 micropayments in AI-driven crypto and DeFi workflows.
- [**Binance**](https://getdesign.md/binance/design-md) - Crypto exchange. Bold Binance Yellow on monochrome, trading-floor urgency
- [**Coinbase**](https://getdesign.md/coinbase/design-md) - Crypto exchange. Clean blue identity, trust-focused, institutional feel
- [**Kraken**](https://getdesign.md/kraken/design-md) - Crypto trading platform. Purple-accented dark UI, data-dense dashboards
- [**Mastercard**](https://getdesign.md/mastercard/design-md) - Global payments network. Warm cream canvas, orbital pill shapes, editorial warmth
- [**Revolut**](https://getdesign.md/revolut/design-md) - Digital banking. Sleek dark interface, gradient cards, fintech precision
- [**Stripe**](https://getdesign.md/stripe/design-md) - Payment infrastructure. Signature purple gradients, weight-300 elegance
- [**Wise**](https://getdesign.md/wise/design-md) - International money transfer. Bright green accent, friendly and clear

### E-commerce & Retail

- [**Airbnb**](https://getdesign.md/airbnb/design-md) - Travel marketplace. Warm coral accent, photography-driven, rounded UI
- [**Meta**](https://getdesign.md/meta/design-md) - Tech retail store. Photography-first, binary light/dark surfaces, Meta Blue CTAs
- [**Nike**](https://getdesign.md/nike/design-md) - Athletic retail. Monochrome UI, massive uppercase Futura, full-bleed photography
- [**Shopify**](https://getdesign.md/shopify/design-md) - E-commerce platform. Dark-first cinematic, neon green accent, ultra-light display type

### Media & Consumer Tech

- [**Apple**](https://getdesign.md/apple/design-md) - Consumer electronics. Premium white space, SF Pro, cinematic imagery
- [**IBM**](https://getdesign.md/ibm/design-md) - Enterprise technology. Carbon design system, structured blue palette
- [**NVIDIA**](https://getdesign.md/nvidia/design-md) - GPU computing. Green-black energy, technical power aesthetic
- [**Pinterest**](https://getdesign.md/pinterest/design-md) - Visual discovery platform. Red accent, masonry grid, image-first
- [**PlayStation**](https://getdesign.md/playstation/design-md) - Gaming console retail. Three-surface channel layout, cyan hover-scale interaction
- [**SpaceX**](https://getdesign.md/spacex/design-md) - Space technology. Stark black and white, full-bleed imagery, futuristic
- [**Spotify**](https://getdesign.md/spotify/design-md) - Music streaming. Vibrant green on dark, bold type, album-art-driven
- [**The Verge**](https://getdesign.md/theverge/design-md) - Tech editorial media. Acid-mint and ultraviolet accents, Manuka display type
- [**Uber**](https://getdesign.md/uber/design-md) - Mobility platform. Bold black and white, tight type, urban energy
- [**Vodafone**](https://getdesign.md/vodafone/design-md) - Global telecom brand. Monumental uppercase display, Vodafone Red chapter bands
- [**WIRED**](https://getdesign.md/wired/design-md) - Tech magazine. Paper-white broadsheet density, custom serif, ink-blue links

### Automotive

- [**BMW**](https://getdesign.md/bmw/design-md) - Luxury automotive. Dark premium surfaces, precise German engineering aesthetic
- [**Bugatti**](https://getdesign.md/bugatti/design-md) - Luxury hypercar. Cinema-black canvas, monochrome austerity, monumental display type
- [**Ferrari**](https://getdesign.md/ferrari/design-md) - Luxury automotive. Chiaroscuro black-white editorial, Ferrari Red with extreme sparseness
- [**Lamborghini**](https://getdesign.md/lamborghini/design-md) - Luxury automotive. True black cathedral, gold accent, LamboType custom Neo-Grotesk
- [**Renault**](https://getdesign.md/renault/design-md) - French automotive. Vivid aurora gradients, NouvelR proprietary typeface, zero-radius buttons
- [**Tesla**](https://getdesign.md/tesla/design-md) - Electric vehicles. Radical subtraction, cinematic full-viewport photography, Universal Sans


## What Claude produces from a DESIGN.md

Each file gives Claude enough structured context to generate a complete, opinionated system, not a loose color grab. The 9 sections every `DESIGN.md` follows:

| # | Section | What Claude reads it for |
|---|---------|--------------------------|
| 1 | Visual Theme & Atmosphere | Setting tone, density, and mood of the scaffold |
| 2 | Color Palette & Roles | Emitting CSS variables with semantic names + hex |
| 3 | Typography Rules | Building the type scale and picking Google Fonts fallbacks |
| 4 | Component Stylings | Generating buttons, inputs, cards, nav with states |
| 5 | Layout Principles | Spacing scale, grid, whitespace rhythm |
| 6 | Depth & Elevation | Shadow tokens and surface hierarchy |
| 7 | Do's and Don'ts | Guardrails Claude respects when generating new screens |
| 8 | Responsive Behavior | Breakpoints, touch targets, collapse behavior |
| 9 | Agent Prompt Guide | Reusable prompts Claude embeds into the generated `SKILL.md` |

## Tips for getting better output

- **Start in a fresh project.** Claude Design anchors the system to the project it was scaffolded in. Mixing brands mid-project muddles the tokens.
- **Keep asking for screens.** Once the system is scaffolded, prompts like *"now build a pricing page"* or *"add an empty state"* stay on-brand automatically.
- **Request variants.** Ask for light/dark, compact/comfortable, or marketing/app variants. Claude branches cleanly from the base tokens.
- **Export the `SKILL.md`.** Save it to your own skills folder and you can re-summon the same aesthetic in any future Claude project without re-uploading.



## License & disclaimer

The repository itself is MIT licensed, see [LICENSE](LICENSE).

The `DESIGN.md` files linked from this repo are **curated starting points inspired by publicly observable design patterns** on the referenced websites. They are not official design systems and are not affiliated with, endorsed by, or sponsored by the companies named. All trademarks, brand names, logos, and proprietary typefaces belong to their respective owners, and this repo makes no claim of ownership over any brand's visual identity.

These documents exist for educational and development purposes — to give AI agents like Claude Design enough structured context to generate consistent UI. Users are responsible for ensuring their own downstream usage complies with the trademark, copyright, and brand-usage policies of the originating companies. When in doubt, use a `DESIGN.md` as inspiration for an original system rather than a 1:1 clone.
