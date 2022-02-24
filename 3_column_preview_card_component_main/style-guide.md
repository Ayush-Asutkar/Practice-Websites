# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

Bright orange: hsl(31, 77%, 52%)
Dark cyan: hsl(184, 100%, 22%)
Very dark cyan: hsl(179, 100%, 13%)

### Neutral

Transparent white (paragraphs): hsla(0, 0%, 100%, 0.75)
Very light gray (background, headings, buttons): hsl(0, 0%, 95%)

## Typography

### Body Copy

- Font size: 15px

### Font

- Family: [Lexend Deca](https://fonts.google.com/specimen/Lexend+Deca)
- Weights: 400

- Family: [Big Shoulders Display](https://fonts.google.com/specimen/Big+Shoulders+Display)
- Weights: 700

//Styles.css
<!-- @import url('https://fonts.googleapis.com/css2?family=Big+Shoulders+Display:wght@702&family=Lexend+Deca&display=swap');
/* 
font-family: 'Big Shoulders Display', cursive;
font-family: 'Lexend Deca', sans-serif; */

body {
    background-color: hsl(0, 0%, 95%);
    min-height: 100vh;
    display: flex;
    align-items: center;
    font-size: 15px;
    font-family: 'Lexend Deca', sans-serif;
    font-weight: 400;
}

.container {
    max-width: 960px;
    margin: 0 auto;
}

.wrapper {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    
} -->