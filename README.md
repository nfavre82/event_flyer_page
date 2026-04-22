# 🌸 Event Flyer Page — The Blooming Orchid Yoga Studio
## Creative Portfolio Version — `portfolio` branch
 
This is the **personal portfolio version** of the Event Flyer Page project — an enhanced, creatively styled iteration of the FreeCodeCamp-compliant version found on the `main` branch. While the core HTML structure and content remain the same, this version reflects my own design sensibility, creative choices, and the additional skills I learned and practiced along the way.
 
This is the version deployed as [a live GitHub Page](https://nfavre82.github.io/event_flyer_page). ✅
 
---
 
## 🌿 About This Branch
 
The `portfolio` branch was created as a dedicated space to push the project beyond the FreeCodeCamp requirements — experimenting with visual design, SVG illustration, responsive design, and Git branch management. Every addition in this version was an opportunity to learn something new.
 
For the FreeCodeCamp-compliant version of this project, please visit the `main` branch.
 
---
 
## 🎨 Creative & Styling Additions
 
### 🖌️ Enhanced CSS Styling
 
The visual identity of this version was developed around a carefully chosen three-color palette — `#FAA9BE` (soft pink), `#91B849` (fresh green), and `#F8D940` (warm yellow) — inspired by the fictional brand of The Blooming Orchid Yoga Studio.
 
Key styling decisions include:
 
- A **three-tone pastel gradient background** (`#fef6f9` → `#fdfbe8` → `#f8fef0`) that subtly weaves all three brand colors across the full page height
- **Event cards** styled with a soft diagonal gradient and a delicate green border, creating a cohesive visual rhythm with the background
- A **decorative `hr` divider** using a green-toned gradient that fades gracefully on both sides
- Careful typographic pairing between **Archivo Black** (headings) and **Bitter** (body text), chosen for their complementary contrast between geometric boldness and warm serif elegance
### 🌺 Custom SVG Logo
 
One of the most exciting additions to this version was the design and integration of a **custom SVG logo** for the fictional Blooming Orchid Yoga Studio — built entirely in code, without any external design software.
 
The logo features:
- A **naturaliste and fluid orchid flower** composed of layered ellipses in pink (`#FAA9BE`) and yellow (`#F8D940`), rotating symmetrically around a green center (`#91B849`)
- A **stylized stem and leaves** drawn with SVG `path` and `ellipse` elements
- The studio name typeset in two lines: **"THE BLOOMING ORCHID"** in green and **"YOGA STUDIO"** in yellow, using Georgia serif with generous letter-spacing
The logo was saved as a standalone `logo.svg` file in the `assets/` folder and linked in `index.html` via a standard `<img>` tag. It was then styled with CSS — positioned to the left of the header using `align-self: flex-start`, with carefully chosen dimensions and spacing.
 
### 📱 Mobile Responsive Design — First Time with Media Queries !
 
This was my **first ever experience writing media queries** — and a genuinely exciting milestone. I learned how CSS media queries work, what breakpoints are, and how to use them to adapt a desktop layout for smaller screens.
 
I implemented a mobile breakpoint at `max-width: 480px`, with the following adaptations:
 
- The **CSS Grid** switches from three columns to a single column (`grid-template-columns: 1fr`)
- The **logo** is recentered and reduced in size
- The **festival image** expands to `85%` width for better mobile readability
- **Font sizes** are scaled down across headings, descriptions, and footer text
- **Spacing and padding** are adjusted throughout for a comfortable mobile experience

---
 
## 🧠 Git & GitHub Skills Learned
 
Managing this portfolio version was also a significant Git learning journey :
 
- **Created and set up a second branch** (`portfolio`) from `main`
- **Learned what branches are** and understood their purpose — maintaining parallel versions of a project without affecting the stable main version
- **Restructured the project tree** — reorganized the repo from a two-subfolder structure (`fcc_version/` and `portfolio_version/`) to a clean single-file structure at the root of each branch
- **Merged changes** from `main` into `portfolio` using `git merge`
- **Resolved merge conflicts** — learned to read conflict markers, understand `--theirs` and `--ours`, and commit the resolved result
- **Deployed the portfolio branch** as a live GitHub Pages site

---
 
## 🛠️ Technologies Used
 
- **HTML5** — semantic structure and content
- **CSS3** — Flexbox, Grid, gradients, media queries, and custom SVG styling
- **SVG** — custom orchid logo designed and coded entirely by hand
- **Google Fonts** — Archivo Black & Bitter typefaces
- **Git & GitHub** — branch management, merging, conflict resolution, and GitHub Pages deployment

---
 
## ✨ Key Features
 
- Three-tone pastel gradient background inspired by the studio's brand palette
- Custom hand-coded SVG orchid logo integrated into the header
- Event cards styled with a soft diagonal gradient and green border
- Nine event cards displayed in a responsive CSS Grid layout
- Mobile-responsive design with media queries at `480px`
- Live deployment via GitHub Pages

---
 
## 🔗 Live Demo & Repository
 
### 🌐 Live Demo (GitHub Page)
 
**GitHub Page:** You can view the live version of this project on its dedicated 👉 [GitHub Page](https://nfavre82.github.io/event_flyer_page/). The version published is the **portfolio branch version**.
 
### 📁 Repository and Branches Source Code
  
- 📁 **Root Repository:** You can consult the root repository of this project on its dedicated 👉 [GitHub repository](https://github.com/nfavre82/event_flyer_page)
- 🌿 **Main Branch - Source Code:** You can view the source code for the main branch on its dedicatede 👉 [main branch page](https://github.com/nfavre82/event_flyer_page/tree/main)
- 🎨 **Portfolio Branch - Source Code:** You can view the source code for the portfolio branch on its dedicated 👉 [portfolio branch page](https://github.com/nfavre82/event_flyer_page/tree/portfolio)

---
 
## 🙏 Credits
 
- **Project context:** [FreeCodeCamp](https://www.freecodecamp.org/) — Responsive Web Design Curriculum
- **Author:** **NF Web Development Studio**
© 2026