# GITSAM LAB | Design Studio 🎨

> "느좋코딩 좋문 좋소기업 깃샘"

This repository serves as a central **Hub** for various experimental projects (**Spokes**). It features a gamified UI inspired by the **Bauhaus** design movement—using primary colors, thick borders, and geometric shapes.

## 📂 Project Structure

- `index.html`: The central **Hub** dashboard with a retro Slot Machine interface.
- `spoke.json`: The source of truth for all **Spoke** (project) data.
- `screenshot/`: Contains visual thumbnails for the project cards.

## ⚙️ Hub & Spoke Model

This project follows a decoupled approach:
1.  **Data (JSON)**: All project metadata (repo, url, title, description) is managed in `spoke.json`.
2.  **Logic (JS)**: The Hub dynamically renders project cards and handles category filtering.
3.  **UI (HTML/CSS)**: A gamified slot-machine header and Bauhaus-style grid provide a unique exploration experience.

## 🎨 Design Philosophy

- **Style**: Bauhaus (Minimalism, Geometric, Primary Colors)
- **Experience**: Gamified navigation (Slot machine spinning)
- **Tech**: Vanilla HTML/JS + Tailwind CSS (Native API prioritized)

---
© 2026 / gitsam / KR
