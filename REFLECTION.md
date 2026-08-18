# CSS Reflection

One non-obvious CSS decision I made was combining CSS Grid and Flexbox instead of using only one layout model for the whole PlayReal landing page. I chose Grid for sections like the hero, the problem cards, the justification cards, the user stories, and the checklist because those parts need a clear two-dimensional structure. The cards must align in rows and columns, and the layout changes from one column on mobile to multiple columns on tablet and desktop.

If I had used Flexbox for all of those card sections, the result would have been harder to control because Flexbox is better for one-direction layouts. The cards could wrap, but their columns would not feel as intentional or balanced across breakpoints. I chose Grid because it makes the responsive structure easier to understand and keeps the landing page organized.

I still used Flexbox for the navigation, hero buttons, flow steps, and form because those elements mainly move in one direction. That made the CSS easier to maintain: Grid controls page structure, while Flexbox controls smaller rows of actions and controls.
