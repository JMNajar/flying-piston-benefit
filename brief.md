# Flying Piston Benefit — Landing Page Prompt
# SAVE THIS FILE IN VS CODE AS: brief.md
# THEN PASTE THE CONTENTS INTO claude.ai TO GENERATE YOUR index.html

---

## INSTRUCTIONS FOR CLAUDE

Create a single-file landing page called **index.html** for the **Flying Piston Benefit** silent art auction sign-up page.

The file must be completely self-contained — all CSS and JavaScript inside the one HTML file. No external files. No frameworks. No dependencies except Google Fonts.

---

## BRAND IDENTITY

- **Organization:** Flying Piston Benefit
- **Partners:** All Kids Bike (allkidsbike.org) | Gnarly Magazine | Paint Slinger Shootout | HorsepowerAI
- **Mission:** Bikers fund balance bikes for kindergarten classrooms across America. Over 250,000 kids have learned to ride — a skill for life.
- **Tone:** Gritty biker energy meets genuine heart. Bold. Loud. But ultimately joyful. Happy kids. Happy bikers. This is a cause worth celebrating.
- **Aesthetic:** Vintage rally poster meets modern web. Think Sturgis Buffalo Chip meets a charity gala. Raw edges, bold type, red-hot energy.

### Colors
- Primary Red: `#C8102E`
- Deep Red: `#9B0B22`
- Black: `#0D0D0D`
- Off-White / Parchment: `#F5F0E8`
- Gold Accent: `#F0A500`
- White: `#FFFFFF`

### Fonts (load from Google Fonts)
- Headlines: **Bebas Neue** — all-caps, bold, rally-poster feel
- Subheadings: **Barlow Condensed** weight 700 — tight and punchy
- Body: **Barlow** weight 400/500 — readable, clean
- Accent / Pull Quotes: **Special Elite** — typewriter grit

---

## PAGE SECTIONS — BUILD IN THIS ORDER

### 1. STICKY NAVIGATION BAR
- Background: `#0D0D0D` with 2px bottom border in `#C8102E`
- Left: Logo text "FLYING PISTON BENEFIT" — Bebas Neue, white, with "BENEFIT" in red
- Right navigation links: About | The Bikes | Events | Register Now
- "Register Now" is a red pill button that scrolls to the sign-up form
- Sticky on scroll, slight backdrop blur

---

### 2. HERO SECTION
- Full-viewport height
- Background: Deep black with a radial gradient of dark red (`#3D0010`) glowing from center — like a spotlight on a dark stage
- Add a subtle halftone dot texture overlay (CSS, no image needed) for that vintage rally-poster feel
- Two-column layout:
  - **Left column:** Text content
  - **Right column:** Large bold stat display

**Left column content:**
- Small eyebrow text (red, Barlow Condensed, uppercase, letter-spaced): `FROM BIDDING WARS TO FIRST RIDES`
- H1 headline (Bebas Neue, 96px, white, line-height 0.9):
  ```
  SILENT
  ART AUCTION
  ```
- Subheadline (Barlow Condensed, 28px, gold `#F0A500`):
  `Daytona Beach • March 2025 | Sturgis • August 2025`
- Body copy (Barlow, 18px, off-white, max-width 480px):
  "Every bid you place puts a balance bike in a kindergarten classroom. Flying Piston Benefit and All Kids Bike have helped over 250,000 kids learn to ride across America. This is how it keeps rolling."
- Two CTA buttons side by side:
  - Primary: Red fill, white text — "CLAIM MY SPOT" → scrolls to sign-up form
  - Secondary: White outline, white text — "SEE HOW IT WORKS" → scrolls to mission section

**Right column content:**
- Bold stat card with a dark red border and gold glow, centered:
  ```
  250,000+
  KIDS RIDING
  ACROSS AMERICA
  ```
  Font: Bebas Neue. Number in gold. Text in white. Small caption below in red: "Powered by Flying Piston Benefit & All Kids Bike"

