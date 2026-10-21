---
name: Wag N' Bag Dog Waste Removal
description: We scoop the poop so you don't have to. A warm, playful one-page pitch site in the calm band style.
colors:
  paper: "#f7f3ec"
  card: "#ffffff"
  field: "#ebe2d2"
  ink: "#3b2a0e"
  body: "#4a3d2a"
  soft: "#6b5c45"
  brown: "#523c16"
  deep: "#33260d"
  on-dark: "#faf6ee"
  on-dark-soft: "#e3d7c3"
  taupe: "#cdc2b2"
  accent: "#e8a64a"
  accent-2: "#f0b964"
  accent-ink: "#8a520f"
  line: "rgba(59,42,14,.12)"
  focus: "#523c16"
  error: "#b3261e"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(40px, 11.4vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  title:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(20px, 5.4vw, 24px)"
    fontWeight: 400
    lineHeight: 1.15
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.02em"
  button:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1
  step-title-desktop:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "22px"
    fontWeight: 400
    lineHeight: 1.2
  note:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.7
rounded:
  focus: "6px"
  field: "10px"
  panel: "20px"
  card: "24px"
  pill: "999px"
spacing:
  gutter: "20px"
  gutter-desktop: "40px"
  stack-sm: "16px"
  stack-md: "28px"
  section: "64px"
  section-desktop: "96px"
components:
  button-primary:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.accent-2}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  eyebrow:
    backgroundColor: "rgba(59,42,14,.07)"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "9px 14px"
  eyebrow-on-dark:
    backgroundColor: "rgba(255,255,255,.14)"
    textColor: "{colors.on-dark}"
  input:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "#ffffff"
  form-card:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
  link-row:
    backgroundColor: "{colors.brown}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.panel}"
    padding: "14px 16px 14px 22px"
    height: "76px"
  step-number:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "48px"
  float-text:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "60px"
---

# Design System: Wag N' Bag Dog Waste Removal

## Overview

**Creative North Star: "The Warm Porch Note"**

The system is the business's own logo spread across a page: the umber paw, the taupe stripes, warm paper, plus one caramel fill. It is Ellie's calm band style (after lpmr.co.uk) translated from navy-and-gold into umber-and-caramel. Full-bleed bands alternate light and dark so each section is obvious on a phone. Shapes are soft and borderless and the copy is short, so the page reads like a friendly note left by a neighbour rather than a corporate service page.

It is phone-first and sparse. Every band holds one idea: a heading, a short lede, and at most one list or one form. The only display face is Cal Sans; everything else is the system stack at a relaxed 16/1.7. Motion is small and deliberate. The hero headline bounces in letter by letter once, everything below the first screen gets one 12px fade-up, and a single floating text circle appears once the hero is gone. Nothing else moves.

The palette is kept warm and brown on purpose, clearly apart from the green and mustard of another pet-waste business in the same pipeline.

**Key Characteristics:**
- Logo-derived umber neutrals on warm paper, with a single caramel accent used as a fill.
- Full-bleed bands: paper, umber photo hero, deep umber with a faint diagonal line texture, brown closing band.
- One display webfont (Cal Sans, weight 400) for headings, buttons, and labels; system sans for running text.
- Soft, borderless forms: 24px cards, pill buttons and chips, 10px tinted fields.
- Three motions only: hero H1 letter bounce-in, a single fade-up, the floating text circle sliding in.

## Colors

Warm umber neutrals sampled from the logo, plus one caramel accent. Every tone, including the dark bands, leans warm (OKLCH hue around 77 to 82).

### Primary
- **Caramel** (accent): the single warm fill. It appears on primary buttons, numbered step discs, the floating text circle, the eyebrow dot, `::selection`, and (on dark bands only) as the accent phrase of a heading. Text on caramel is always Umber Ink (6.5:1).
- **Light Caramel** (accent-2): the hover state of Caramel fills. It is used nowhere else.
- **Burnt Caramel** (accent-ink): Caramel as text or icon on light grounds, for the header phone icon, the claim icons, the accent phrase in light-band headings, and link hover (5.8:1 on paper).

