#### **Lab: Building Your Portfolio Shell**

* **Level 1: The Single Page**  
  * **Tasks:** Create a project folder, create an index.html file, and add a single \<h1\> tag.  
  * **Outcome:** A single, local HTML file that can be opened in a web browser.  
* **Level 2: A Structured Project**  
  * **Tasks:** Create css and js sub-folders, create an empty styles.css file, add HTML boilerplate, and link the stylesheet.  
  * **Outcome:** A well-organized project folder with linked CSS, ready for styling.  
* **Level 3: The Multi-Page Site Shell & Version Control**  
  * **Tasks:** Create additional HTML pages (about.html, contact.html), initialize a Git repository, and make your first commit.  
  * **Outcome:** A complete, multi-page static website skeleton, safely tracked in version control history.  
* **Level 4: Professional Repository Setup**  
  * **Tasks:** Create a README.md and a .gitignore file. Add a basic navigation section to all pages and commit the changes.  
  * **Outcome:** A professional-looking local Git repository that includes documentation and ignores unnecessary files.  
* **Level 5: Advanced Workflow & Remote Setup**  
  * **Tasks:** Create and switch to a develop branch. Create a new repository on GitHub, link your local repo to it, and push your branches.  
  * **Outcome:** A project that is not only version-controlled locally but also backed up remotely on GitHub, following a standard branching workflow.

#### **Lab: Applying Styles & The Box Model**

* **Level 1: Basic Styling**  
  * **Tasks:** Link your styles.css file. Use **element selectors** (h1, p) to set a default font family and color for the entire page.  
  * **Outcome:** A page with consistent, basic typography and color, moving away from the browser's default look.  
* **Level 2: Class-based Styling**  
  * **Tasks:** Create and apply **class selectors** (e.g., .nav-link, .project-card) to style specific, reusable elements. Give your header and footer distinct background colors.  
  * **Outcome:** A site with a clear visual hierarchy and styled sections.  
* **Level 3: Mastering the Box Model**  
  * **Tasks:** Use **padding** to give your content sections breathing room. Add **margins** between elements like project cards or paragraphs to create clear separation. Place a **border** around a key element, like your profile picture.  
  * **Outcome:** A well-spaced, clean layout that is easy to read and navigate.  
* **Level 4: Themed Design**  
  * **Tasks:** Select a professional color palette (2-3 colors) and a font pairing (one for headings, one for body text). Apply this theme consistently across all pages of your portfolio. Commit your styling changes to Git with a message like "feat: Add base styling and theme".  
  * **Outcome:** A portfolio with a cohesive and intentional design theme, with all changes tracked in Git.  
* **Level 5: Advanced Selectors & Dev Tools Debugging**  
  * **Tasks:** Use more advanced selectors, like attribute selectors (input\[type="text"\]) or pseudo-classes (a:hover), to add subtle interactive feedback. Intentionally create a spacing issue and use the browser's **developer tools** to inspect the Box Model, diagnose the problem, and fix it.  
  * **Outcome:** A polished and interactive design, and the foundational skill of debugging CSS visually using professional tools.

#### **Lab: Building a Responsive NavBar & Page**

* **Level 1: Flexbox Navigation**  
  * **Tasks:** Convert your top navigation from a simple list into a horizontal bar using display: flex. Use justify-content to space the links out evenly.  
  * **Outcome:** A clean, single-row navigation bar for your portfolio header.  
* **Level 2: Grid Page Structure**  
  * **Tasks:** Use display: grid to define the main layout regions of your index.html page (e.g., a header, a main content area, and a footer).  
  * **Outcome:** A well-structured page where major sections are explicitly placed in a grid.  
* **Level 3: Combining Flexbox and Grid**  
  * **Tasks:** Nest the Flexbox-powered navigation bar from Level 1 inside the "header" area of your CSS Grid layout.  
  * **Outcome:** A layout that correctly uses the best tool for the job: Grid for the overall page structure and Flexbox for the components within it.  
* **Level 4: Basic Responsiveness**  
  * **Tasks:** Write your first **media query**. For screen widths below 768px, make the navigation links stack vertically instead of sitting in a row.  
  * **Outcome:** A layout that adapts its navigation for smaller screens, preventing horizontal scrolling.  
* **Level 5: Mobile-First Responsive Layout**  
  * **Tasks:** Refactor your CSS to follow a "mobile-first" approach. Your default styles should be for mobile, and you'll use media queries with min-width to add complexity for larger screens (e.g., changing from a single-column layout to a two-column layout on tablets/desktops). Commit your changes to Git with a message like "feat: Implement responsive layout with Flexbox and Grid".  
  * **Outcome:** A professional, fully responsive portfolio that provides an optimal viewing experience on any device, with all changes tracked in Git.

## To do:
Play with color pallette variations:

Role	          Color	                       Use case
Primary	        #FF69B4 (Hot Pink)	        Navigation bar, headings, key highlights
Secondary	      #FFC0CB (Light Pink)	      Hover states, buttons, subtle accents
Accent	        #00CED1 (Dark Turquoise)	  Links, call-to-action elements
Neutral Light 	#F5F5F5 (Very Light Gray)	Page background, containers
Neutral Dark	  #333333 (Dark Gray)	      Body text for readability
