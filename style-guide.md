# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Very dark blue (main background): hsl(233, 47%, 7%)
- Dark desaturated blue (card background): hsl(244, 38%, 16%)
- Soft violet (accent): hsl(277, 64%, 61%)

### Neutral

- White (main heading, stats): hsl(0, 0%, 100%)
- Slightly transparent white (main paragraph): hsla(0, 0%, 100%, 0.75)
- Slightly transparent white (stat headings): hsla(0, 0%, 100%, 0.6)

## Typography

### Body Copy

- Font size: 15px

### Font

- Family: [Inter](https://fonts.google.com/specimen/Inter)
- Weights: 400, 700

- Family: [Lexend Deca](https://fonts.google.com/specimen/Lexend+Deca)
- Weights: 400
.images {
    position: relative;
    height: 13em;
    width: 100%;
    background-image: url(images/image-header-mobile.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    overflow: hidden;
    border-radius: 10px 10px 0 0;
}

.overlay {
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: var(--violet-overlay);
}

.overlay2 {
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: var(--violet-overlay2);
    mix-blend-mode: color-burn;
}