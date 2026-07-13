# Idayat Sanni — Portfolio

Personal portfolio site showcasing AI, data, and web development projects.

**Live site:** [idayatsannia.netlify.app](https://idayatsannia.netlify.app)

---

## About

I'm an AI Integration & Governance student at Humber College, building practical,
deployable AI and data solutions. This site is where I share what I've built —
from AI-powered automation tools to machine learning models and data analysis.

## Pages

| Page             | Description                                                                                     |
| ---------------- | ----------------------------------------------------------------------------------------------- |
| `index.html`     | Home — intro, tagline, and featured project cards                                               |
| `about.html`     | Background, skills, and experience timeline                                                     |
| `projects.html`  | Full list of projects with links to case studies                                                |
| `project-*.html` | Individual case study pages for each project (write-up, images, embedded video, what I learned) |

## Projects featured

- **AI-Powered WhatsApp Finance Assistant** — n8n, WhatsApp Business API (capstone project)
- **Payment Default Risk Model** — Azure ML Designer, AutoML, binary classification
- **Retail Superstore EDA** — Python, Pandas, Matplotlib/Seaborn
- **BookAndBite2** — ASP.NET Core MVC, C#

## Built with

- HTML5, CSS3, vanilla JavaScript
- Google Fonts: Space Grotesk, IBM Plex Sans, IBM Plex Mono
- Hosted on [Netlify](https://netlify.com)

## Project structure

```
├── index.html
├── about.html
├── projects.html
├── project-whatsapp-assistant.html
├── project-default-risk-model.html
├── project-retail-eda.html
├── project-bookandbite.html
├── style.css
└── assets/
    ├── js/
    │   └── script.js
    └── img/
        ├── Idayat.jpg              (profile photo)
        └── projects/             (project cover images & screenshots)
```

## Running locally

No build step required — it's plain HTML/CSS/JS.

```bash
# clone the repo
git clone https://github.com/IdayatSanni/portfolio.git
cd portfolio

# open directly in a browser
open index.html

# or serve it locally
python3 -m http.server 8000
```

## Deployment

Deployed via Netlify, connected to this repo's `main` branch. Any push to `main`
triggers a new deploy.

## Contact

- LinkedIn: [linkedin.com/in/idayat-sanni](https://linkedin.com/in/idayat-sanni)
- GitHub: [github.com/IdayatSanni](https://github.com/IdayatSanni)
- Portfolio: [idayatsannia.netlify.app](https://idayatsannia.netlify.app)
