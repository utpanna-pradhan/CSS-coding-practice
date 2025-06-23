# Q1. What is CSS BEM naming convention?
A: Block Element Modifier — improves readability: block__element--modifier

# Q02. What is contain in CSS?
A: Helps with performance by containing layout, paint, or size of elements.

# Q03. How can you create animations in CSS?
A: Using @keyframes and animation properties.

# Q04. What is the difference between transition and animation?
A: transition is for state changes; animation is keyframe-based with more control.

# Q05. What is @supports rule?
A: A conditional group rule for checking feature support:

@supports (display: grid) { ... }
Q06. What is is() and where() in CSS selectors?
A: Group multiple selectors with reduced specificity.

# Q07. How does accent-color work?
A: Changes color of native UI elements like checkboxes and radio buttons.

# Q08. How do you create a CSS-only dropdown menu?
A: Using :hover and nested elements.

# Q09. What is the Shadow DOM and how does it affect CSS?
A: Encapsulated DOM structure; styles outside don't apply unless specifically exposed.

# Q10. What are CSS Houdini APIs?
A: Allow direct access to CSS rendering engines via JavaScript.

# Q11. What is a @layer in CSS?
A: Helps organize and manage specificity across different style blocks.

# Q12. What are :has() and :is() pseudo-classes?
A: :has() selects a parent if it contains a child; :is() simplifies complex selectors.

# Q13. What is backdrop-filter?
A: Applies graphical effects (like blur) to the area behind an element.

# Q14. What is the difference between absolute and fixed inside a scrollable div?
A: fixed is relative to the viewport; absolute is relative to the nearest positioned ancestor.

# Q15. What is scroll-snap in CSS?
A: Controls scroll behavior for carousels, slides, etc.

# Q16. What does mix-blend-mode do?
A: Blends an element with the background.

# Q17. How do you create dark/light themes using CSS variables?
A: Define variables and switch them using classes or media queries.

# Q18. What is a CSS paint API?
A: Allows custom drawing logic for elements.

# Q19. What is a CSS nesting proposal?
A: Syntax allowing nested rules inside selectors (like Sass).

# Q20. What is logical property inset?
A: Shorthand for top, right, bottom, left.

# Q21. What is scrollbar-gutter?
A: Provides control over layout shifts caused by scrollbars.

# Q22. What is the difference between CSS Modules and SCSS?
A: CSS Modules scope styles by default; SCSS adds features like nesting and mixins.

# Q23. What is @property in CSS?
A: Allows defining custom animatable CSS properties.

# Q24. What is the role of hyphens in CSS?
A: Controls word breaking with hyphenation.

# Q25. What is subgrid in CSS Grid?
A: Allows nested grids to inherit grid lines from the parent grid.

# Q26. What are environment variables in CSS?
A: Variables like safe-area-inset-top for notch-aware layout.

# Q27. What is the env() function in CSS?
A: Retrieves values from environment variables like safe areas.

# Q28. What is the purpose of image-set()?
A: Serve different image resolutions depending on device.

# Q29. What does overflow-anchor do?
A: Prevents scroll jumps during content load.

# Q30. How do CSS counters work?
A: Create numbered content using counter-reset and counter-increment.

# Q31. What is a clip-path in CSS?
A: Clips an element to a specific shape.

# Q32. What is page-break in print styles?
A: Controls page breaks when printing.

# Q33. What are keyframe percentages in @keyframes?
A: Define stages of animation (0% to 100%).

# Q34. What is reflow and repaint in CSS?
A: Reflow = layout recalculation; repaint = visual update.

# Q135. What is object-position used for?
A: Sets position of replaced elements like images inside containers.

# Q136. What is overscroll-behavior?
A: Controls scroll chaining and bounce effects.

# Q37. How do you hide an element from screen readers only?
A: aria-hidden=\"true\" or visually hide but keep accessible.

# Q38. What is contain-intrinsic-size?
A: Provides a fallback size for off-screen content.

# Q39. How to control print-specific styles?
A: Use @media print { ... }

# Q40. How does animation-fill-mode work?
A: Defines how styles are applied before/after animation.

# Q41. What are custom media queries?
A: Define reusable queries using @custom-media.

# Q42. What are layered animations?
A: Using multiple animations on the same element simultaneously.

# Q43. What is resize in CSS?
A: Allows users to resize elements (like textareas).

# Q44. What is an @font-face rule?
A: Embeds custom fonts into a webpage.

# Q45. What is the difference between inline and inline-block?
A: inline-block allows width/height, inline doesn’t.

# Q46. What is a fallback font in font-family?
A: Alternative fonts used if the preferred one isn't available.

# Q47. What is critical CSS?
A: The CSS required to render above-the-fold content quickly.

# Q48. What is the purpose of translateZ(0)?
A: Promotes element to GPU layer for performance boost.

# Q49. How to animate display in CSS?
A: You can’t; use opacity, visibility, or JS toggle.

# Q50. How to optimize CSS for performance?
A: Minify, use fewer selectors, reduce specificity, load only required styles.
