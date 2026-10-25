# Prime Video Content Analysis | Power BI

> **My first Power BI dashboard.** Built as a *shadow learning* project: I followed a YouTube tutorial step by step to learn the Power BI workflow, then used what I learned to build my second project from scratch on my own: [Healthcare RCM Analytics Dashboard](https://github.com/YOUR-USERNAME/rcm-powerbi-dashboard).

![Prime Video dashboard](Screenshots/01_dashboard.png)

---

## Why I built this (shadow learning)

I work in healthcare revenue cycle (AR) and I am moving into data analytics. I had no hands-on Power BI experience, so I started the way many people learn a new tool: **shadow learning**. I watched a tutorial, built the same dashboard alongside the instructor, paused to understand each step, and rebuilt the parts I got wrong.

This project is **not** presented as an original analysis. It is a learning exercise that gave me the foundation for my independent work:

| Stage | Project | How it was built |
|---|---|---|
| 1 | **Prime Video Content Analysis** (this repo) | Followed a YouTube tutorial to learn the basics |
| 2 | [Healthcare RCM Analytics Dashboard](https://github.com/YOUR-USERNAME/rcm-powerbi-dashboard) | Designed and built by me, step by step, on a healthcare domain I know |

**Tutorial credit:** [TUTORIAL TITLE](PASTE-YOUTUBE-LINK) by **CHANNEL NAME**. All credit for the original dashboard design goes to the creator.

---

## What the dashboard shows

The dashboard summarises the Amazon Prime Video catalogue (9,651 titles, release years 1920 to 2021).

- **KPI cards:** total titles, rating categories, genre categories, directors, start year, end year
- **Ratings by total shows:** how many titles sit in each rating (13+, 16+, ALL, 18+, R and others)
- **Genres by total shows:** the most common genre combinations (Drama, Comedy, Drama/Suspense and others)
- **Total shows by country:** a map of where titles come from
- **Movies vs TV shows:** about 81% movies (7.81K) and 19% TV shows (1.85K)
- **Total shows by release year:** a trend line for movies and TV shows, which grows sharply after 2000

### Quick observations

- Movies make up roughly four out of five titles in the catalogue.
- Drama is the biggest single genre category (986 titles), followed by Comedy (536).
- 13+ is the most common rating (2,117 titles), ahead of 16+ (1,547).
- Titles added by release year rise steeply from around 2000, peaking near 2020.

---

## Skills practised

- Loading and cleaning data with **Power Query**
- Building **KPI cards**, **bar charts**, a **map**, a **donut chart** and an **area chart**
- Dashboard layout, colour theme and consistent formatting
- Basic **DAX measures** for counts and distinct counts
- Publishing a project to **GitHub** with a README

---

## Dataset

Amazon Prime Video titles dataset: [DATASET NAME](PASTE-DATASET-LINK).
Columns include show id, type (movie or TV show), title, director, country, release year, rating, duration and genres (`listed_in`).

## Files

| Path | What it is |
|---|---|
| `powerbi/Prime_Video_Dashboard.pbix` | The Power BI report |
| `screenshots/` | Dashboard screenshots |
| `data/` | Dataset (only if the licence allows redistribution, otherwise use the link above) |

## How to open

1. Download the `.pbix` file and open it in **Power BI Desktop** (free).
2. If Power BI asks for the data location: **Transform data → Data source settings → Change source**.

## Limitations

- Learning project built from a tutorial, so the questions and layout are not my own design.
- "Genres" counts unique genre *combinations* as listed in the data (for example "Drama, Suspense"), not individual genres.
- Some titles have a blank rating in the source data.

## Disclaimer

This is an unofficial, educational project. It is not affiliated with or endorsed by Amazon or Prime Video. The Prime Video name and logo belong to Amazon.

---

**Gokul Selvam K A** · Coimbatore · [LinkedIn](PASTE-LINKEDIN-LINK) · [GitHub](https://github.com/YOUR-USERNAME)
