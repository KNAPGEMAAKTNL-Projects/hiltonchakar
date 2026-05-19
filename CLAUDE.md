# Hilton Shakar Project Guidelines

## Brand Name
Always write the brand name as **Hilton Shakar** (working — confirm with operator before any client-facing copy).

## Tech Stack
- Framework: Astro 6 (Static Site Generation)
- Styling: Tailwind CSS 4 (via @tailwindcss/vite, NOT @astrojs/tailwind)
- Deployment: Cloudflare Pages
- Animation: CSS-only (or GSAP if interaction level requires it)

## Design System
Read `SESSION1-DECISIONS.md` and `homepage-reference.html` before making any
visual decisions. `.impeccable.md` holds the creative context.
Read `.claude/rules/astro-conversion.md` and `.claude/rules/design-fidelity.md`
before any build — these MUST be followed.

## Skills
Activate `frontend-design` for any HTML generation tasks.
Use Impeccable commands (/audit, /critique, /polish, etc.) for design refinement.

## Copy Language
en — set during Session 1 Step 1 (international travelers, hospitality default).
Confirm with operator before Session 2; possibly also fr/ar. This determines which
`lang/` copywriting references Session 2 loads from Hub/business/sops/copywriting/lang/.

## Critical Rules
- Trailing slash: trailingSlash: "never" in astro.config (greenfield project)
- All text in English unless operator specifies otherwise
- Hospitality / boutique short-stay context — write like a riad owner, not a hotel chain
- Never use stock photos for apartment / property imagery — real apartment photos only
- Never use aggressive sales language ("Book now and save!", "#1 in Morocco", etc.)
- Never use casual / pushy CTAs — hospitality voice is calm, hosted, gracious
- NEVER add max-w-*, mx-auto, or container wrappers not in the reference HTML
- NEVER normalize padding/margin values across sections — varied rhythm is intentional
- NEVER symmetrize asymmetric layouts from the reference design
- No gradient text, no glassmorphism/glow borders, no rounded corners > 8px
  (boutique hospitality archetype — refined edges, not playful)
- No identical card layouts repeated 3-4 times — vary per apartment / section

## Design Context
[POPULATED BY /teach-impeccable IN STEP 5 — left empty during setup]

## Reference Project
Sister project for vibe reference (do NOT copy verbatim): `C:\Code\clients\byshakir` —
"By Shakir Luxury Interiors". Hilton Shakar is the "hotel-neat" / hospitality version
of the same warm Mediterranean aesthetic. Likely same owner / family — confirm with operator.
