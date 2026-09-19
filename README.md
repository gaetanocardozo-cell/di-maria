# 🎬 Di Maria Jawns - Movie Club

A feature-rich web application built for a private film club to log, rate, and review movies, curate custom lists, and analyze community viewing statistics.

[👉 View Live Application](https://dimariajawns.netlify.app/)

---

## ✨ Core Features

* **Movie Logging & Reviews:** Search TMDB to log viewings, add custom ratings, tag rewatches, and assign favorite performances.
* **Community Feed & Profiles:** View club-wide logs, leave comments, and explore detailed individual member profile statistics.
* **Custom Film Lists:** Build, rank, and curate custom movie collections with dynamic backdrop banners.
* **Letterboxd Data Importer:** Parse and import full Letterboxd ZIP archives (diary entries, ratings, reviews, and watchlists) with automated deduplication.
* **Analytics & Club Leaderboards:** Dedicated statistics dashboard featuring top-ranked films, director performance metrics, decade distributions, and cumulative cinema time.
* **TMDB Match Verification:** In-app metadata scanner and auto-fix tooling to detect and resolve mismatched movie IDs across member logs.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, Tailwind CSS (via CDN), Alpine.js (reactive client-side state)
* **Backend & Auth:** Supabase (PostgreSQL, Row Level Security, Auth API)
* **External APIs:** The Movie Database (TMDB API) for metadata, posters, and cast details
* **Data Processing:** JSZip & PapaParse (client-side CSV/ZIP parsing)
* **Hosting & CI/CD:** Netlify

---

## 🚀 Getting Started

Since this is a client-side application using CDN dependencies, running it locally requires no build process:

1. Clone or download this repository.
2. Open `index.html` directly in any modern browser.