---

### 3. SCROLLING MARQUEE BAR
- Full width, red background `#C8102E`
- White text, Bebas Neue, 20px
- Gold diamond dividers `◆` between items
- Infinite scroll animation (CSS only, left-to-right)
- Items: `DAYTONA BEACH 2025` ◆ `STURGIS 2025` ◆ `SILENT ART AUCTION` ◆ `250,000+ KIDS RIDING` ◆ `ALL KIDS BIKE` ◆ `FREE TO REGISTER` ◆ `BIKES FOR KINDERGARTNERS` ◆ `FLYING PISTON BENEFIT` ◆

---

### 4. MISSION SECTION — "IT STARTS WHERE LEGENDS RIDE"
- Background: Off-white `#F5F0E8`
- All text in black/dark
- Section headline (Bebas Neue, 60px, black): `WHERE LEGENDS RIDE FOR KIDS`
- Body paragraph (Barlow, 17px, dark gray):
  "The Flying Piston Benefit was born at the world's biggest motorcycle rallies — Daytona Bike Week and the Sturgis Buffalo Chip. Thousands of riders gather, art goes on the block, and every dollar raised goes straight to putting All Kids Bike balance bikes into kindergarten P.E. programs nationwide. No kid left behind. No training wheels needed."
- Three stat cards in a row (dark background cards, red top border, white text):
  - `$0 UPFRONT` — "Schools receive bikes at zero cost"
  - `K–5 PROGRAMS` — "Integrated into school PE curriculum"
  - `250,000+ KIDS` — "Have learned to ride across America"
- Cards have a subtle red glow on hover

---

### 5. THE EVENTS SECTION — "TWO RALLIES. ONE MISSION."
- Background: `#0D0D0D` (dark)
- Section headline (Bebas Neue, 60px, white): `TWO RALLIES. ONE MISSION.`
- Two large side-by-side event cards. Each card:
  - Dark gray background `#1A1A1A`
  - Red left border (4px)
  - Gold accent label at top (Barlow Condensed, uppercase): EVENT 01 / EVENT 02
  - Event name (Bebas Neue, 48px, white)
  - Date (Barlow Condensed, 24px, red)
  - Location (Barlow, 16px, off-white)
  - Short description
  - "REGISTER FOR THIS EVENT" button — red, full width of card

**Card 1 — Daytona:**
- Label: `EVENT 01`
- Name: `DAYTONA BEACH BIKE WEEK`
- Date: `MARCH 2025`
- Location: Daytona Beach, Florida
- Description: "The original. The iconic. The sunrise rally where the first bids are placed and the first bikes are won. Join thousands of riders who show up for the kids."
- Button: "REGISTER FOR DAYTONA"

**Card 2 — Sturgis:**
- Label: `EVENT 02`
- Name: `STURGIS BUFFALO CHIP`
- Date: `AUGUST 2025`
- Location: Sturgis, South Dakota
- Description: "The legendary rally that never sleeps. The Flying Piston Benefit takes over the art auction floor and riders dig deep. This one's for the history books."
- Button: "REGISTER FOR STURGIS"

---

### 6. HOW IT WORKS SECTION
- Background: Off-white `#F5F0E8`
- Headline (Bebas Neue, 60px, black): `HOW YOUR BID CHANGES A KID'S LIFE`
- Four horizontal step cards, numbered 01–04. Each card: white background, red step number in top-left corner (Bebas Neue, 80px, very light red as background number), black text:
  - `01` — **YOU SHOW UP** — "Register for the silent art auction at Daytona or Sturgis. It's free to attend."
  - `02` — **YOU BID** — "Original artwork from legendary artists goes on the block. Place your bid. Win something amazing."
  - `03` — **WE BUY BIKES** — "Every dollar raised buys All Kids Bike balance bikes for kindergarten classrooms across the U.S."
  - `04` — **KIDS RIDE** — "A child who couldn't balance yesterday is riding free today. That's the moment that changes everything."

