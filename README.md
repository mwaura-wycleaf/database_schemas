# Cookbookly 🍳

Cookbookly is a recipe website that allows users to organize and browse recipes. This repository contains the **database schema** for the project.

---

## 🗂️ Database Schema

The database is designed to store the core entities needed for the website. The main tables are:

- **users** – Stores user information like username, email, and password.
- **categories** – Stores recipe categories such as Desserts, Main Course, and Appetizers.
- **recipes** – Stores all recipes submitted by users, including title, description, instructions, prep time, and cook time.
- **ingredients** – Stores ingredients for each recipe with name and quantity.
- **recipe_images** – Stores images associated with recipes, including optional captions.

**Relationships:**

- Each user can submit multiple recipes.
- Each recipe belongs to one category.
- Each recipe can have multiple ingredients.
- Each recipe can have multiple images.

---

## 🛠️ Technologies

- **SQL / MariaDB** – For creating and managing database tables.
- **PHP** – For connecting and querying the database (in the main project).
- **HTML, CSS, JavaScript** – For building the front-end interface of the website.

---

## 📁 File Structure
