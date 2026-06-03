# 🍽️ Odin Recipes

A basic multi-page recipe website built with pure HTML as part of **[The Odin Project](https://www.theodinproject.com/)** Foundations curriculum.

---

## 📖 Table of Contents

- [About the Project](#about-the-project)
- [Recipes Included](#recipes-included)
- [Project Structure](#project-structure)
- [Skills Demonstrated](#skills-demonstrated)
- [What I Learned](#what-i-learned)
- [How to View](#how-to-view)
- [Credits & References](#credits--references)

---

## 📝 About the Project

This project was assigned as part of **The Odin Project – Foundations: Recipes lesson**. The goal was to build a simple multi-page recipe website using only HTML — no CSS or JavaScript — to practice the fundamentals of HTML structure, linking between pages, and organizing files in a project directory.

The site features a main homepage (`index.html`) that links to three individual recipe pages, each containing a dish image, description, ingredients list, and step-by-step cooking instructions.

> ⚠️ **Note:** The site intentionally has no styling. CSS will be added in a future iteration of this project as part of the curriculum.

---

## 🥘 Recipes Included

| Recipe | Source |
|--------|--------|
| Natasha's Kitchen Moist Banana Bread | [natashaskitchen.com](https://natashaskitchen.com/banana-bread-recipe-video/) |
| Copycat Levain Chocolate Chip Cookie | [joshuaweissman.com](https://www.joshuaweissman.com/recipes/best-levain-chocolate-chip-cookie-recipe) |
| Tini's Famous Mac and Cheese | [12tomatoes.com](https://12tomatoes.com/tinis-mac-cheese/) |

---

## 📁 Project Structure

```
odin-recipes/
├── index.html          # Main homepage with links to all recipes                   
├── images/             # Dish images used across recipe pages
└── recipes/
    ├── banana-bread.html
    ├── levain-choco-chip-cookie.html
    └── tinis-mac-and-cheese.html
```

Each recipe page follows the same structure:
- Link back to the homepage
- Recipe title
- Dish image
- Description
- Ingredients (unordered list)
- Steps (ordered list)

---

## 🛠️ Skills Demonstrated

- Semantic HTML structure (headings, paragraphs, lists, links, images)
- Linking between pages using relative file paths
- Organizing a multi-page project with a logical folder structure
- Setting up and using a Git repository
- Committing and pushing code to GitHub

---

## 🧠 What I Learned

- How to build a basic multi-page website from scratch
- How to navigate between HTML pages using relative paths
- The importance of proper file and folder organization in a web project
- How to write meaningful, incremental Git commits
- Writing accessible and well-structured HTML content

---

## 👀 How to View

### Option 1 – View locally
1. Clone this repository:
   ```bash
   git clone https://github.com/arkintamayo/odin-recipes.git
   ```
2. Open `index.html` in your web browser.

### Option 2 – View on GitHub Pages
*(If GitHub Pages is enabled)*
Visit: `https://arkintamayo.github.io/odin-recipes`

---

## 🔗 Credits & References

- **Project assigned by:** [The Odin Project – Recipes Lesson](https://www.theodinproject.com/lessons/foundations-recipes)
- **Banana Bread Recipe:** [Natasha's Kitchen](https://natashaskitchen.com/banana-bread-recipe-video/)
- **Mac and Cheese Recipe:** [12 Tomatoes](https://12tomatoes.com/tinis-mac-cheese/)
- **Chocolate Chip Cookie Recipe:** [Joshua Weissman](https://www.joshuaweissman.com/recipes/best-levain-chocolate-chip-cookie-recipe)
- **README formatting reference:** [GeeksforGeeks – What is README.md?](https://www.geeksforgeeks.org/git/what-is-readme-md-file/)

> All recipe content, images, and links are used strictly for **educational purposes** as part of a coding curriculum project.
