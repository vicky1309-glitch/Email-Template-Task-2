# The Meridian Summit — Event Invitation Email 

A premium, hand-designed HTML event invitation email — built for **Task 2: Email Template**. Styled as a luxury private summit invite, with a charcoal-and-gold editorial aesthetic, custom inline SVG illustrations, and print-invitation-inspired details like a gold frame border, wax-seal-style crest, and QR-code graphic.

---

##  Preview

Open [`5-invite-meridian-summit.html`](./5-invite-meridian-summit.html) directly in your browser to preview the full template.

>  Tip: For the most accurate preview, test inside [Litmus](https://litmus.com) or [Email on Acid](https://www.emailonacid.com), or send yourself a test email through Gmail/Outlook — real inbox rendering can differ slightly from a browser preview.

---

##  Features

- **Gold outer frame** — the entire email sits inside a thin gold border, like a printed invitation card
- **Monogram pattern strips** — repeating diamond patterns at the top and bottom, mimicking foil-stamped card stock
- **Ornamental crest** — a double-ring emblem with a star, used in place of a plain logo mark
- **Rooftop night-scene illustration** — string lights, a moon, candlelit tables, and a distant skyline
- **Ticket-style detail card** — date, venue, and dress code laid out like a physical ticket stub, complete with a dashed "perforated" divider
- **Attendee social proof** — a stacked-avatar graphic ("128 guests already attending")
- **QR-code-style graphic** — decorative, reinforcing the physical-ticket feel
- **Drop-cap opening paragraph** — a large serif initial letter, a classic editorial/print technique
- **Full evening agenda timeline** — vertical timeline with connected gold ring markers, from welcome reception through rooftop mingling
- **Speaker lineup** — three featured speakers, each with a custom illustrated avatar and title
- **Testimonial block** — a quote from a past attendee with a large gold quotation mark
- **Sponsor strip** — "Presented With Support From" partner names
- **Fully responsive** — stacks to a single column on mobile (<600px)

---

##  Built With

- Pure **HTML** + **inline CSS** (email-safe, no external stylesheets)
- **Table-based layout** — the email industry standard, since most clients strip modern CSS
- **Inline SVG** for every illustration, icon, and ornamental divider — no external image hosting required
- Media queries for responsive stacking on mobile clients that support them

---

##  File Structure

```
├── 5-invite-meridian-summit.html   # Main email template file
└── README.md                        # This file
```

---

##  Design System

| Element         | Value                              |
|-----------------|-------------------------------------|
| Background      | `#211b17` (near-black charcoal)     |
| Card background | `#f7f2e9` (warm ivory)               |
| Gold accent     | `#c9a24b`                            |
| Muted text      | `#9c9186` / `#8f8065`                |
| Dark text       | `#2b2117`                            |
| Headline font   | Georgia / Times New Roman (serif)   |
| Body font       | Arial / Helvetica (email-safe)      |

---

##  Email Client Compatibility Note

This template uses **inline SVG** for all illustrations and ornamental details, which renders beautifully in browsers, Apple Mail, and most modern Gmail clients. However, **Outlook (desktop) and some older email clients don't support inline SVG**. For a production send where guaranteed rendering across every client matters, export the SVGs (skyline, crest, agenda icons, speaker avatars, QR graphic) as PNG images and host them externally (e.g. via a CDN) instead of inlining them.

---

##  How to Customize

1. Replace the event name, date, venue, and dress code in the ticket detail card
2. Swap out the three speaker names/titles and their avatar colors
3. Update the testimonial quote and attribution, or remove the block entirely if this is a first-time event
4. Replace `#` placeholder `href`s with your real RSVP link
5. Update the footer host name and address — most ESPs require a physical mailing address for compliance
6. Adjust the gold/charcoal palette in the `<style>` block if a different brand color is needed
