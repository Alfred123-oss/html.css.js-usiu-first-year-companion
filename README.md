# USIU First-Year Companion (v1)

Audience & Context
This project is aimed at new USIU-A students during Orientation Week. It provides a quick “First-Year Companion” microsite that welcomes students, introduces them to campus budgeting, and gives a friendly, interactive first experience with technology.

Core Jobs (v1)

Personalized greeting: Prompt for name, greet student with “Karibu, [Name]”, log to console, and show on page.
Campus commute estimator: Collects user inputs via prompt() and calculates transport + snack costs. Provides a saving tip (cutting 10%). Displays results in a neat summary box.

Theme toggle: Allows student to switch between day mode (white/blue text) and night mode (dark background, white text).

Constraints

Vanilla HTML/CSS/JS only (no libraries, no network calls).
Must run inside a Docker container via Nginx.
Success Criteria
Loads instantly.
Prompts user once at start.
Estimator calculates correctly.
Clear summary visible on page.
Theme toggle works.
No console errors.
Runs locally and inside Docker.

2. Wireframes (/design/)

wireframe-home.png → Greeting screen with personalized message + buttons.

wireframe-estimator.png → Estimator prompt → summary box.

notes.md → Short explanations of each screen & JS role.