---

### 7. SIGN-UP FORM SECTION
- Background: `#0D0D0D` with red radial glow from center bottom
- Large headline (Bebas Neue, 72px, white): `CLAIM YOUR SPOT`
- Subhead (Barlow Condensed, 24px, gold): `Register for the 2025 Silent Art Auction`
- Two-column layout:
  - **Left:** Form
  - **Right:** Benefit list

**Form fields (dark input styling — `#1A1A1A` background, red border on focus):**
- First Name (text input)
- Last Name (text input)  
- Email Address (email input)
- Phone Number (tel input)
- Which event? (select dropdown): Both Events | Daytona Beach — March 2025 | Sturgis — August 2025
- How did you hear about us? (select): Word of mouth | Social media | Gnarly Magazine | Paint Slinger Shootout | Another biker told me | Other
- Are you interested in donating artwork? (radio): Yes, tell me more | No, just attending
- Submit button: Full width, red background, white text — **"I'M IN — REGISTER ME NOW"** — Bebas Neue, 28px
- Fine print below button: "No spam. Ever. Just rally updates and bike news."

**Right column — benefit list (gold checkmarks, white text):**
- ✔ Free to register — no entry fee
- ✔ Access to exclusive silent auction artwork
- ✔ Your bid directly funds kindergarten bikes
- ✔ Updates from both Daytona and Sturgis events
- ✔ Join 250,000+ kids' worth of good karma
- ✔ Featuring legendary builders & artists

---

### 8. SOCIAL PROOF / QUOTE SECTION
- Background: Deep red `#9B0B22`
- Large opening quote mark (Bebas Neue, 200px, semi-transparent darker red)
- Pull quote (Special Elite font, 32px, white, centered, max-width 700px):
  `"We sent one email. One post. Orders from riders we'd never met. The kids just kept riding."`
- Attribution (Barlow Condensed, 18px, gold): `— All Kids Bike Partner School, Kansas City`
- Below: three small logos in a row (text placeholders): Gnarly Magazine | Paint Slinger Shootout | All Kids Bike | HorsepowerAI

---

### 9. FOOTER
- Background: `#0D0D0D`
- Red top border 3px
- Three columns:
  - **Col 1:** Logo + tagline: "Flying Piston Benefit — Where legends ride for kids."
  - **Col 2:** Quick links — About | The Bikes | Daytona Event | Sturgis Event | Register | All Kids Bike (allkidsbike.org)
  - **Col 3:** "Powered By" — list the four partner logos as styled text: Gnarly Magazine | Paint Slinger Shootout | All Kids Bike | HorsepowerAI
- Bottom strip: copyright line centered, small text, dark gray

---

## TECHNICAL REQUIREMENTS

- Single file: `index.html` — CSS in `<style>` tag in `<head>`, JS in `<script>` tag before `</body>`
- Mobile responsive — works on phone, tablet, desktop
- Smooth scroll on all anchor links
- Form does NOT need a backend — on submit, hide the form and show a thank-you message:
  ```
  "YOU'RE IN! 🤘 We'll see you at the rally."
  ```
- Add scroll-triggered fade-in animation (IntersectionObserver) for each section as it enters the viewport
- The marquee bar must loop infinitely and smoothly with CSS animation only
- Sticky nav changes background opacity on scroll (more opaque as user scrolls down)
- All hover states on buttons: slight scale up (1.03) + brightness increase
- Image placeholders: use styled `<div>` elements with background gradients — NO broken `<img>` tags

---

## WHAT SUCCESS LOOKS LIKE

When this page is done it should feel like: you just walked into the Sturgis Buffalo Chip, spotted a charity booth run by the coolest bikers you've ever met, and realized they were doing something genuinely beautiful for kids. Bold. Loud. But full of heart.

---
# END OF PROMPT — COPY EVERYTHING ABOVE THIS LINE AND PASTE INTO CLAUDE.AI