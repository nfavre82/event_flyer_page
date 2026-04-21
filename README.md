# 🌸 Event Flyer Page — The Blooming Orchid Yoga Studio
## FreeCodeCamp Compliant Version — `main` branch
 
This is the **FreeCodeCamp-compliant version** of the Event Flyer Page project, built as part of the FreeCodeCamp Responsive Web Design curriculum. The page is a fictional event flyer for the **Spring Yoga Festival 2026**, hosted by the imaginary **The Blooming Orchid Yoga Studio**.
 
This branch represents the version that was successfully submitted to and validated by the FreeCodeCamp platform. ✅
 
---
 
## 🌿 About This Branch
 
The `main` branch contains the version of the project that strictly meets all FreeCodeCamp curriculum requirements. Every design and layout decision was made with compliance in mind, while still aiming for a clean, readable, and pleasant visual result.
 
For the creative and personal portfolio version of this project, please visit the `portfolio` branch.
 
---
 
## 🎓 What I Learned & Practiced
 
This project was a rich learning experience that allowed me to practice and consolidate a wide range of HTML and CSS skills.
 
### 📐 Absolute and Relative Units in CSS
 
One of the key focuses of this project was understanding the difference between absolute and relative units, and knowing when to use each appropriately:
 
- **`px`** — used for precise, fixed values such as border thickness and font sizes where consistency matters
- **`%`** — used for widths of `hr` and `section` elements relative to their parent container, as required by the FreeCodeCamp curriculum
- **`vw`** — used to set the `width` of the `body` relative to the viewport width, ensuring the layout adapts to different screen sizes
- **`vh`** — used in combination with the `calc()` function to set the `min-height` of the `body` relative to the viewport height
- **`rem`** — used for spacing (margins, paddings, gaps) to maintain consistent rhythm across the page
- **`em`** — explored and understood as a unit relative to the parent element's font size
### 🧮 The `calc()` Function
 
A particularly satisfying requirement was using the `calc()` function to set the body's `min-height` dynamically:
 
```css
min-height: calc(100vh - 100px);
```
 
This subtracts the total vertical padding (`50px` top + `50px` bottom) from the full viewport height — ensuring the body always fills the screen correctly regardless of its content.
 
### 📦 CSS Flexbox & Grid
 
- **Flexbox** — used to structure and center the header content (logo, festival image, title, and presentation text) along a vertical axis
- **CSS Grid** — used to display the event cards in a responsive three-column layout using `repeat(3, 1fr)`
### 🌐 Other Key CSS Concepts Practiced
 
- CSS linear gradients for background and decorative `hr` elements
- Google Fonts integration (`Archivo Black` and `Bitter`)
- Semantic HTML structure with `header`, `main`, `section`, `article`, and `footer`
- Class-based styling for reusable and maintainable CSS rules

---
 
## 🛠️ Technologies Used
 
- **HTML5** — semantic structure and content
- **CSS3** — Flexbox, Grid, relative units, `calc()`, and linear gradients
- **Google Fonts** — Archivo Black & Bitter typefaces
- **Git & GitHub** — version control and branch management

---
 
## ✨ Key Features
 
- Event flyer layout structured with a clear visual hierarchy
- Header with festival image, title, and event details centered using Flexbox
- Nine event cards displayed in a three-column CSS Grid layout
- Horizontal rules styled with a soft gradient divider
- Body width set with `vw` and `min-height` calculated with `calc()`
- Clean typographic pairing between Archivo Black (headings) and Bitter (body text)

---
 
## 🔗 2. Live Demo & Repository

### 🌐 Live Demo (GitHub Page): 
  
**GitHub Page:** You can view the live version of this project on its dedicated 👉[GitHub Page](https://nfavre82.github.io/event_flyer_page/). The version published is the **portfolio branch version**.

 ### 📁 Repository and Branches Source Codes: 

- 📁 **Root Repository:** You can consult the root repository of this project on its dedicated 👉 [GitHub repository](https://github.com/nfavre82/event_flyer_page)
- 🌿 **Main Branch - Source Code:** You can consult the source code for the main branch on its dedicated 👉 [main branch page](https://github.com/nfavre82/event_flyer_page/tree/main)
- 🎨 **Portfolio Branch - Source Code:** You can consult the source code for the Portfolio branch on its dedicated 👉 [portfolio branch page](https://github.com/nfavre82/event_flyer_page/tree/portfolio)

---
 
## 🙏 Credits
 
- **Project context:** [FreeCodeCamp](https://www.freecodecamp.org/) — Responsive Web Design Curriculum
- **Author:** **NF Web Development Studio**  
© 2026