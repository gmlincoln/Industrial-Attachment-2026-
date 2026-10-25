# 📚 HTML Practical Task 02: Student Profile Webpage

## 📌 Task Overview

Create a **Student Profile Webpage** using HTML only. The webpage should display a student's personal information, educational background, skills, hobbies, and contact information.

This task will help you practice essential HTML elements and organize webpage content using proper HTML structure.

## 🎯 Learning Objectives

After completing this task, you will be able to:

- Create a complete HTML5 document.
- Use headings, paragraphs, and text formatting.
- Add images and hyperlinks.
- Create ordered and unordered lists.
- Display information using an HTML table.
- Organize a webpage using semantic HTML elements.

## 📋 Task Requirements

Your webpage must contain the following sections.

### 1. Header Section

- Add your full name as the main heading.
- Add a short title, such as `CSE Student` or `Web Development Learner`.
- Add a horizontal line below the header.

### 2. About Me Section

Write a paragraph introducing yourself. Include:

- Your name
- Your educational background
- Your current learning goals
- Your future career goal

Use the `<p>` element for the paragraph.

### 3. Profile Picture

- Add your profile picture using the `<img>` element.
- Provide meaningful `alt` text.
- Use an image file stored in your project folder.

Example:

```html
<img src="profile.jpg" alt="Student profile picture" width="200">
```

### 4. Educational Background

Create an HTML table containing your educational information.

Your table must have these columns:

| Degree | Institution | Passing Year | Result |
|---|---|---|---|
| SSC | Your School | 2020 | GPA 5.00 |
| HSC | Your College | 2022 | GPA 5.00 |
| BSc | Your University | 2026 | CGPA 3.80 |

*The information above is an example. Replace it with your own details.*

Use the following HTML elements:

- `<table>`
- `<tr>`
- `<th>`
- `<td>`

### 5. Skills Section

Create an unordered list of at least five skills.

Example:

- HTML
- CSS
- JavaScript
- Python
- Git

Use the `<ul>` and `<li>` elements.

### 6. Hobbies Section

Create an ordered list of at least three hobbies.

Example:

1. Reading books
2. Playing sports
3. Travelling

Use the `<ol>` and `<li>` elements.

### 7. Useful Links Section

Add links to at least three websites or profiles, such as:

- GitHub
- LinkedIn
- Your favorite learning website

Example:

```html
<a href="https://github.com/">Visit GitHub</a>
```

Use appropriate URLs for your links.

### 8. Contact Information

Display the following information:

- Email address
- Phone number
- City or district

Also add an email link using the `mailto:` attribute.

Example:

```html
<a href="mailto:student@example.com">Send Me an Email</a>
```

### 9. Footer Section

At the bottom of the webpage, display a copyright notice.

Example:

```html
<footer>
    <p>Copyright © 2026 My Student Profile</p>
</footer>
```

## 🛠️ Project Setup

Create the following folder structure:

```text
student-profile/
│
├── index.html
└── profile.jpg
```

You may use another image filename, but make sure the image path in your HTML matches it.

## 💡 HTML Elements You Must Use

| Element | Purpose |
|---|---|
| `<h1>` to `<h3>` | Headings |
| `<p>` | Paragraphs |
| `<img>` | Images |
| `<a>` | Links |
| `<ul>` and `<ol>` | Lists |
| `<li>` | List items |
| `<table>`, `<tr>`, `<th>`, `<td>` | Table structure |
| `<hr>` | Horizontal line |
| `<footer>` | Footer section |

## ⭐ Bonus Challenges

Complete these additional tasks to improve your skills:

- Add a `target="_blank"` attribute to external links.
- Add a `<blockquote>` containing your favorite quote.
- Use `<strong>` and `<em>` to emphasize important text.
- Add a separate section describing your favorite project.
- Use `<header>`, `<main>`, and `<section>` to organize the webpage.
- Add a link that allows visitors to download your CV using the `download` attribute.

## 📤 Submission Guidelines

Submit the following:

1. Your `index.html` file.
2. Your profile image.
3. A screenshot of your completed webpage.

**Submission folder name:** `student-profile`

## ✅ Evaluation Criteria

| Criteria | Marks |
|---|---:|
| Correct HTML document structure | 10 |
| About Me and personal information | 15 |
| Profile image and alternative text | 10 |
| Educational table | 20 |
| Skills and hobbies lists | 15 |
| Useful links and contact information | 15 |
| Semantic structure and code readability | 15 |
| **Total** | **100** |

## ⚠️ Important Instructions

- Use **HTML only**. CSS and JavaScript are not required.
- Do not copy another student's work.
- Use your own information wherever possible.
- Indent your code properly and use meaningful section headings.
- Test your webpage in a browser before submission.

**Challenge:** Build a webpage that clearly presents your profile and could later become the foundation of your personal portfolio.

Happy coding! 🚀
