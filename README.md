[README.md](https://github.com/user-attachments/files/26370731/README.md)
# Museum Exhibit Companion
### DSIGN241-26A — Aspects of Web Design 

A digital companion website for a temporary Pop Art museum exhibit, designed to be accessible and provide layered content for a broad audience.

---

## Team
- Andrew Graham
- Mia Wang
- Rowan Lea
- Seven Liu
- Toby Childs

---

## Project Brief
Assignment 1 part A:
Design a digital companion website for a temporary Museum Exhibit that is accessible and provides layered content for children, general public, and more curious users seeking deeper detail.
Used: Figma and Adobe Illustrator.

Assignment 1 part B:
Build out a Website using a pre-existing template. Add CSS and HTML to continue the design styles.

Assignment 2 — Refactoring (Part A: Investigate, Part B: Implementation)
A: Investigate Tailwind CSS and Bootstrap, rebuild part or all of a page and understand the context you might use each framework.
B: Pick a framework and build out the previously templated CSS site.

---

## Concept & Rationale
By team consensus the scope was narrowed to a **Pop Art exhibition** using a **mobile-first** approach to layout and display.

The design uses contemporary web tools to allude to **four colour process printing techniques**, with a bold maximalist aesthetic to encourage engagement.

---

## Design System

### Colour Palette
| Colour | Hex | RGB |
|---|---|---|
| Red | `#EE2B2F` | R237, G28, B36 |
| Cyan | `#00AEEF` | R0, G174, B239 |
| Yellow | `#FFF200` | R255, G242, B0 |
| Magenta | `#EC008C` | R236, G0, B140 |
| Cream | `#FDF5E6` | R255, G244, B231 |
| Black | `#231F20` | R35, G31, B32 |

### Typography
| Role | Font | Size |
|---|---|---|
| h1 | Bangers | — |
| h2 | Bangers | — |
| h3 | Roboto | 28pt |
| h3 | Roboto | 21pt |
| p | Roboto | 16pt |

**Bangers** evokes a handmade comic book appearance for headings. **Roboto** provides readability for body copy.

---

## Process
- Developed style guide in **Adobe Illustrator**
- Translated design tokens (colours, typography, layout) into **CSS**
- Applied to provided HTML boilerplate
- Shared component library built in **Figma**

### Figma File
[View Figma Design](https://www.figma.com/design/L9u50g8OCdZVPaekSDKpCc/DSIGN241-Assignment1?node-id=0-1&t=26qcDjfgULjEdB5M-1)

---

## UI Components
- **Layout** — Mobile-first carousel with swipeable content panels (not implemented in the first iteration, still at the concept level)
- **Content** — Styled speech bubbles linking content to images
- **Display Boxes** — High contrast irregular shaped boxes with dark text
- **Icons** — Shared icon set created in Figma
- **Buttons** — Hover and inactive states styled to match aesthetic

---

## Technologies Used
- HTML
- CSS
- Adobe Illustrator (style guide)
- Google Fonts (Bangers, Roboto)
- Figma (component library)

---


**Assignment:** Assignment 2 — Style Guide (Part A: Proposal, Part B: Implementation)

## Technical Implementation & Refactoring
To ensure the "Pop Art" aesthetic remained mathematically consistent across the 3-column exhibit grid, I implemented several advanced front-end strategies:

- **Design Token Integration:** Translated Figma styles into a custom `tailwind.config.js`, enabling a "Single Source of Truth" for brand colors like `pop-red` and the `Bangers` typeface.
- **Structural Stewardship:** Refactored the DOM from a nested CSS architecture to a flattened Flexbox model. This enabled the use of `flex-grow` to normalize container heights across grid rows, ensuring a perfectly aligned horizontal baseline.
- **Automated Quality Control:** Utilized the **Prettier** formatter with the **Tailwind CSS plugin** to automate class sorting and maintain code legibility throughout the build.

"The primary goal of this refactor was not merely aesthetic, but an investigation as per the assignment brief.
By migrating the Museum Companion index page to Tailwind CSS I gained an understanding of the application of this framework.
I did not start with mobile first because I needed to gain some understanding of the framework first.