Modern SaaS Landing Page 🚀

A fully responsive, high-performance landing page designed for a SaaS product. Built with Semantic HTML and Tailwind CSS, featuring a custom dark mode toggle, responsive grid layouts, and interactive pricing cards.

🔗 Live Demo

View the Live Project Here

📸 Screenshots

Light Mode

Dark Mode





(Note: You will need to take screenshots of your site and save them in your public folder to make these appear!)



🛠️ Tech Stack

Core: Semantic HTML5

Styling: Tailwind CSS (Utility-First Framework)

Scripting: Vanilla JavaScript (for Theme Toggling)

Typography: Google Fonts (Nunito)

Icons: Heroicons (SVG)

✨ Key Features

🎨 Fully Responsive Design: Utilizes Tailwind's breakpoint system (md:, lg:) to ensure a seamless experience from mobile devices to large desktops.

🌙 Dark Mode Support: Implemented a manual theme toggle using Tailwind's darkMode: 'class' strategy and local state management via JavaScript.

🧩 Component Extraction: Used Tailwind's @apply directive to create reusable .card and .btn components, keeping the HTML clean while maintaining utility-first flexibility.

⚡ JIT Compilation: Configured the Tailwind CLI build process for optimized production builds.

💎 Modern UI/UX: Features glass-morphism effects, hover transitions, and a minimalist monochrome aesthetic.

🧠 What I Learned

Building this project deepened my understanding of the Tailwind ecosystem:

Tailwind Configuration: I learned how to customize the tailwind.config.js file to extend the default theme, add custom fonts (Nunito), and configure content scanning paths.

The @apply Directive: I learned when to use utility classes directly in HTML vs. extracting them into CSS components for maintainability.

Flexbox & Grid: I combined Flexbox (for internal card layout) and CSS Grid (for the main page layout) to create a robust structure.

Dark Mode Logic: I learned how to toggle classes on the <html> element to trigger Tailwind's dark: modifiers.

💻 Running Locally

If you want to view or edit the code source:

Clone the repository

git clone [https://github.com/YOUR-USERNAME/ninja-food-saas.git](https://github.com/YOUR-USERNAME/ninja-food-saas.git)
cd ninja-food-saas


Install Dependencies

npm install


Run the Build Process
This project uses the Tailwind CLI to generate styles.

npm run build-css


Open index.html in your browser or use the VS Code Live Server extension.

📄 License

This project is open source and available under the MIT License.

Built with ❤️ by [Your Name]
