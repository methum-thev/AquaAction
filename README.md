AquaAction Project Documentation: UN SDG 06 Platform
Project Overview
AquaAction is a student-led web application designed to promote UN Sustainable Development Goal 06: Clean Water and Sanitation. The platform serves as an educational and interactive mission to convert global sustainability goals into actionable daily habits, emphasizing that clean water is a fundamental human right rather than a luxury.

Core Features and Functionality
The platform provides a comprehensive suite of interactive modules:

Animated Splash Screen: Features a canvas-based water environment simulation with floating particles, ripple animations, and a synchronized countdown timer for user onboarding.

Mission Landing Page: Includes a professional hero section with a linear-gradient overlay, mission-driven cards, and a direct call-to-action for joining the sustainable initiative.

Innovation Gallery: A dynamic 3x2 grid of portrait cards showcasing water technologies such as Rainwater Harvesting and Solar Desalination; integrated with JavaScript-driven modal pop-ups for detailed technical insights.

Action Impact Simulator (AIS): An interactive JavaScript application that allows users to select water-related actions and receive real-time, dynamic feedback on their combined environmental impact through scoring logic.

Progressive User Profile: A guided multi-step builder that progressively reveals a user's SDG engagement profile while tracking completion via a dynamic progress bar updated through DOM manipulation.

Visual Website Sitemap: A hand-coded inline SVG diagram representing the site hierarchy, featuring CSS-based interactive nodes, hover effects, and enhanced keyboard accessibility focus states.

Specialized Content Research: Detailed awareness sections covering Water Conservation (ST1), Sanitation Systems (ST2), and Future Innovations in water tech, such as smart grids and precision agriculture (ST4).

Technical Architecture
The project is built using modern web standards to ensure high performance and accessibility:

Structure: Semantic HTML5 markup utilized with a shared template to maintain a consistent header, navigation bar, and footer across all sub-pages.

Styling: A centralized "Dark Abyss" theme implemented via a global CSS file using custom properties (variables) for consistent branding (Teal: #2a8da7, Dark Abyss: #1d5d6f).

Interactivity: JavaScript (ES6+) for DOM manipulation, asynchronous state management for gallery modals, and real-time impact scoring in the simulator.

Accessibility: Compliance with WCAG 2.1 standards, including a custom targeted text-scaling system (Requirement C) via a floating action button, high color contrast, and semantic ARIA roles.

Responsive Design: Mobile-first approach using CSS Grid (auto-fit/minmax logic) and Flexbox for seamless cross-device compatibility.

Directory Structure
-------------------
AquaAction/
├── images/               # Optimized assets for content and innovation gallery
├── validationSnapshots/  # Documentation of W3C compliance
├── style.css             # Global branding and theme definitions
├── home.html             # Project landing page
├── gallery.html          # Interactive innovation showcase
├── ais.html              # Action Impact Simulator interactive tool
├── content_ST1.html      # Water Conservation awareness content
├── content_ST4.html      # Future Innovation research content
├── sitemap.html          # Interactive SVG visual sitemap
└── profile.html          # Progressive profile builder system
Team Contributions
The project was developed collaboratively with defined individual responsibilities:

Student 1 (Methum Thevjan Weeratunga): Technical Implementation Lead. Responsible for the global CSS framework, shared template, Home page, Innovation Gallery, and the Water Conservation content page.

Student 2 (Sachith Pamoda Wattaranthenna): Interaction Specialist. Developed the Splash Screen, the Action Impact Simulator logic, and the Sanitation Systems content page.

Student 4 (T S Thewnuja Rajasinghe): Information Architect. Engineered the Progressive User Profile builder, the hand-coded SVG Sitemap, and the Future Innovation content page.

Standards and Compliance
W3C Validation: All individual pages and the global stylesheet have passed HTML5 and CSS3 validation with no errors.

Regulation: Adheres to JANET acceptable use policies governing academic web publication.

Attribution: All research data and imagery from institutions (such as the UN, USAID, ResearchGate, and Scielo) are correctly referenced in the individual page editors.
