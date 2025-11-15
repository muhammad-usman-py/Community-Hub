# 🌐 CommunityHub Website
### IICT Fall 2025 — National University of Computer & Emerging Sciences  
**Team Members:**  
- 🧑‍💻 Usman (Leader)  
- 👨‍💻 Hammad  
- 👨‍💻 Maaz  

---

## 🧠 Project Overview
This is our **Community Hub Website** for the IICT Fall 2025 project.  
It is made with **only HTML and CSS** — no JavaScript, no templates, and no CMS.

The website has **6 pages** that connect people in a community:
- 🏠 Welcome Page  
- 📰 Community News  
- 🎉 Local Events  
- 🏪 Directory of Local Businesses  
- 📚 Resource Center  
- 📞 Contact & Feedback  

---

## 🗂️ Folder & File Structure (Explained Simply)



```
CommunityHub/
│
├── index.html                    ← Usman: Welcome (main landing)
├── community-news.html           ← Hammad: Community News
├── local-events.html             ← Hammad: Local Events
├── directory.html                ← Maaz: Directory of Local Businesses
├── resources.html                ← Maaz: Resource Center
├── contact.html                  ← Usman: Contact & Feedback
│
├── css/
│   ├── style.css                 ← Base layout, navbar, typography, global colors
│   ├── pages.css                 ← Page-specific tweaks (accordion, grid, tabs)
│   └── themes.css                ← Dark/Light mode (CSS variables + toggle)
│
├── images/
│   ├── logo.png
│   ├── welcome/                  ← Hero images for landing page
│   ├── news/                     ← Thumbnails & carousel images
│   ├── events/                   ← Event posters/banners
│   ├── directory/                ← Business logos/photos
│   └── resources/                ← Resource icons or PDFs
│
├── fonts/                        ← (Optional) Custom or Google font downloads
│
├── report/
│   └── CommunityHub_Report.docx  ← Required report for submission
│
├── README.md                     ← Optional: Project overview, member roles
└── .gitignore                    ← Optional: To ignore temporary files if using Git
```

---

## 👥 Member Responsibilities

| Member | Pages | CSS Focus | Description |
|---------|--------|-----------|--------------|
| **Usman (Leader)** | `index.html`, `contact.html` | `style.css`, `themes.css` | Sets base layout, navbar, footer, dark/light mode |
| **Maaz** | `community-news.html`, `local-events.html` | `pages.css` | Adds news accordion, image carousel, and event grid |
| **Hammad** | `directory.html`, `resources.html` | `pages.css` | Builds business directory grid and tabbed resources layout |

---

## 🎨 Design Rules
- Use the **same navbar and footer** on all pages.  
- Stick to the **color theme:** blue (#0078FF), white (#FFFFFF), light gray (#F4F4F4).  
- Add **hover animations** (`transition: all 0.3s ease;`) for buttons and cards.  
- Make it **responsive** using CSS media queries.  
- Use **Google Fonts** (e.g., *Poppins*, *Roboto*).  
- Add a **Dark/Light theme toggle** using CSS variables (in `themes.css`).

---

## 🧑‍💻 GitHub Workflow (Simple Version)
1. **Usman** created the repo and invited **Hammad** and **Maaz**.  
2. Everyone clones the repo:
   ```bash
   git clone https://github.com/UsmanUsername/CommunityHub.git
