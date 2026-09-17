# Portfolio asset checklist

This checklist matches the updated `index.html` against the repository at commit `9a3c735`. The updated HTML references local assets that are not currently present. Existing fonts, `favicon.png`, `images/og-image.png`, and the tool SVG files already match and do not need to be uploaded again.

## Asset status

| Status | Count | Notes |
|---|---:|---|
| Already present | 29 | Four Poppins font files, favicon, `images/og-image.png`, and 23 tool SVGs |
| Added from existing repository asset | 1 | `profile.png`, copied from the existing `portfolio.png` portrait |
| Still needed | 44 | Project reel/thumbnail assets and expanded project-detail screenshots |

## Still-needed files

All paths below are relative to the repository root. Upload the files using exactly these names so the updated HTML resolves them without code changes.

### Project reel and card thumbnails

| File to upload | Used in updated HTML | How and where to get it |
|---|---|---|
| `images/projects/1.png` | Project reel and MathDesk card thumbnail | Export a 16:9 screenshot of the MathDesk landing page; use the same image as the MathDesk card cover. |
| `images/projects/2.png` | Project reel and Scroll & Tell card thumbnail | Export a 16:9 screenshot of the Scroll & Tell experience or its primary visual. |
| `images/projects/3.png` | Project reel and AI Content Automation Pipeline card thumbnail | Export a 16:9 screenshot of the n8n pipeline canvas or pipeline overview. |
| `images/projects/4.png` | Project reel and Short-Form Workflow card thumbnail | Export a 16:9 screenshot of the five-stage workflow overview. |

Recommended export: PNG, approximately 1600–2400 px wide, with the important content near the top because the card uses `object-position: top`.

### AI builds section

| File to upload | Placement | How and where to get it |
|---|---|---|
| `images/aibuilds/mathdesk-hero.png` | AI builds → MathDesk visual | Capture the live MathDesk homepage at `https://mathdesk.vercel.app/` or the current MathDesk deployment, then crop/export the hero area. |
| `images/aibuilds/scrolltell-automation-1.png` | AI builds → Scroll & Tell visual 1 | Export a screenshot of the Scroll & Tell Instagram/conversation flow from the project’s working files or live demo. |
| `images/aibuilds/scrolltell-automation-2.png` | AI builds → Scroll & Tell visual 2 | Export a screenshot of the corresponding n8n automation canvas from the Scroll & Tell workflow. |
| `images/aibuilds/pipeline-architecture.png` | AI builds → AI Content Automation Pipeline visual | Open the n8n workflow, fit the full canvas to the window, and export a legible PNG of the pipeline architecture. |

### Certification badges

| File to upload | Placement | How and where to get it |
|---|---|---|
| `images/certs/upgrad-badge.png` | Certifications → upGrad | Download the badge from the upGrad certificate or learner profile. The updated HTML also contains a direct certificate URL for reference. |
| `images/certs/googlecloud-badge.png` | Certifications → Google Cloud | Download the badge from the Google Cloud Skills Boost achievement/certificate page. |
| `images/certs/kodekloud-badge.png` | Certifications → KodeKloud | Download the badge from the KodeKloud profile or course-completion page. |
| `images/certs/efset-badge.png` | Certifications → EF SET | Download the score/certificate badge from the EF SET certificate page. |
| `images/certs/canva-essentials-badge.png` | Certifications → Canva Essentials | Download the certificate/badge from Canva or the course provider where it was issued. |
| `images/certs/canva-graphic-badge.png` | Certifications → Canva Graphic Design | Download the certificate/badge from Canva or the course provider where it was issued. |
| `images/certs/google-digital-badge.png` | Certifications → Google Digital Garage | Download the badge/certificate from the Google Digital Garage credential page. |

Use PNG exports with transparent backgrounds where available. Do not use screenshots containing private credential IDs unless you intend those IDs to be public.

### MathDesk project detail gallery

