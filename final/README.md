# MaxGain Foods
**Description:** A nutrition-focused project highlighting the best foods and meals to build muscle, increase strength, and support healthy gains.
**Key Facts**
-Protein is key – Foods like chicken, eggs, fish, and beans provide the building blocks (amino acids) your muscles need to grow.
-Healthy carbs fuel workouts – Whole grains, oats, and sweet potatoes give energy for lifting and help muscles recover faster.
Fats support hormone production – Healthy fats from nuts, avocado, and olive oil help produce hormones like testosterone, which are important for muscle growth.

## MaxGain Foods: Eat Smart, Build Strong
''' MaxGain Foods is your go-to guide for choosing the best meals to support muscle growth, increase strength, and achieve healthy weight gain. Nutrition plays a major role in fitness, and the right foods can make a big difference in how your body performs and recovers. This project highlights simple, effective ways to fuel your body with purpose.

By focusing on balanced nutrition, MaxGain Foods helps you understand how to eat smarter, not just more. Whether you're working out regularly or just starting your fitness journey, the right combination of nutrients can improve your energy, endurance, and overall results.
## About MaxGain Foods
''' MaxGain Foods is built around the idea that proper nutrition is essential for building muscle and strength. Protein-rich foods like chicken, eggs, fish, and beans provide amino acids that repair and grow muscles after workouts. These nutrients are the foundation of any effective muscle-building plan.

In addition to protein, healthy carbohydrates and fats play important roles in performance and recovery. Carbs from whole grains, oats, and sweet potatoes provide the energy needed for intense workouts, while healthy fats from nuts, avocado, and olive oil support hormone production. Together, these nutrients help your body grow stronger, recover faster, and perform at its best.

