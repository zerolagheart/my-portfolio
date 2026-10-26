# Titiksha Yadav — Interactive Portfolio

**Human-Computer Interaction · Human-Centered AI · Computer Vision · Product Design**

An interactive, futuristic portfolio exploring the intersection of machine learning, human experience, and interface design. Built to showcase selected projects, research interests, experience, and technical skills through an animated 3D visual experience.

<p align="center">
  <a href="https://my-portfolio-hci.vercel.app/">Live Portfolio</a> ·
  <a href="https://github.com/zerolagheart">GitHub Profile</a> ·
  <a href="mailto:titikshayadav6144@gmail.com">Contact</a>
</p>

---

## Overview

I am an Electronics Engineering undergraduate at Madhav Institute of Technology and Science (MITS), Gwalior, interested in building technology that is useful, adaptive, and human-centered.

My interests include human-computer interaction (HCI), affective computing, human-centered AI, computer vision, and UX research.

This portfolio brings together my selected projects, research interests, experience, and technical toolkit in one interactive website.

## Features

- **Interactive 3D background** — Animated wireframe geometry, particles, and orbiting elements powered by Three.js.
- **Responsive interface** — A dark visual system with gradient typography and glass-inspired cards.
- **Dynamic introduction** — Typing animation for research and design interests.
- **Interactive project cards** — Hover-based 3D tilt effects.
- **Scroll animations** — Sections and statistics reveal as visitors navigate the page.
- **Adaptive color themes** — Calm, focus, and energy modes.
- **Resume access** — A dedicated section for viewing or downloading the resume.
- **Direct contact** — Email and professional profile links.

## Selected Work

| Project | Focus |
|---|---|
| MoodOS | Emotion-adaptive interfaces and HCI |
| Vivere | AI-assisted mental wellness experiences |
| Helixx | Healthcare coordination and intelligent systems |
| Sentinel AI | AI visibility and answer-engine optimization |
| SafeRoute AI | Personal safety and accessible navigation |
| Lingofy | Language learning through music |

See the live portfolio for project descriptions, implementation details, and current project status.

## Technology Stack

- **Frontend:** HTML, CSS, JavaScript
- **3D graphics:** Three.js
- **Build tooling:** Python
- **Content management:** JSON
- **Deployment:** Vercel

## Project Structure

```text
titiksha-portfolio/
├── dist/          # Generated website for deployment
├── assets/        # Static assets, if used
├── app.js         # UI interactions and animations
├── build.py       # Generates the standalone HTML page
├── data.json      # Portfolio content and project data
├── scene3d.js     # Three.js scene and animation
├── style.css      # Styling, layout, and responsive rules
├── resume.pdf     # Public resume, if included
└── README.md
```

## Run Locally

### Requirements

- Python 3
- A modern web browser
- Internet access for the externally loaded Three.js module and Google Fonts

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/titiksha-portfolio.git
cd titiksha-portfolio
```

### 2. Generate the website

```bash
python build.py
```

The build script generates `dist/index.html`.

### 3. Preview the website

Open `dist/index.html` in your browser, or serve the generated folder locally:

```bash
python -m http.server 8000 --directory dist
```

Visit `http://localhost:8000`.

## Customization

- **Portfolio content:** Edit `data.json`.
- **Visual design:** Edit `style.css`.
- **UI interactions:** Edit `app.js`.
- **3D background:** Edit `scene3d.js`.
- **HTML generation:** Edit `build.py`.

After updating the source files, rerun `python build.py` to regenerate the website.

## Deployment

The generated website is static and can be hosted on Vercel or another static hosting provider.

For Vercel, configure the project to serve the generated `dist` directory. If using Git-based automatic deployments, ensure that the generated HTML and all referenced assets are included in the deployed output.

## Contact

**Titiksha Yadav**

- Email: [titikshayadav6144@gmail.com](mailto:titikshayadav6144@gmail.com)
- LinkedIn: [linkedin.com/in/titikshayadav](https://www.linkedin.com/in/titikshayadav/)

## License

See [LICENSE](LICENSE) for usage terms. Replace the license file with the license you choose before publishing.