| Files to upload | Placement | How and where to get them |
|---|---|---|
| `images/projects/mathdesk-visual-1.png` | MathDesk modal: opening visual | Capture the MathDesk homepage/hero from the live app. |
| `images/projects/mathdesk-visual-2a.png` through `mathdesk-visual-2d.png` | MathDesk modal: input modes/gallery | Capture the four input-mode states shown in the modal copy: typing, handwriting, camera, and image input. |
| `images/projects/mathdesk-visual-3a.png` through `mathdesk-visual-3d.png` | MathDesk modal: solving/explanation states | Capture the four step-by-step solving or explanation states represented in the project narrative. |
| `images/projects/mathdesk-visual-4a.png` through `mathdesk-visual-4d.png` | MathDesk modal: practice/features gallery | Capture the four practice, calculator, chat, or related feature screens used by the project story. |
| `images/projects/mathdesk-visual-5.png` | MathDesk modal: supporting visual | Capture the specific feature or result screen corresponding to the fifth visual in the modal. |
| `images/projects/mathdesk-visual-6.png` | MathDesk modal: supporting visual | Capture the sixth visual from the MathDesk walkthrough. |
| `images/projects/mathdesk-visual-7.png` | MathDesk modal: supporting visual | Capture the seventh visual from the MathDesk walkthrough. |
| `images/projects/mathdesk-visual-8a.png` and `mathdesk-visual-8b.png` | MathDesk modal: final gallery | Capture the two final screens/results used to close the MathDesk case study. |

The exact visual-to-caption mapping is defined by the `<figure>` blocks in `index.html` around the MathDesk article. Use those captions as the final authority when selecting screenshots.

### Scroll & Tell project detail gallery

| File to upload | Placement | How and where to get it |
|---|---|---|
| `images/projects/scrolltell-visual-1a.png` through `scrolltell-visual-1f.png` | Scroll & Tell modal: opening/gallery sequence | Export the six primary product/content screens from the Scroll & Tell project. |
| `images/projects/scrolltell-visual-2a.png` through `scrolltell-visual-2d.png` | Scroll & Tell modal: workflow/content sequence | Export the four supporting workflow or content-transformation screens. |
| `images/projects/scrolltell-visual-3.png` | Scroll & Tell modal: supporting visual | Export the screen matching the third visual in the modal article. |
| `images/projects/scrolltell-visual-4a.png` through `scrolltell-visual-4d.png` | Scroll & Tell modal: closing gallery | Export the four final case-study screens. |

The existing repository has older Scroll & Tell screenshots in `images/scrolltell-*.png`; reuse them only if they match the updated modal captions and crop requirements. Otherwise export fresh screenshots from the project files/live demo.

### AI pipeline project detail gallery

| File to upload | Placement | How and where to get it |
|---|---|---|
| `images/projects/pipeline-visual-1.png` through `pipeline-visual-6.png` | AI Content Automation Pipeline modal | Open the n8n workflow and the related content-generation outputs, then export six legible screenshots matching the modal’s six figure captions. Prefer one workflow overview, one intake example, one generation output, one approval step, one distribution step, and one end-to-end result. |

### Short-form workflow project detail gallery

| File to upload | Placement | How and where to get it |
|---|---|---|
| `images/projects/shortform-visual-1.png` | Short-Form Workflow modal: opening visual | Capture the source/input stage shown in the article. |
| `images/projects/shortform-visual-2.png` | Short-Form Workflow modal: five-stage pipeline | Export a diagram or screenshot showing Extract → Script → Caption → CTA → Hashtags. |
| `images/projects/shortform-visual-3a.png` through `shortform-visual-3c.png` | Short-Form Workflow modal: prompt/output examples | Export the raw → extracted, extracted → script, and script → caption examples. |
| `images/projects/shortform-visual-4.png` | Short-Form Workflow modal: connection to next project | Export the visual showing the five-stage content workflow leading to the modular n8n automation. |

## Existing assets that were not renamed

The repository already contains older assets such as `images/mathdesk-home.png`, `images/mathdesk-chat.png`, `images/mathdesk-calculator.png`, `images/mathdesk-solve.png`, and several `images/scrolltell-*.png` files. The updated HTML does not reference those filenames directly, so they were left untouched. They can be reused as source material when creating the new named assets above.

## Upload workflow

1. Capture or export each screenshot from the corresponding live project, n8n canvas, credential page, or design file.
2. Rename it to the exact path in this checklist.
3. Keep sensitive certificate details out of public screenshots.
4. Test the site locally and check the browser console for 404 errors before publishing.
5. Commit the assets and push them to `main` together with the updated `index.html`.
