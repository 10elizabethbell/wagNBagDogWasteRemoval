# Wag N' Bag Dog Waste Removal — handoff at ~60%

**Live:** https://10elizabethbell.github.io/wagNBagDogWasteRemoval/ · **Repo:** https://github.com/10elizabethbell/wagNBagDogWasteRemoval · **Built:** 2026-10-21 from Muse brief (run 2026-10-21, Ocean County Home Helpers ad post) · **Call Sheet:** site URL set

## What's built
- One page, in this order: header, hero, "A clean yard means more tail wags." (three short promises and the Facebook row), How it works (3 steps, deep band), free-quote form, closing band with the full logo and big number, footer.
- **Palette, from the logo:**
  - umber paw #523c16 for the hero overlay and closing band
  - deeper umber #33260d with the line texture for How it works and the footer
  - warm paper #f7f3ec as the page ground
  - caramel #e8a64a as the one accent fill (#8a520f when it has to be text on light)
  - taupe #cdc2b2, the logo's stripe colour, as the ring around the logo
- **Hero:** their own yard photo, a frame from their Facebook video ad, under a brown overlay.
  - On phones the dog walks in a clear strip under the buttons.
  - On desktop the dog sits to the right of the headline.
  - The wicker chair and a piece of litter on the lawn are cropped or painted out.
- **H1:** their tagline, "We scoop the poop so you don't have to." It bounces in letter by letter. The rest of the page uses one quiet fade-up.
- **Contact:**
  - Tap-to-call (609) 467-4064 in the top-right corner of the header.
  - "Get a free quote" (filled) jumps to the form; "Text us" (outlined) opens a pre-written text.
  - The 60px floating text circle shows after the hero and hides while the form is on screen.
  - The form asks for name (required), dogs, how often, town and a note, then opens Messages with the text written out. If Messages doesn't open, a fallback line with the number appears.
- **Facebook:** "Click to see more of our work." under the promises, and in the footer.
- **Icons and preview:** favicon and home-screen icon use the logo's paw circle. The og:image (`og.jpg`, 1200×630) shows the headline, the logo and the yard.

## Assumptions I made
- **Caramel accent:** inferred, not in the logo. The calm style needs one warm fill colour; the logo only has umber and taupe. I picked caramel to sit with the umber and stay well away from NJ Scatman's green and mustard.
- **"We" voice:** their own captions say "we".
- **"On a regular schedule" and "All season long, cold days too":** paraphrased from their ad ("Get on our schedule today and enjoy a cleaner yard all season long").
- **"So it never has a chance to pile up"** (step 2): inferred from "get on our schedule". It describes regular visits; it isn't a stated frequency.
- **Form choices:** "Every week / Every other week / Not sure yet" and "1 / 2 / 3 / 4+" dogs are questions for the customer to answer, not plans the business has said it offers. Confirm or change them with the owner.
- **Hero photo:** it shows a house and a camper in the background, heavily darkened. I assumed this is their own or a willing customer's yard, since they posted it publicly in their ad. No faces, plates or house numbers are visible.

## Placeholders and gaps
- **No place name in the H1 and no service area on the page.** The brief says "Do NOT publish a location". This breaks the calm style's "place in the H1" rule on purpose. The closing band says "Not sure we come to your street? Call or text and ask."
- **No email:** none exists, so the footer has none.
- **Not on the page, because none were found:** prices, reviews, owner name, hours, years in business.
- **Photos:** only one exists (a video-ad frame). There's no work gallery and no before/after. The hero is 1080px wide, so it's a little soft on big desktops; the dark overlay hides most of it.
- **Wordmark:** their logo is square with script lettering, so the header uses the paw mark plus a Cal Sans "Wag N' Bag / Dog Waste Removal". The full logo is in the closing band.

## Questions for the owner
1. Which towns do you cover, and are you OK with listing them? A place in the headline helps people find you.
2. Weekly, every other week, one-time cleanups: which do you offer, and do you publish prices?
3. Your first name (and a photo of you or the crew)? People trust a name.
4. Any photos of yards you've cleaned, your gear, or happy dogs? And the original video from your ad?
5. Do you want an email in the footer?
6. Any reviews from customers we can quote, word for word?
7. Days and hours you work?

## Ideas not built (yours to pick)
- **Runner-up signature motion** (opt-in), worlds from the trade:
  1. Grass that sways and parts under your finger.
  2. Paw prints that trail the pointer and fade.
  3. Falling autumn leaves and first snow, which fits their "cold weather is coming" hook.
  4. A pooper-scooper that sweeps the hero clean as you drag.
  5. Taupe stripes from the logo drifting like a lawn-mowing pattern.

  Best fit: **grass that parts under your finger.** It's their actual job surface and reads instantly.
- **Delight:** paw-print step markers instead of numerals, and a tiny paw "sent" reward after the form opens Messages.
- **Proof section:** stills from their video ad (or the video itself) once the owner shares it.
- **Ellie's chosen features Impeccable flagged; all kept on purpose:**
  - eyebrow pills (craft floor: no eyebrows)
  - the H1 bounce-in (overshoot easing; makes visitors wait for the headline)
  - the floating circle (duplicates "Text us")
  - the diagonal band texture (decorative stripes)
  - the cream paper ground ("cream palette" reflex). The tint comes from the logo's warm whites.
- **Detector "flat type hierarchy":** left standing. It counts the small UI sizes (11–20px). The headings are 30–80px clamps it doesn't see.
- **Process note:** the finish reviewer asked for a concept-roll seed key on the direction contract. None was used; the calm house style fixes the structure.
- **Copy alternatives:**
  - Hero promise: "Stay warm inside. We'll handle the yard bombs."
  - Facebook row: "See more of our work on Facebook" (the sweep preferred it to "Click").

## Not verified
- Real-device touch, and the real SMS handoff on iOS and Android, including inside Facebook's in-app browser. Tested in headless Chromium and WebKit only: the pre-filled body decodes correctly and the form composes the right message.
- How the hero photo looks on a real 3x phone screen (it's upscaled about 1.5x on phones).
- Frame rate of the bounce-in on old phones.
