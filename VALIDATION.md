# Validation report

Tested October 26, 2026 against the production website.

- Public URL, CSS, JavaScript, portrait, and all four project images returned HTTP 200 without authentication.
- Browser viewport checks: 1440x900 desktop, 1366x768 laptop, 768x1024 tablet, and 390x844 phone. No horizontal page overflow; representative layouts visually reviewed.
- Additional 320px phone-width overflow check passed locally.
- Mobile menu opens and closes after navigation. Escape closes the menu and returns focus.
- Profile, Skills, Projects, Education, and Contact navigation produce their matching section URLs.
- Project filters show two Web projects, two Design projects, and four All projects.
- All five production images loaded successfully with descriptive alternative text.
- No browser console errors recorded during production interaction checks.
- GitHub profile, NaviFlow demo, and both Figma design URLs returned HTTP 200.
- Email link uses mailto:irl27.pena@gmail.com. No email was sent.
- LinkedIn returned its automated-access error 999; independent profile availability remains unverified.
- Print action calls the browser print function. The browser automation timed out on that action; final print/PDF appearance was not verified.
- Device tests use browser viewport simulation, not physical hardware or multiple browser engines.

Source history contains genuine commits for the CV foundation, GitHub correction, and deployment/validation documentation. No history was fabricated or backdated.

## Animation update

Local browser check confirmed hero/accent animations are active, the motion stylesheet loads, Web/All filters show 2/4 cards, and no console errors or horizontal overflow were observed at the tested viewport. Reduced-motion CSS disables animation and transition; filter animation checks the motion preference before running.