### Neutral
- **Warm Paper** (paper): the page ground, the header, and the light bands. It is never pure white.
- **Card White** (card): the quote form card, plus the logo disc in the closing band.
- **Oat Field** (field): the fill of inputs and chips on the white form card.
- **Umber Ink** (ink): headings on light, text on caramel, and the selected chip fill.
- **Umber Body** (body): running text on light (9.5:1 on paper).
- **Soft Umber** (soft): secondary text, placeholders, the "(optional)" hints, and the wordmark subline (5.9:1 on paper).
- **Paw Brown** (brown): the logo's paw. It is the hero's base and overlay tint, the closing band, the Facebook link row, and the light-ground focus colour (focus).
- **Deep Umber** (deep): the "How it works" band and the footer, always carrying the diagonal line texture.
- **Cream on Dark** (on-dark) and **Soft Cream** (on-dark-soft): headings and body text on brown and deep bands.
- **Logo Taupe** (taupe): the logo's stripe colour. It is reserved for the ring around the logo disc.
- **Hairline** (line): the 12% umber divider between claim rows.
- **Error Red** (error): the border and message for invalid fields only.

### Named Rules
**The Fill-Only Caramel Rule.** Caramel is a fill. Text on it is Umber Ink. When caramel has to be text on a light ground, use Burnt Caramel instead. Plain Caramel works as text only on brown or deep bands (4.9:1 on brown, 7.0:1 on deep).

**The Warm Dark Rule.** Dark bands use Paw Brown or Deep Umber, never black or a cool grey. The hero overlay is the same umber family: `rgba(46,33,10,.76–.88)`.

**The Faint Line Rule.** Deep Umber surfaces carry `repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)` (the `--texture` token). Keep it at about 4% white or fainter so it never reads as lines through the text. It belongs on deep bands and the footer only, never on paper or brown.

## Typography

