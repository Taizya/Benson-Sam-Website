## TODO

1. Read the @src/pages/index.astro, extrapulate the styles that create the glass like effect
   from the expert-guidance-content class and apply them to the @src/components/GlassEffect.astro
   Ensure that GlassEffect component accepts
   props to be used in the paragraph and heading
2. Use the new glass effect instead of applying the styles directly instead of using a the div with expert-guidance-content
   and use the exact same paragraph and heading text used in the previous iteration
3. Modify the button styles for both black and gold to use the following:
   ```
      padding: 0.35rem 1.5rem;
      border-radius: 0.425em;
      font-size: 1.25em;
   ```
4. Modify the our-team and the ourt-insights sections to use a flexbox to contain the Heading, Cardslayout/insights-grid
   and the button with a 1.5rem gap. Make sure all the elements are still aligned in a column with the elements
   contained int it in different rows not a row with columns.
5. do a git commit with a message saying "updated homepage jul 28 2025"
6. Everything seems too big so i would like to reduce the size but not so much that everything looks small,
   reduce the size of everything by a scale of .25 times.
