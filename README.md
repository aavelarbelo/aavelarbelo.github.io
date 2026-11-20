# Andressa Avelar — Personal Website

**Author:** Andressa Avelar Belo · [LinkedIn](https://linkedin.com/in/andressaavelar) · [GitHub](https://github.com/aavelarbelo) · eng.belo@gmail.com

Source code of my personal website and portfolio, published with GitHub Pages:
**[aavelarbelo.github.io](https://aavelarbelo.github.io/)**

![GitHub Pages](https://img.shields.io/badge/deployed%20with-GitHub%20Pages-blue)
![No dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)

> Junior Data Engineer with a Control & Automation Engineering background and a Postgraduate
> Diploma in Big Data & Decision Making (ISEP, Porto, 2026). Authorised to work in Portugal.
>
> **Status:** live. The site is updated together with my projects and my profile README.

## What the site shows

| Section | Content |
|---|---|
| About | Background, transition into data, the LLM workflow I run in production |
| Skills | Core stack, postgraduate foundations, LLM applications, what I am currently learning |
| Experience | INEGI (research), SIEL Engenharia (cost estimates, sales KPIs, projects), earlier roles |
| Education | ISEP postgraduate diploma, FEUP, BSc in Control & Automation Engineering |
| Projects | LLM Job Application Assistant, UrbanEco Analytics, Customer Churn Prediction |
| Contact | LinkedIn, GitHub, email |

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| [LLM Job Application Assistant](https://github.com/aavelarbelo/llm-job-application-assistant) | Daily n8n workflow that scores job postings against a verified profile with the Claude API and drafts a tailored CV and cover letter; I review and submit every application myself | n8n · Claude API · Python · Gmail · Google Sheets |
| [UrbanEco Analytics](https://github.com/aavelarbelo/urbaneco-analytics) | Group final project (ISEP, 16/20): energy efficiency vs. asking price per m² in Porto. My part: scraper, cleaning, PostgreSQL in Docker, dashboard review | Python · Selenium · pandas · PostgreSQL · Docker · Power BI |
| [Customer Churn Prediction](https://github.com/aavelarbelo/data-mining-churn-prediction) | CRISP-DM churn project comparing KNN, Decision Tree, SVM and Naive Bayes | Python · pandas · scikit-learn |

## How it is built

- One `index.html` file: HTML, CSS and vanilla JavaScript, no frameworks and no build step.
- Intro with a Matrix-style code rain and typewriter (canvas), then a circuit-board tree drawn on a
  second canvas as the background.
- Sections appear on scroll (Intersection Observer).
- Respects `prefers-reduced-motion`: users who turn animations off go straight to the content.

## Running it locally

```bash
git clone https://github.com/aavelarbelo/aavelarbelo.github.io
cd aavelarbelo.github.io
python -m http.server 8000   # then open http://localhost:8000
```

Opening `index.html` directly in the browser also works.

## Repository structure

```text
aavelarbelo.github.io/
├── index.html   # the whole site
└── README.md
```

## Related

- [GitHub profile README](https://github.com/aavelarbelo/aavelarbelo): kept in a separate repository.

---

© Andressa Avelar Belo
