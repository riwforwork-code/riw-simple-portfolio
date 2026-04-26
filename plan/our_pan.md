# Portfolio Website Plan: Pakkapon Riw (Data Analyst)

### 1. Visual Design System
*   **Theme:** "Deep Space" Dark Mode (`#0d1117` background, `#e6edf3` text).
*   **Typography:** JetBrains Mono (via Google Fonts) for all elements to emphasize the "Data/Code" aesthetic.
*   **Accent Color:** Electric Blue (`#58a6ff`) for links, buttons, and borders.
*   **Layout:** Responsive flex/grid container with a max-width of 900px for a focused, professional look.

### 2. Implementation Steps

#### **Step 1: Project Initialization**
*   Create a local directory for the project.
*   Create core files: `index.html` and `style.css`.

#### **Step 2: HTML Structure (`index.html`)**
*   **Header/Nav:** Minimalist links (Projects, Contact).
*   **Hero Section:** 
    *   `<h1>Pakkapon Riw</h1>`
    *   `<h2>Data Analyst</h2>`
    *   A short "hook" about turning raw data into actionable insights.
*   **Projects Section:** 
    *   Three `<article>` cards.
    *   Each card contains: Project Title, Tech Stack (Tags), Key Insight/Result, and a "View Project" button.
*   **Contact Section:** Links for Email, LinkedIn, and GitHub.

#### **Step 3: Styling (`style.css`)**
*   Use CSS Flexbox/Grid for the project layout (1 column on mobile, 3 columns on desktop).
*   Add subtle hover effects on project cards (border glow or slight lift).
*   Ensure high contrast and readability using CSS variables.

#### **Step 4: Content Population**
Three high-impact projects:
1.  **E-commerce Customer Segmentation:** RFM analysis using Python/SQL.
2.  **Financial Dashboard:** Interactive visualization using Tableau/PowerBI.
3.  **Predictive Sales Model:** Time-series forecasting using Scikit-learn.

#### **Step 5: Deployment to GitHub Pages**
1.  Initialize a Git repository.
2.  Push code to a GitHub repository.
3.  Enable **GitHub Pages** in repository settings.

### 3. Verification Plan
*   **Lighthouse Audit:** Ensure high scores for Performance and SEO.
*   **Responsiveness:** Test on mobile and desktop views.
*   **Link Check:** Verify all social and project links.
