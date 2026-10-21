---
name: JAW Creations
description: A personal exhibition of custom artwork and handmade designs.
colors:
  paper: "#f8f3e9"
  plum: "#523d61"
  deep: "#34263e"
  pink: "#efc2cb"
  sage: "#d4d7bf"
  ink: "#342b38"
  muted: "#665a68"
  line: "#d8cbd5"
  white: "#fffdf8"
typography:
  display:
    fontFamily: "Rubik, Arial, sans-serif"
    fontSize: "clamp(3rem, 6.2vw, 5.6rem)"
    fontWeight: 700
    lineHeight: 1.035
    letterSpacing: "-.035em"
  headline:
    fontFamily: "Rubik, Arial, sans-serif"
    fontSize: "clamp(2.35rem, 4vw, 3.75rem)"
    fontWeight: 700
    lineHeight: 1.08
    letterSpacing: "-.035em"
  body:
    fontFamily: "Rubik, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "Rubik, Arial, sans-serif"
    fontSize: ".9rem"
    fontWeight: 700
    lineHeight: 1.4
  annotation:
    fontFamily: "Georgia, serif"
    fontSize: "1.5rem"
rounded:
  image: "3px"
  menu: "4px"
  button: "6px"
  filter: "30px"
spacing:
  caption: "14px"
  action: "24px"
  section: "32px"
components:
  button-primary:
    backgroundColor: "{colors.plum}"
    textColor: "{colors.paper}"
    rounded: "{rounded.button}"
    padding: "14px 24px"
    typography: "{typography.label}"
  button-primary-hover:
    backgroundColor: "{colors.deep}"
  button-contact:
    backgroundColor: "{colors.pink}"
    textColor: "{colors.deep}"
    rounded: "{rounded.button}"
    padding: "14px 24px"
  button-contact-hover:
    backgroundColor: "{colors.paper}"
  filter:
    backgroundColor: "transparent"
    textColor: "{colors.plum}"
    rounded: "{rounded.filter}"
    padding: "9px 18px"
  filter-selected:
    backgroundColor: "{colors.plum}"
    textColor: "{colors.paper}"
---

# Design System: JAW Creations

## Overview

**Creative North Star: "The Artist Exhibition Foldout"**

An artist exhibition foldout: cream paper, large plum lettering, pink and sage fields, and real artwork with printed captions. The personality is personal and handmade, with restrained tilted mounts and occasional italic serif annotations.

Documented from the final inline CSS and markup in `index.html`. Browser rendering and capture were blocked; this records source intent, not verified visual fidelity.

**Key Characteristics:**
- Cream paper and plum type anchor the page.
- Real artwork leads; captions identify each medium.
- Pink and sage fields organize the exhibition.

## Colors

### Primary
Plum carries headings, primary actions, and the contact field. Deep plum supplies hover depth and dark text on pink.

### Secondary
Pink highlights the hero phrase, the medium strip, and the contact action. Sage backs the services section and a fabric artwork mount.

### Neutral
Paper is the page canvas; white is the lighter artwork mount. Ink is body text, muted is supporting copy, and line separates controls and footer content. The frontmatter records reused colors; isolated divider and contact-text colors remain in source.

## Typography

Rubik is self-hosted in regular and bold weights. The hero uses the display role, section headings use headline, and body remains comfortably spaced with a general maximum measure of 68ch. Buttons use the label role. Georgia italic appears in annotations, the quotation, signature, and footer line; italic style is applied in CSS. Smaller captions and contextual heading sizes remain component-specific in source.

## Layout

The centered container is capped at 1280px with 48px desktop side gutters. At 1050px and below the gutters become 32px, and at 760px and below they become 20px. Desktop hero, services, story, and contact use paired columns; at 760px they stack. The artwork gallery changes from three columns to two. Its initial lead image is portrait and spans two rows on desktop; filtering and mobile restore square images. Section padding ranges from 57px to 110px, depending on section and viewport. Above 1600px the hero column gap increases to 85px; at 360px actions stack.

## Elevation & Depth

Depth comes mainly from colored paper mounts, artwork, and small rotations. Only the hero window mount uses a shadow (`0 14px 30px -20px #34263e66`). Window, fabric, and story mounts rotate −3°, 4°, and −2° respectively. Gallery images enlarge subtly on hover; they are not raised cards.

## Shapes

Artwork links have barely rounded corners; buttons are softly squared, menu controls slightly tighter, and filter chips fully rounded at their compact height. Thin borders and open captions keep artwork separate without heavy enclosing boxes.

## Components

Primary actions are bold plum links with paper text, a thin matching border, and a 54px minimum height. The contact action reverses to pink on plum. Navigation uses plain links and a smaller action; at 760px a progressive menu control manages the links when JavaScript is available. Filter chips use `aria-pressed` to expose selection and remain hidden until their behavior is ready. Artwork is a linked image followed by a title, medium, and optional desktop view cue. There is no inquiry input or form: the contact action opens an email client.

Focus uses a 3px plum outline offset by 5px; the contact region changes the outline to pink. Button color changes take .25s, filter changes .2s, image scale .6s, and gallery recomposition .36s using the source easing. Reduced-motion preferences disable animation, transitions, and smooth scrolling.

## Do's and Don'ts

- Do use supplied artwork and clear captions.
- Do preserve visible keyboard focus and reduced-motion behavior.
- Do use pink and sage as broad section or mount fields.
- Don’t stretch artwork; preserve the implemented contain/cover choices.
- Don’t turn every content group into a raised card.
- Don’t use the serif annotation face for body copy.
