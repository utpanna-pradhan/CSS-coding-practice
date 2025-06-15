Q101. What is CSS BEM naming convention?
A: Block Element Modifier — improves readability: block__element--modifier

Q102. What is contain in CSS?
A: Helps with performance by containing layout, paint, or size of elements.

Q103. How can you create animations in CSS?
A: Using @keyframes and animation properties.

Q104. What is the difference between transition and animation?
A: transition is for state changes; animation is keyframe-based with more control.

Q105. What is @supports rule?
A: A conditional group rule for checking feature support:

css
Copy
Edit
@supports (display: grid) { ... }
Q106. What is is() and where() in CSS selectors?
A: Group multiple selectors with reduced specificity.

Q107. How does accent-color work?
A: Changes color of native UI elements like checkboxes and radio buttons.

Q108. How do you create a CSS-only dropdown menu?
A: Using :hover and nested elements.

Q109. What is the Shadow DOM and how does it affect CSS?
A: Encapsulated DOM structure; styles outside don't apply unless specifically exposed.

Q110. What are CSS Houdini APIs?
A: Allow direct access to CSS rendering engines via JavaScript.

Q111. What is a @layer in CSS?
A: Helps organize and manage specificity across different style blocks.

Q112. What are :has() and :is() pseudo-classes?
A: :has() selects a parent if it contains a child; :is() simplifies complex selectors.

Q113. What is backdrop-filter?
A: Applies graphical effects (like blur) to the area behind an element.

Q114. What is the difference between absolute and fixed inside a scrollable div?
A: fixed is relative to the viewport; absolute is relative to the nearest positioned ancestor.

Q115. What is scroll-snap in CSS?
A: Controls scroll behavior for carousels, slides, etc.

Q116. What does mix-blend-mode do?
A: Blends an element with the background.

Q117. How do you create dark/light themes using CSS variables?
A: Define variables and switch them using classes or media queries.

Q118. What is a CSS paint API?
A: Allows custom drawing logic for elements.

Q119. What is a CSS nesting proposal?
A: Syntax allowing nested rules inside selectors (like Sass).

Q120. What is logical property inset?
A: Shorthand for top, right, bottom, left.

Q121. What is scrollbar-gutter?
A: Provides control over layout shifts caused by scrollbars.

Q122. What is the difference between CSS Modules and SCSS?
A: CSS Modules scope styles by default; SCSS adds features like nesting and mixins.

Q123. What is @property in CSS?
A: Allows defining custom animatable CSS properties.

Q124. What is the role of hyphens in CSS?
A: Controls word breaking with hyphenation.

Q125. What is subgrid in CSS Grid?
A: Allows nested grids to inherit grid lines from the parent grid.

Q126. What are environment variables in CSS?
A: Variables like safe-area-inset-top for notch-aware layout.

Q127. What is the env() function in CSS?
A: Retrieves values from environment variables like safe areas.

Q128. What is the purpose of image-set()?
A: Serve different image resolutions depending on device.

Q129. What does overflow-anchor do?
A: Prevents scroll jumps during content load.

Q130. How do CSS counters work?
A: Create numbered content using counter-reset and counter-increment.

Q131. What is a clip-path in CSS?
A: Clips an element to a specific shape.

Q132. What is page-break in print styles?
A: Controls page breaks when printing.

Q133. What are keyframe percentages in @keyframes?
A: Define stages of animation (0% to 100%).

Q134. What is reflow and repaint in CSS?
A: Reflow = layout recalculation; repaint = visual update.

Q135. What is object-position used for?
A: Sets position of replaced elements like images inside containers.

Q136. What is overscroll-behavior?
A: Controls scroll chaining and bounce effects.

Q137. How do you hide an element from screen readers only?
A: aria-hidden=\"true\" or visually hide but keep accessible.

Q138. What is contain-intrinsic-size?
A: Provides a fallback size for off-screen content.

Q139. How to control print-specific styles?
A: Use @media print { ... }

Q140. How does animation-fill-mode work?
A: Defines how styles are applied before/after animation.

Q141. What are custom media queries?
A: Define reusable queries using @custom-media.

Q142. What are layered animations?
A: Using multiple animations on the same element simultaneously.

Q143. What is resize in CSS?
A: Allows users to resize elements (like textareas).

Q144. What is an @font-face rule?
A: Embeds custom fonts into a webpage.

Q145. What is the difference between inline and inline-block?
A: inline-block allows width/height, inline doesn’t.

Q146. What is a fallback font in font-family?
A: Alternative fonts used if the preferred one isn't available.

Q147. What is critical CSS?
A: The CSS required to render above-the-fold content quickly.

Q148. What is the purpose of translateZ(0)?
A: Promotes element to GPU layer for performance boost.

Q149. How to animate display in CSS?
A: You can’t; use opacity, visibility, or JS toggle.

Q150. How to optimize CSS for performance?
A: Minify, use fewer selectors, reduce specificity, load only required styles.
