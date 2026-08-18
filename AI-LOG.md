# AI Log - HW03 CSS Fundamentals

## Which CSS sections did you generate with AI?

I used AI to help create the first structure of `styles.css` for the PlayReal landing page. The AI helped suggest the order of the CSS file, including design tokens, base styles, layout rules, reusable components, forms, cards, and responsive media queries.

AI also helped with examples for using CSS Grid in the hero and card sections, Flexbox in the navigation and action buttons, and `position: sticky` for the header.

## What did you modify and why?

I modified the generated CSS to better match the PlayReal project and the visual direction we had already defined in previous homework. I adjusted the colors to use a brighter blue, soft backgrounds, white cards, rounded borders, and green accents that connect with the gamified dashboard idea.

I also reorganized some selectors so the CSS was easier to read: first reset and variables, then base elements, then layout, components, forms, and media queries. This made it easier to compare the file with the rubric and verify that margin, padding, border, Grid, Flexbox, and responsive breakpoints were present.

## What was hardest to understand about the generated CSS?

The hardest part was understanding when to use Grid and when to use Flexbox. At first, both seemed like they could solve the same problem, but reviewing the generated CSS helped me see the difference. Grid works better for larger page sections with rows and columns, while Flexbox works better for one-direction groups like navigation links, buttons, and form fields.

Another difficult part was understanding specificity. Some selectors were general, like `section`, while others were more specific, like `.hero-actions a:first-child`. I had to review the order of the file so later selectors did not accidentally override earlier styles in a confusing way.
