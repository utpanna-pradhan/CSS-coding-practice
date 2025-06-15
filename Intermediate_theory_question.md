Q51. What are media queries in CSS?
A: Media queries apply styles based on screen size, resolution, or device type.

Q52. How do you write a media query for mobile devices?
A: @media (max-width: 768px) { ... }

Q53. What is Flexbox in CSS?
A: A layout model for one-dimensional layout (row or column) that distributes space efficiently.

Q54. How do you center a div using Flexbox?
A:

css
Copy
Edit
display: flex;  
justify-content: center;  
align-items: center;
Q55. What is the difference between justify-content and align-items in Flexbox?
A: justify-content aligns items along the main axis; align-items aligns items on the cross axis.

Q56. What is flex-wrap used for?
A: Allows flex items to wrap to multiple lines.

Q57. What is the difference between auto and % in width?
A: auto sizes based on content; % is relative to parent container.

Q58. What is specificity in CSS?
A: Determines which style rule applies when there is a conflict.

Q59. How is specificity calculated?
A: Inline styles > ID selectors > Class/attribute/pseudo-class > Element selectors

Q60. What is the z-index stacking context?
A: It determines the vertical stacking order of elements.

Q61. What is relative positioning used for?
A: Offsets the element from its normal position.

Q62. What is the calc() function in CSS used for?
A: To perform calculations within CSS values (e.g. width: calc(100% - 50px))

Q63. What are custom properties (CSS variables)?
A: Reusable values defined with --name: value; and used with var(--name).

Q64. What is clamp() in CSS?
A: Sets a scalable value within a defined min and max.

Q65. What is the difference between vh, vw, and %?
A: vh/vw are relative to viewport; % is relative to parent.

Q66. How do you make a sticky header?
A: position: sticky; top: 0;

Q67. What’s the purpose of min-height and max-height?
A: To set boundaries for element height.

Q68. What’s the use of object-fit for images?
A: Controls how content (like images) is resized within a container.

Q69. What does outline do in CSS?
A: Adds a line outside the border (commonly seen on focused inputs).

Q70. Difference between visibility: hidden and display: none?
A: hidden hides element but keeps space; none removes it entirely.

Q71. What is a CSS transition?
A: A way to animate changes in CSS properties smoothly.

Q72. How do you add a hover effect to a button?
A: button:hover { background-color: blue; }

Q73. What is nth-child() in CSS?
A: Selects elements based on their position among siblings.

Q74. How do you use not() selector?
A: div:not(.active) { ... } — targets all except .active

Q75. What is pointer-events: none; used for?
A: Disables mouse interactions for the element.

Q76. How to make a responsive image?
A: img { max-width: 100%; height: auto; }

Q77. What is the currentColor keyword?
A: Refers to the current text color.

Q78. What is the difference between em, rem, and px?
A: em = parent size, rem = root size, px = fixed size.

Q79. What is a breakpoint in responsive design?
A: A screen width where layout changes via media queries.

Q80. What is filter in CSS?
A: Applies visual effects like blur, brightness, grayscale, etc.

Q81. What is the box-shadow property?
A: Adds shadow outside an element.

Q82. What is text-overflow: ellipsis;?
A: Truncates text and adds ... when content overflows.

Q83. What does white-space: nowrap; do?
A: Prevents text from wrapping to the next line.

Q84. How to prevent an element from being resized in a textarea?
A: resize: none;

Q85. What is a grid in CSS?
A: A 2D layout system for rows and columns.

Q86. How to define a grid container?
A: display: grid;

Q87. What does grid-template-columns: 1fr 2fr; mean?
A: Creates two columns, one 1 part wide, another 2 parts.

Q88. What is the difference between fr, %, and auto in CSS Grid?
A: fr is fractional unit, % is parent-relative, auto fits content.

Q89. How to position an element in the center of the screen?
A:

css
Copy
Edit
position: absolute;  
top: 50%;  
left: 50%;  
transform: translate(-50%, -50%);
Q90. What is layering in CSS?
A: Controlling the stacking order using z-index.

Q91. What is the difference between logical and physical properties?
A: Logical: margin-inline, padding-block; Physical: margin-left, padding-top

Q92. What is aspect-ratio in CSS?
A: Controls the width-to-height ratio of an element.

Q93. How do you style form inputs in CSS?
A: Target them with input, textarea, select, etc.

Q94. How to make an element unselectable?
A: user-select: none;

Q95. What is scroll-behavior: smooth;?
A: Enables smooth scrolling to anchor links.

Q96. What is stacking context in CSS?
A: A three-dimensional context that controls which elements appear on top.

Q97. What does content do in pseudo-elements?
A: Inserts generated content into an element via ::before or ::after.

Q98. How to debug CSS issues in browser?
A: Use browser DevTools (Inspect Element).

Q99. What is backface-visibility in CSS3?
A: Controls visibility of the back side of elements during 3D transforms.

Q100. What is will-change used for?
A: Hints to the browser what will change, to optimize rendering.
