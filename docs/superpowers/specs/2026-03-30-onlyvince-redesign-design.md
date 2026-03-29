# OnlyVince.net Redesign

## Goal

Transform onlyvince.net from a generic OnlyFans parody into a distinctive dating profile that genuinely attracts dates (primary) while subtly showcasing professional credibility (secondary). The site should feel like Vince — not like a template.

## Visual Identity

### Color Palette

| Role | Color | Hex |
|------|-------|-----|
| Background | Near-black | #0b0b0b |
| Card background | Dark navy | #16161e |
| Primary | Purple | #9b59b6 |
| Accent | Orange | #e67e22 |
| Warm | Red | #e74c3c |
| Gradient | Warm→purple | #e67e22 → #e74c3c → #9b59b6 |

Replaces the current OnlyFans blue (#00AFF0) entirely.

### Cover Banner

Gradient from purple → red → orange → dark, with animated dashed SVG lines (from vincentologie visual language). Lines are subtle (low opacity), moving slowly. No emoji system — just the visual DNA.

### Accent Usage

- **Purple**: primary actions, verified badges, pinned post borders, active tab indicators, social link backgrounds
- **Orange**: accent highlights, premium labels, "Wat ik bouw" social link (distinct from others), new content markers
- **Warm gradient** (orange→red→purple): CTA button ("Swipe Right"), cover banner
- **Post borders**: subtle purple tint on pinned post, neutral on others

### Typography & Layout

Keep the current system font stack and layout structure (single column, 580px max-width). The OnlyFans-style structure is the joke — just reskinned with the new palette.

## Language

All content in Dutch. Not translated English — proper, natural Dutch that sounds like how Vince actually talks. The tone: zelfspot zonder zelfhaat, kwetsbaar zonder wanhopig.

## Content Plan

### Post Lineup (8 posts)

#### 1. Vastgepind: De Pitch (Free)
- **Action**: Full rewrite in Dutch
- **Changes**: Merge "Why I'm Single" narrative into this post. The "did the work, knows what he wants" story belongs in the opening, not buried in a premium post. Promote the Wi-Fi line ("Fixt je Wi-Fi EN je standaarden voor emotionele beschikbaarheid") — it's the strongest line on the site.
- **Priority**: High — this is the first real content visitors read

#### 2. Wat ik meebring (Free)
- **Action**: Rewrite in Dutch
- **Changes**: Less checkbox-style list, more personality. The current version reads like a feature spec. Rewrite with the same humor but more flow.
- **Priority**: Medium

#### 3. Echte Gevoelens (Premium)
- **Action**: Translate blurred text, but focus effort on the lock-text and CTA
- **Lock-text**: Strong, intriguing teaser (currently "De Zachte Kant — Kijkwijzer Aangeraden 🥺" — already Dutch, refine if needed)
- **CTA**: "Ontgrendel met een eerste date" → WhatsApp
- **Priority**: Lock-text is high, blurred content is low (invisible to visitors)

#### 4. Dealbreakers (Free)
- **Action**: Translate to Dutch
- **Changes**: Minimal — the literal-mindedness framing and direct tone already work. Just make it proper Dutch.
- **Priority**: Medium

#### 5. Hoe een date eruitziet (Premium)
- **Action**: Translate and tighten
- **Changes**: Current version is generic dating profile territory. Tighten to something more distinctly Vince. Focus on lock-text.
- **Lock-text**: Update to Dutch
- **Priority**: Lock-text is medium, blurred content is low

#### 6. Het vader-ding (Premium)
- **Action**: Translate to Dutch
- **Changes**: The DILF manifesto works. Translate faithfully. Focus on lock-text.
- **Lock-text**: Update to Dutch
- **Priority**: Lock-text is medium, blurred content is low

#### 7. Boyfriend Changelog v46.0 (Premium)
- **Action**: Translate to Dutch
- **Changes**: The dev humor format is authentic and naturally bridges to the professional side. Keep the changelog structure.
- **Lock-text**: Update to Dutch
- **Priority**: Lock-text is medium, blurred content is low

#### 8. NEW: Wat ik bouw als ik niet hier ben (Free)
- **Action**: Write new post
- **Purpose**: Professional crossover. Not a CV — shows what Vince does in a way that's interesting to a date, not a recruiter. Links to vincability.com naturally (not as a hard sell).
- **Tone**: Same as rest of site. "Oh by the way, I also build things" energy.
- **Priority**: Medium

### Posts Removed

- **Friday Night Options**: Cut — generic, adds nothing distinctive
- **Why I'm Single**: Merged into the pinned pitch post

### Premium Content Strategy

The blurred premium content is invisible to visitors. Investment priority:

1. **Lock-texts** — the teaser headlines visible on each premium post. These sell the mystery.
2. **CTAs** — the unlock buttons. All route to WhatsApp with contextual prefill messages.
3. **Blurred content** — lowest priority. It's decoration. Write something decent but don't agonize over it.

## Bio Refinements (from external feedback)

| Fix | Detail |
|-----|--------|
| Height joke placement | Move "186cm*" and the fine print disclaimer out of the top bio line. Place it lower (e.g., after stats row or in footer) so it lands as a joke after they already like you, not as the opening. |
| Drop "fully serviced" | "Vers gescheiden, factory reset complete ✨" — "fully serviced" reads sexually in a way that undercuts the opening. Remove it. |
| 9.2/10 context | Add "zelf beoordeeld, nog geen peer review" or similar — makes the joke land instead of being random. |
| Wi-Fi line promotion | "Fixt je Wi-Fi EN je standaarden voor emotionele beschikbaarheid" — this is the best line. Move it to the bio or the pinned post opening where it gets read. |
| WhatsApp CTA | Keep as-is. Deliberate choice to have direct contact. No changes. |

## Professional Crossover

Two touchpoints:

1. **Social link**: "Wat ik bouw" link in the social links row, styled with orange accent to differentiate from GitHub/LinkedIn/Email links. Links to vincability.com.
2. **Post**: The new "Wat ik bouw als ik niet hier ben" free post. Natural discovery — she reads through the dating content and finds out he's also professionally impressive.

## Technical Scope

This is a CSS + HTML rewrite of an existing static site. No framework, no build tools, no new dependencies.

- **styles.css**: Full color palette swap, cover gradient update, animated SVG lines, button gradient, updated label colors
- **index.html**: All content rewritten/translated to Dutch, post lineup restructured, bio refinements applied, new post added, social link added
- **No new files** beyond what already exists (index.html, styles.css, assets/profile.jpg)

## Out of Scope

- No JavaScript changes (toast system, WhatsApp links work the same)
- No responsive layout changes (current mobile handling is fine)
- No new assets or images
- No vincentologie emoji system (👽🤖→🥰 stays on paniekpoppetje.nl)
- No tab functionality (tabs remain decorative as they are now)