**Display Font:** Cal Sans (with Avenir Next, Segoe UI, system-ui)
**Body Font:** System sans (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** Cal Sans is rounded and friendly, and it carries the playful voice in headings, buttons, list titles, and form labels. The system body is quiet and fast. Cal Sans is only ever used at weight 400.

### Hierarchy
- **Display** (400, clamp(40px, 11.4vw, 80px), 1.02): the hero H1 only, in white on the photo overlay, max 12ch.
- **Headline** (400, clamp(30px, 7.6vw, 48px), 1.08): section H2s, balanced wrapping.
- **Title** (400, 20–24px, 1.15–1.2): claim rows, step titles (21px, 22px on desktop), and the Facebook link row.
- **Big Number** (400, clamp(30px, 9vw, 52px), 1): the closing-band phone number.
- **Lede** (400, clamp(17px, 4.6vw, 19px), 1.7, max 38ch): the one paragraph under a section heading. The hero promise is a sibling at clamp(17px, 4.7vw, 20px), 1.5, max 30ch.
- **Body** (400, 16px, 1.7): all running text. Inputs are 16px so iOS doesn't zoom.
- **Label** (500, 14px, 0.02em): eyebrow pills. The wordmark subline is a separate 600 11px uppercase tracked line that belongs to the logo lockup only.
- **Field labels** (Cal Sans 400, 17px, 1.2): form labels and legends.

### Named Rules
**The One Display Face Rule.** Cal Sans is the only webfont, always at weight 400. Use weight and size changes, not a second family.

**The Open Word Space Rule.** Cal Sans sets word spaces tight at small sizes. Wherever it is used at 24px or below (buttons, claim rows, step titles, field labels, the wordmark, phone numbers), add `word-spacing: .08em`.

## Layout

There is a single centred column, max 1160px, with a 20px gutter on phones and 40px from 760px. Sections are full-bleed bands with 64px vertical padding, rising to 96px on desktop. Band order: paper header, then the brown photo hero, paper, deep (texture), paper (form), brown close, and the deep footer.

Within a band, content stacks with gaps of 16px between heading and lede, and 28px between blocks. Breakpoints:
- **≤380px:** tightens the header lockup (36px mark, 18px wordmark) and chip padding.
- **≤759px:** the hero gets a 210px bottom strip so the dog in the photo shows below the buttons. The overlay thins to 25–35% at the bottom.
- **≥760px:** wider gutter, taller header (80px), and the hero buttons sit side by side at 240px min width.
- **≥1024px:** the "why" band splits into two columns with a 64px gap. Steps go to three columns with a 40px gap. The form band centres. The close band lays out logo, text, and number in a row with 48px gaps.

Every tap target is at least 44px. Buttons are 56px tall, chips 48px, and inputs 52px.

## Elevation & Depth

The page is flat. Depth comes from the band colour changes and the photo overlay, not from shadows. Only one element is lifted: the floating text circle, because it sits above the page.

### Shadow Vocabulary
- **Float lift** (`box-shadow: 0 10px 28px rgba(46,33,10,.32)`): the floating text circle only.
- **Logo ring** (`box-shadow: 0 0 0 6px #cdc2b2`): a spread-only taupe ring around the round logo disc. It is a border, not elevation.

### Named Rules
**The Flat Bands Rule.** Cards, buttons, chips, and rows have no shadow at rest or on hover. Hover changes colour or outline only.

## Shapes

The shapes are soft, rounded, and borderless:
- Cards use 24px corners and the Facebook link row uses 20px.
- Buttons, chips, eyebrows, and step numbers are full pills or circles (999px / 50%).
- Fields use 10px corners.
- The brand mark, the logo disc, the arrow circle, and the floating button are all circles, echoing the round paw logo.

Borders appear only as state (the 2px transparent border that turns Paw Brown on hover or focus) or as the single hairline between claim rows. Icons are inline SVG strokes, 2.2–2.6px wide with round caps and joins.

## Components

### Buttons
Pill-shaped and confident, set in Cal Sans 18px.
- **Shape:** full pill (999px), 56px min height, 0 26px padding, 2px border.
- **Primary:** Caramel fill with Umber Ink text, used for "Get a free quote" and the form submit (full width in the form).
- **Ghost:** transparent with a 75% cream border and cream text, used on the hero only, beside the primary.
- **Hover (pointer devices only):** primary goes to Light Caramel; ghost gets a white border and a 10% white wash; the form submit also gets a 2px Paw Brown outline. On `:active` the button scales to 0.98. Transitions are 0.2s on colour and 0.12s on transform.
- **Icons:** 20px inline stroke SVGs with a 10px gap.

### Eyebrow Pills (house style, deliberate)
These are a quiet label above a few key headings, and they are Ellie's chosen calm-style device (2026-10-19).
- **Style:** 14px weight 500 system text, 9px 14px padding, pill shape, a 7% umber wash with a 7px Caramel dot before the text. On dark bands and the hero it uses cream text on a 14% white wash.
- **Use:** the hero, plus at most a few section heads (here: hero and the quote form). They are marked up as `<p>`, never as a heading.
- **Restraint:** no arrow, no hover state, no shadow, and never a full Caramel fill, so it can't be mistaken for a button.

### Chips
Chips are radio choices on the form.
- **Style:** Oat Field fill, Umber Ink 16px system text, pill shape, 48px min height and width, 0 18px padding, 2px transparent border.
- **Hover / Focus:** the border turns Paw Brown.
- **Selected:** Umber Ink fill with white text. When selected and focused, a 3px Paw Brown outline sits 3px off the chip, because a border on the ink fill would be invisible.

### Cards / Containers
- **Form card:** Card White, 24px corners, padding clamp(20px, 5vw, 32px), 22px gaps between fields, max 600px. No border, no shadow.
- **Link row:** Paw Brown fill, 20px corners, 76px min height, with a Cal Sans label beside a 28px Caramel icon. The trailing 44px arrow circle (12% white) fills with Caramel on hover or focus. Only the arrow changes; the row itself stays still.

### Inputs / Fields
- **Style:** Oat Field fill, 2px transparent border, 10px corners, 13px 14px padding, 52px min height (textarea 110px, vertical resize). Text is 16px Umber Ink, placeholders are Soft Umber, and the caret is Paw Brown.
- **Hover / Focus:** the border turns Paw Brown (0.15s). There is no glow.
- **Boundary:** Oat Field on Card White is only about 1.3:1. The field is found by its tint, its label, and the Paw Brown outline on hover or focus. Don't push the fill paler.
- **Error:** the border turns Error Red and stays red while focused. A plain-sentence message in 15px Error Red sits under the field.
- **Labels:** Cal Sans 17px with an optional "(optional)" in 14px Soft Umber system text.

### Navigation
A slim paper header with no menu:
- The round paw mark and a two-line wordmark (Cal Sans 20–24px over an 11px uppercase tracked subline) sit on the left.
- A tap-to-call number in Cal Sans 17–20px with a Burnt Caramel phone icon sits on the right.
- The footer is Deep Umber with the texture, holding the name, number, and a Facebook link (cream text, Caramel on hover).

### Focus
The global focus ring is a 3px outline offset 3px in Paw Brown. On the hero, brown, and deep bands and in the footer it switches to Caramel.

### Numbered Steps (signature)
Each step is a 48px Caramel disc with an Umber Ink Cal Sans 20px numeral (CSS counter), beside a cream Cal Sans title and a soft-cream line. They stack on phones and go to three columns at 1024px.

### Floating Text Circle (signature, house default)
- **Style:** a 60px Caramel circle with a 26px Umber Ink chat icon, fixed 16px from the bottom-right (safe-area aware). It carries the Float lift shadow.
- **Behaviour:** it opens a pre-filled `sms:`. It slides up from 120px below over 0.35s `cubic-bezier(.2,.8,.2,1)` once the hero is less than 15% visible, and hides while the quote form is on screen. When hidden it is `tabIndex=-1` and `aria-hidden`.
- **Limit:** there is only ever one circle, never a bottom bar.

### Hero H1 Bounce-In (signature, house default)
- **Motion:** the hero H1 only. JS splits it into letters inside nowrap word wrappers. Each letter goes from `opacity:0; translateX(50px)` to rest over 1s `cubic-bezier(.34,1.56,.64,1)`, staggered 20ms per letter.
- **Accessibility:** the H1 carries an `aria-label` and the letter wrappers are `aria-hidden`. After the last letter lands, the original HTML is restored.
- **Fallback:** it is skipped without JS and under reduced motion.

### Fade-Up (house default)
Elements marked `.rise` that start below the first screen rise 12px and fade in over 0.4s ease-out as they enter (IntersectionObserver, -8% bottom margin). Everything is visible at rest, without JS, and under reduced motion.

## Do's and Don'ts

### Do:
- **Do** take every dark tone from the logo's umber family (#523c16, #33260d) and keep the ground Warm Paper.
- **Do** use Caramel only as a fill, with Umber Ink text. Use Burnt Caramel (#8a520f) when the accent must be text on light.
- **Do** alternate full-bleed light and dark bands, and put the faint 135° line texture on Deep Umber surfaces only.
- **Do** set every heading, button, and form label in Cal Sans 400, adding `word-spacing: .08em` at 24px and below.
- **Do** keep forms on a white 24px card with Oat Field fills, pill chips, and Paw Brown outlines on hover and focus.
- **Do** keep eyebrow pills quiet and few: hero plus a couple of key headings, a `<p>` not a heading, no hover, no arrow.
- **Do** keep tap targets at 44px or larger and inputs at 16px or larger.
- **Do** limit motion to the hero H1 bounce-in, the single 12px fade-up, and the floating circle, all off under `prefers-reduced-motion`.
- **Do** gate hover styles behind `@media (hover:hover)` so taps don't leave them stuck on.

### Don't:
- **Don't** use green or mustard tones; the palette must stay distinct from NJ Scatman.
- **Don't** put white text on Caramel or Caramel text on paper (both fail contrast).
- **Don't** add shadows to cards, buttons, or rows. The floating circle is the only lifted element.
- **Don't** letter-animate any heading other than the hero H1.
- **Don't** add a second webfont or a bold Cal Sans weight.
- **Don't** replace the floating circle with a bottom bar, or show it while the form is on screen.
- **Don't** leave content at opacity 0 at rest, without JS, or under reduced motion.
