# Portfolio asset checklist

This checklist reflects the current portfolio structure after the Scroll & Tell merge and the latest audit cleanup. It is implementation guidance for the current repository, not a historical upload plan.

## Current implementation

| Area | Current state |
|---|---|
| Project cards | Two cards remain: MathDesk and Scroll & Tell. The older AI Content Automation Pipeline and Short-Form Workflow cards are no longer rendered in the Projects grid. |
| AI Builds cards | Two cards remain: MathDesk and Scroll & Tell Automation. The Scroll & Tell card has a direct `Read case study →` modal action and a secondary `Visit Substack →` external action. |
| MathDesk status | The existing card wording is intentionally preserved while the app is being revised. Do not rewrite feature claims or replace its screenshots without checking the current build first. |
| Scroll & Tell workflow | The case study distinguishes the five-stage content-preparation process from the four-module n8n architecture. It must not imply validated end-to-end autonomous publishing. |
| Certifications | Four primary rows are shown in the framed credentials panel, with compact additional certificates below. Badge images are public brand/badge artwork, not private credential documents. |

## Referenced assets

All paths below are relative to the repository root. Confirm that replacements match the current portfolio copy and do not expose private IDs, tokens, account data, or credentials.

### Project cards and reel

| File | Current use |
|---|---|
| `images/projects/banner-mathdesk.png` | MathDesk Projects card banner and MathDesk project modal hero asset |
| `images/projects/banner-scrolltell.png` | Scroll & Tell Projects card banner and project modal hero asset |
| `images/projects/1.png` through `images/projects/4.png` | Homepage project reel visuals |

Project card banners are displayed edge-to-edge with `object-fit: cover`; cropping is intentional so the artwork fills the frame.

### AI Builds

| File | Current use |
|---|---|
| `images/aibuilds/mathdesk-hero.png` | MathDesk AI Builds card visual |
| `images/aibuilds/scrolltell-automation-1.png` | Scroll & Tell conversation/story-intake visual |
| `images/aibuilds/scrolltell-automation-2.png` | Scroll & Tell n8n automation visual |

The AI Builds card visuals should remain current with the working projects. Replace an image only after checking that it does not show an obsolete interface, broken feature, private information, credential, token, or account data.

### Certification badges

| File | Current use |
|---|---|
| `images/certs/kodekloud-badge.png` | n8n: Zero to Hero, KodeKloud |
| `images/certs/upgrad-badge.png` | Advanced Prompt Engineering with ChatGPT, upGrad |
| `images/certs/googlecloud-badge.png` | Introduction to Generative AI, Google Cloud |
| `images/certs/efset-badge.png` | EF SET English Certificate, C2 Proficient |
| `images/certs/canva-essentials-badge.png` | Additional Canva Essentials certificate |
| `images/certs/canva-graphic-badge.png` | Additional Graphic Design Essentials certificate |
| `images/certs/google-digital-badge.png` | Additional Google Digital Garage certificate |

Use public badge or brand artwork rather than screenshots containing personal certificate IDs unless those IDs are intentionally public.

### Project-detail galleries

The project articles reference the following local image groups. Keep filenames stable when replacing screenshots so the article markup does not need to change.

- MathDesk: `images/projects/mathdesk-visual-1.png`, `mathdesk-visual-2a.png` through `mathdesk-visual-2d.png`, `mathdesk-visual-3a.png` through `mathdesk-visual-3d.png`, `mathdesk-visual-4a.png` through `mathdesk-visual-4d.png`, `mathdesk-visual-5.png` through `mathdesk-visual-8b.png`.
- Scroll & Tell: `images/projects/scrolltell-visual-1a.png` through `scrolltell-visual-1f.png`, `scrolltell-visual-2a.png` through `scrolltell-visual-2d.png`, `scrolltell-visual-3.png`, and `scrolltell-visual-4a.png` through `scrolltell-visual-4d.png`.
- Scroll & Tell workflow support: `images/projects/shortform-visual-1.png` through `shortform-visual-4.png` and `images/projects/pipeline-visual-1.png` through `pipeline-visual-6.png`.

For every gallery replacement:

1. Match the screenshot to its figure caption and the current workflow.
2. Redact tokens, credentials, private account data, and personal information.
3. Keep text-heavy screenshots legible; do not crop away the evidence needed by the caption.
4. Verify that the image loads locally and on GitHub Pages.

## External-link QA

Test these destinations from the deployed site after each content or link change:

- LinkedIn: `https://www.linkedin.com/in/chelseaandreadominguez/`
- GitHub profile: `https://github.com/Tselseya`
- MathDesk demo: `https://app.mathdesk.page.gd/`
- Scroll & Tell Facebook: `https://www.facebook.com/thescrolltell`
- Scroll & Tell Instagram: `https://www.instagram.com/thescrolltell/`
- Scroll & Tell TikTok: `https://www.tiktok.com/@thescrolltell`
- Scroll & Tell YouTube: `https://www.youtube.com/@thescrolltell`
- Substack homepage: `https://chelseaandrea.substack.com/`
- Four primary certificate links in `index.html`

The Substack destination is a publication homepage, so the external CTA says `Visit Substack →`; the separate `Read case study →` action opens the in-portfolio article.

## Final QA checklist

- [ ] Hard-refresh the deployed site after Pages publishes.
- [ ] Check 320–360 px, 375–430 px, 768 px, 1280–1440 px, and 1600+ px widths.
- [ ] Check light and dark themes.
- [ ] Confirm Projects images fill their frames without unintended gutters.
- [ ] Confirm AI Builds cards remain readable on mobile, adapt to added cards, and expose both Scroll & Tell actions without clipping or nested card scrolling.
- [ ] Confirm every navigation item opens the intended page.
- [ ] Confirm the Scroll & Tell card exposes only `Visit Substack →` as its external CTA.
- [ ] Confirm project cards still open their detail modal and the modal can close and reopen.
- [ ] Confirm keyboard focus indicators and reduced-motion behavior remain usable.
- [ ] Check for broken images, missing fonts, clipped headings, horizontal overflow, and console 404s.