## https://www.heart.org/en/healthy-living/healthy-eating/eat-smart/nutrition-basics/food-as-fuel-before-during-and-after-workouts
''' 

## AI Session Link
https://chatgpt.com/share/69c1bd8c-d1dc-8000-9969-51f7e9ca2ea7

# Difference Between Block and Inline Elements

- **Block Elements**
  - Take up the **full width** of their container.
  - Start on a **new line**.
  **Inline Elements**
  - Take up **only as much width as needed**.
  - Do **not start on a new line**.

  # Links

- **<a> tag**
  - Used to create hyperlinks in HTML.
  - Syntax: `<a href="URL">Link Text</a>`

- **href attribute**
  - Stands for "hypertext reference".
  - Specifies the destination URL of the link.

- **Absolute vs. Relative Paths**
  - **Absolute path:** full URL or full path to a file.
    - Example: `https://www.example.com/page.html`
  - **Relative path:** path relative to the current file location.
    - Example: `about.html` (same folder) or `../images/pic.jpg` (one folder up)
    # Images

- **<img> tag**
  - Used to display images in HTML.
  - It is a self-closing tag (no closing tag needed).

- **src attribute**
  - Specifies the path to the image file.
  - Example: `src="images/photo.jpg"`

- **alt attribute**
  - Provides alternative text if the image cannot load.
  - Important for accessibility and screen readers.
  - Example: `alt="Person climbing a wall"`
  # Week 4: CSS

CSS (Cascading Style Sheets) is used to style and design a website. It controls how HTML elements look, such as colors, fonts, spacing, and layout, making the webpage visually appealing and organized.
## Hex Code and Color

Hex codes are used in CSS to define exact colors. They start with a # followed by 6 characters (numbers and letters). This allows designers to match colors precisely across websites.
## The Cascade

The cascade in CSS means that when multiple styles apply to the same element, the browser decides which one to use based on rules like importance, specificity, and order. The last rule written or the most specific selector usually wins.
## Logical and Align Properties

Logical and align properties in CSS help control how elements are positioned and aligned on a webpage. They allow you to center, align, and organize content (like text and images) in a clean and consistent layout, making the design easier to read and more structured.
## Font Stack

A font stack in CSS is a list of fonts used for text. The browser will try the first font, and if it is not available, it will move to the next one in the list. This ensures the text still looks good even if a certain font is not installed on the user’s device.
## Week 4: Design & Layout

### Colors

- Primary: #2E7D32 — I chose this green because it represents health, growth, and fitness, which matches my topic of building strength and nutrition.
- Accent: #FF8F00 — I chose this orange to add energy and attention to key parts of the design like buttons and highlights.
- Text / Background: #424242 — I chose this dark gray because it keeps text readable and balanced without being too harsh like pure black.

### Fonts

- Font Stack: Verdana, Geneva, sans-serif

I chose this font stack because it is clean, easy to read, and works well for both headings and body text on all devices.
<!-- final check -->
# Week 5: Layout & Box Model

## Inheritance

Inheritance in CSS means that some properties from a parent element (like body) are automatically passed down to child elements (like h1, p, etc.). This is important because it helps reduce repetition in CSS and keeps the code cleaner and easier to manage. Instead of writing the same styles for every element, we can set them once in the parent and let them flow down.
## User Agent

User Agent Styles are the default styles that browsers apply to HTML elements when no custom CSS is written. For example, links are usually blue and underlined by default. These styles come from the browser itself, not from the developer. We can override User Agent styles using CSS to fully control how elements look on a webpage.
## User REM

REM units are a relative measurement in CSS that are based on the root element’s font size (usually the <html> element). This means 1rem is equal to the default font size set in the browser, often 16px.

### Why REMs?

REMs are important because they make websites more flexible and scalable. Instead of using fixed pixel sizes, REMs allow text and spacing to adjust more easily across different screen sizes and user settings. This improves accessibility and makes designs more consistent, especially when users zoom in or change their default font size.
## Dev Tools

DevTools are built into the browser and help developers inspect and debug HTML and CSS in real time. I can right-click any element and use “Inspect” to see its styles, structure, and layout. I can also enable or disable CSS rules to test changes instantly without editing my code. This helps me find and fix design problems faster.
## Padding

Padding is the space inside an element between the content and its border or background edge. It makes elements feel less cramped and improves readability. When padding is added, the background color expands because padding is part of the element’s internal space.

Rule: Padding gives you more background.
## Week 5: Accessibility & Layout

We switched font sizes from pixels (px) to rem units to improve accessibility. REM units allow users to scale text based on their browser settings, making the website easier to read for people with different visual needs or preferences.

We used padding and margin to style the .cta-box. Padding adds space inside the box, making the content feel less cramped, while margin creates space outside the box to separate it from other elements on the page.
## Week 7: pseudo-class(s)

The `a` tag (anchor tag) is used for links. Pseudo-classes let us change how links behave in different states.

- `a` styles the normal link.
- `a:hover` styles the link when the mouse is over it.
- `a:focus-visible` styles the link when it is selected using the keyboard (Tab key).

I grouped `a:hover` and `a:focus-visible` together so both mouse users and keyboard users get the same visual feedback.

The order matters because CSS reads from top to bottom, and more specific or later rules can override earlier ones. This helps ensure links behave consistently across interaction types.
## background image

For this section, a background image was used instead of an `<img>` tag because it allows the image to act as a visual design layer behind the text.

CSS background properties were used because they give better control over layout and readability. Kevin used `background-size: cover` so the image fills the entire section without stretching, and `background-position: center` so the most important part of the image stays visible.

Padding was added to give space around the text, and the text color was changed to white to make it readable over the image.

This approach keeps HTML focused on content while CSS handles design, which is a cleaner and more professional structure.
## Descendant Selectors

A descendant selector targets elements inside another element. Example:

.climber-bg strong

This selects all `<strong>` elements inside `.climber-bg`.

### Benefit

It lets you style specific sections without affecting the rest of the page, keeping your design organized.

### Playing Around

I tested it by adding `<strong>` text inside `.climber-bg` and changing colors to see how it only affects that section.
## Specificity

Specificity in CSS decides which style is applied when multiple rules target the same element.

IDs have higher priority than classes, and classes have higher priority than element selectors. For example, when I applied both `.orange-text` and `#purple-text` to the same `<h2>`, the text became purple because the ID overrides the class.

This impacts design because it controls which styles actually appear on the page, so using more specific selectors can override others. It’s important to keep specificity simple to avoid confusion.x
## Debugging with DevTools

I use Chrome DevTools by right clicking and pressing Inspect. Then I check the Styles panel to see what CSS is applied.

If something is not working, I look for crossed out styles and test changes live to fix it.

## Styling list

I can style list bullets using li::marker.

Example:
li::marker {
color: #E67E22;
}

This changes only the bullet color, not the text.

Things to remember:

* Keep it simple
* Make sure it matches the design
* Don’t make it hard to read
..
## Week 7 Engineering Notes

My descendant selector `.cta-box h2` has a specificity score of 0, 1, 1.

This score is needed because it is more specific than the global `h2` style. The global `h2` only targets the element by tag name, but the descendant selector targets the element inside a specific class. This allows it to override the global styles inside the CTA box without affecting other headings on the page.

## Week 8 Engineering Notes

### The "Why" Behind the Breakpoint
I chose 700px because that was the point where the image and text started looking cramped during the squish test. Before 700px the layout looked cleaner stacked vertically.

### Alignment Logic
I removed the default margin and padding from the ul because browsers automatically add spacing. Removing it helped the logo and navigation links align evenly inside the flexbox header.

### Nesting Benefits
Nesting the media query inside the selector keeps the responsive styles connected to the component they belong to. This makes the CSS easier to read and maintain.

## Week 9 Sub Pages:

For this project, I created two subpages to expand my main website, MaxGain Foods, into a more detailed nutrition-focused system. These subpages help turn the site from a basic homepage into a structured learning platform about nutrition, meal planning, and fitness support.

The first subpage, "Nutrition Tips," focuses on practical advice for improving daily nutrition habits such as meal timing, protein intake, hydration, and avoiding common mistakes when trying to build muscle or gain strength. This page connects directly to the Healthy Meal Plan page by helping users understand how to apply nutrition more effectively in real life.

The second subpage, "Meal Prep," focuses on how to prepare meals in advance for better consistency and results. It teaches users how to organize their weekly meals, choose balanced foods, and stay consistent with their nutrition goals. This page connects to both the Meal Plan and Nutrition Tips pages by turning information into action.

Both subpages are linked through the main navigation bar so users can easily move between all sections of the website. This creates a connected structure where each page builds on the others and supports a complete understanding of nutrition and healthy eating.