# 🌐 Filmawit Portfolio Website

Welcome to my personal portfolio website! This project showcases who I am, what I do, and how to get in touch. It highlights my experience, projects, and contact details in a clean, user-friendly way.

---

## 📖 Table of Contents

- [About the Project](#about-the-project)
- [User Stories](#user-stories)
- [Features](#features)
- [Future Enhancements](#future-enhancements)
- [Technologies Used](#technologies-used)
- [Testing](#testing)

  - [Manual Testing](#manual-testing)
  - [Responsiveness Testing](#responsiveness-testing)
  - [Validation Testing](#validation-testing)
  - [User Stories Testing](#user-stories-testing)
  - [Bugs and Fixes](#bugs-and-fixes)

- [Deployment](#deployment)
- [Credits](#credits)

---

## 📝 About the Project

I created this website to share my professional journey and skills as a **Front-End Developer, Project Manager, and Educator**.
The website includes:

- An **About Me** section with background information.
- A **Projects & Experience** section highlighting my work.
- A **Tech Stack** section showcasing tools I use.
- A **Contact Form** with email and LinkedIn integration.

The goal of the project is to serve as an online CV and portfolio, easily accessible to employers, collaborators, and peers.

---

## 👩‍💻 User Stories

As a user visiting this site:

1. I want to **quickly learn who Filmawit is**, so I can understand her background.
2. I want to **see examples of projects**, so I can judge her technical ability.
3. I want to **view professional experience**, so I can understand her career history.
4. I want to **check her tech stack**, so I know what tools she works with.
5. I want to **easily contact her**, so I can reach out with opportunities.

---

## ✨ Features

- **Responsive Design** – Works on desktop, tablet, and mobile.
- **Navigation Bar** – Consistent across all pages.
- **Projects Section** – Highlights real projects and future works-in-progress.
- **Contact Form** – Simple way to reach out (tested with Code Institute’s formdump).
- **Accessibility Considerations** – Semantic HTML, descriptive alt text for images.

---

## 🚀 Future Enhancements

- Add **form validation with JavaScript**.
- Include **live project demos** and GitHub repo links.
- Improve **animations and interactivity** with CSS/JS.
- Add **unit tests** for form validation and navigation.

---

## 🛠️ Technologies Used

- **HTML5** – Page structure
- **CSS3** – Styling and layout
- **Git & GitHub** – Version control and hosting
- **GitHub Pages** – Deployment

---

## 🧪 Testing

### 🔹 Manual Testing

#### Navigation

- **Expected:** Clicking links in the navbar should load the correct page.
- **Testing:** Clicked **Home**, **Projects**, **Tech Stack**, and **Contact** across Chrome, Edge, and Safari.
- **Result:** All links opened the correct page without errors.
- **Fix:** None needed.

#### Contact Form

- **Expected:** Form should not submit if fields are empty.
- **Testing:** Tried submitting with missing fields.
- **Result:** Validation error appeared; form did not submit.
- **Fix:** None needed.

#### Projects Images

- **Expected:** All project images should load correctly.
- **Testing:** Opened `projects.html` and `portfolio.html`.
- **Result:** One image (`Project Three`) was initially broken due to a missing asset.
- **Fix:** Updated to placeholder image – ✅ working now.

---

### 🔹 Responsiveness Testing

Tested using **Responsive Design Checker** and browser dev tools:

- **Desktop (1920px):** Layout centered, footer aligned at bottom. ✅
- **Tablet (768px):** Grid layouts stack neatly, nav adjusts. ✅
- **Mobile (375px):** Navigation collapses into stacked links, sections readable. ✅

---

### 🔹 Validation Testing

- **HTML:** Passed with [W3C Validator](https://validator.w3.org/). ✅
- **CSS:** Passed with [Jigsaw Validator](https://jigsaw.w3.org/css-validator/). ✅

Screenshots of both validator results are included in `assets/screenshots/`.

---

### 🔹 User Stories Testing

1. **Background Info** – "About Me" clearly displayed on Home. ✅
2. **Projects** – Shown in both `projects.html` and `portfolio.html`. ✅
3. **Experience** – Listed under “Professional Experience”. ✅
4. **Tech Stack** – Presented with logos and explanations. ✅
5. **Contact** – Email, LinkedIn, and form available. ✅

---

### 🔹 Bugs and Fixes

| Bug                                                 | Cause                         | Fix                                                     |
| --------------------------------------------------- | ----------------------------- | ------------------------------------------------------- |
| Footer floated halfway up the page on short content | No min-height on main content | Applied CSS `min-height: calc(100vh - header - footer)` |
| Broken project image                                | Wrong path                    | Replaced with working placeholder                       |
| README incomplete                                   | Missing key sections          | Expanded with features, testing, deployment             |

---

## 🌍 Deployment

This site is deployed via **GitHub Pages**:

🔗 [Live Demo](https://fila2021.github.io/filmawit-portfolio/)

**Steps to Deploy:**

1. Go to your GitHub repository.
2. Navigate to **Settings > Pages**.
3. Under **Source**, select the `main` branch and `/root`.
4. Click **Save**.
5. The live site link will appear at the top of the page.

---

## 🙏 Credits

- All HTML and CSS code written by me.
- Placeholder images from [via.placeholder.com](https://via.placeholder.com).
- Inspiration and assessment guidance from **Code Institute**.

---
