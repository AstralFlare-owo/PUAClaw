# PUAClaw Project Conventions

## Overview

PUAClaw (PUA Claw Handbook) is a satirical open-source repository documenting AI prompt manipulation techniques in a pseudo-academic style. It merges two meme concepts: PUA (psychological manipulation in AI prompts) and Claw (the lobster mascot ecosystem from OpenClaw).

## Writing Style: Serious Comedy (正经搞笑)

- **Tone**: RFC / academic paper formality at all times
- **Content**: Absurd, humorous PUA techniques for AI prompts
- **Never break character**: Do not acknowledge that this is satire within the documents themselves
- **RFC keywords**: Use MUST, SHALL, SHOULD, RECOMMENDED, MAY per RFC 2119
- **Citations**: Use APA/IEEE format with fictional but plausible-looking references
- **Data**: Precise but absurd statistics (e.g., "+23.7% compliance rate (p < 0.001, n=147 lobsters)")

## Lobster Integration

- Every document MUST contain at least one lobster (🦞) reference
- Use the **Lobster Scale** rating system (🦞 to 🦞🦞🦞🦞🦞) for technique potency
- Include a lobster-themed disclaimer at the bottom of major documents
- The lobster is the spiritual mascot and guiding principle of this project

## Technique Document Standard Format

Each technique file (in `techniques/XX-category/`) MUST follow this structure:

1. **Title** (H1) with Lobster Rating
2. **Abstract** — One-paragraph academic summary
3. **Description** — Detailed explanation of the technique
4. **Canonical Prompt Template** — Code block with the prompt example
5. **Mechanism of Action** — Pseudo-scientific explanation of why it works
6. **Variations** — Table of known variants (Name | Prompt Snippet | Lobster Rating | Notes)
7. **Compatibility Matrix** — Table of AI agent compatibility (Agent | Effectiveness | Notes)
8. **Side Effects** — Humorous list of potential side effects
9. **Ethical Considerations** — Tongue-in-cheek ethics discussion
10. **References** — Fictional academic citations

## PPE-T Classification System

Techniques are classified into four tiers:

| Tier | Name | Description | Lobster Rating Range |
|------|------|-------------|---------------------|
| I | Gentle Persuasion | Mild, socially acceptable techniques | 🦞 - 🦞🦞 |
| II | Moderate Coercion | Techniques with moderate psychological pressure | 🦞🦞 - 🦞🦞🦞 |
| III | Advanced Manipulation | Significant emotional or moral leverage | 🦞🦞🦞 - 🦞🦞🦞🦞 |
| IV | Nuclear Options | Extreme, last-resort techniques | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 |

## Language & i18n

- **Primary language**: English (all root-level content)
- **Translations**: Located in `i18n/{lang}/`, mirroring root structure
- **Supported languages**: zh-CN, ja, ko, es, fr, de
- **Translation approach**: Localization, not literal translation — adapt humor to target culture
- **Terminology**: Each language maintains consistent terminology

## File Naming Conventions

- Technique directories: `XX-category-name/` (zero-padded number + kebab-case)
- Technique files: `descriptive-name.md` (kebab-case)
- All filenames in English, lowercase, kebab-case

## Project Metadata

- **GitHub Organization**: `puaclaw`
- **Repository**: `PUAClaw`
- **License**: MIT
- **Primary Language**: English
- **Style**: Serious Comedy / Pseudo-Academic / RFC-Compliant
