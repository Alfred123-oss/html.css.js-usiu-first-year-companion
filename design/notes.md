 USIU First-Year Companion v1 – Wireframe Notes

 Wireframe 1: Home (wireframe-home.png)
- Shows the initial landing page for new students.
- Personalized greeting at the top (from JavaScript `prompt()`).
- Two main buttons:
  - Run Estimator → triggers prompts to calculate costs.
  - Toggle Theme → switches between light and dark mode.
  - Reset → clears the weekly summary.
- Weekly Summary Box is initially empty with placeholder text.
- Footer credits USIU Student Affairs.

Wireframe 2: Estimator (wireframe-estimator.png)
- Represents the flow of prompts that gather:
  - Days on campus per week
  - Transport cost per trip
  - Snacks per day
  - Average snack price
- The output is calculated and shown inside the Weekly Summary box on the home page.
- Console logs all raw values for debugging.
- Includes the “save 10%” tip, encouraging better budgeting.

 Design Rationale
- Mobile-first: Layout is kept single-column for small screens.
- Accessibility: Clear headings, semantic structure, good color contrast.
- Theme: Toggle provides dark/light mode for readability.
- Debugging: Console.log ensures visibility of raw values during tests.

Export/Implementation Note
- The ASCII wireframes here should be redrawn in Figma or by hand.
- Save final wireframes as:
  - `/design/wireframe-home.png`
  - `/design/wireframe-estimator.png`
- Include this `notes.md` alongside them in `/design/`.
