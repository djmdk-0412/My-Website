Madhuka Gihan — Personal Portfolio

Overview:
- Simple, responsive portfolio site built with HTML + Tailwind CSS.
- Showcases education, projects, skills, and contact information.

Features:
- Hero section with background image and CTA buttons
- Responsive navigation with mobile menu toggle (JS)
- Sections: About, Skills, Education, Projects, Contact, Footer
- Animations via AOS, icons via Font Awesome
- Tailwind configured inline for brand colors & font

How to view locally:
1. Open `index.html` in your browser (double-click). This works for static demos.
2. (Recommended) Use a local dev server for correct path handling and faster refreshes:
   - VS Code: install 'Live Server' extension and choose "Open with Live Server".
   - Python: run `python -m http.server 8000` in the project folder and open `http://localhost:8000`.

File structure:
- `index.html`       — Main site markup
- `style.css`        — (Optional) custom styles (if present)
- `main.js`          — (Optional) additional JS (if present)
- `assets/`          — images, `CV.pdf`, and other static files

Notes & Known Issues (small):
- There is an extra `<html class="scroll-smooth">` tag inside the navigation; it is redundant and can be removed.
- Some commented anchor tags appear as `<!a ...` in the Contact section and the WhatsApp anchor has a malformed tag — these may break HTML validation and should be fixed.
- Some image paths use backslashes (e.g., `assets\madhuka.jpeg`) — prefer forward slashes (`assets/madhuka.jpeg`) for cross-platform compatibility.

Customisation tips:
- Update brand colors in the inline `tailwind.config` script.
- Replace placeholder images and update `assets/CV.pdf` to your latest CV.
- Update links (LinkedIn, GitHub, email) in the Contact section.

Dependencies (CDN):
- Tailwind CSS (via CDN)
- Font Awesome (icons)
- AOS (scroll animations)

License & Contact:
- Add your preferred license file if you want to publish this project (e.g., `LICENSE` with MIT).
- For help or edits, contact: djmdk0412@gmail.com

Contributing:
- Fork the repo, make changes, and open a PR. Keep CSS/JS small and self-contained for this static project.

Enjoy your portfolio! ✨
