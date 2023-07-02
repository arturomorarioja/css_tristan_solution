# KEA Tristan Wede Lind

## Purpose
SPA (single page application) for the fictive web developer, author and public speaker Tristan Wede Lind.

## UX Practices
- Responsiveness is enforced through the use of normal flow, float, media queries, flexbox and grid
- Large images are responsive
- As the viewport's horizontal dimension becomes larger, page content is centered between equal-sized margins. Said margins increase their size based on viewport width
- Unnecessary content is removed from the mobile view (e.g., Tristan's header picture, books' preview in the Home article, and Tristan's talk picture in the Contact article)

## Code practices
The following practices applied to the project improve code readability and maintainability:

- The division of CSS code into five different files:
    - variables.css. CSS variables
    - styles.css. Code that is common to all four articles
    - home.css, tour.css, books.css, contact.css. CSS specific to each one of the articles
- The cards used in both the On tour and Books articles are styled via the common class `.card-container`
- CSS variables are used for colours and fonts

## Tools
CSS3 / HTML5

## Author:
Arturo Mora-Rioja