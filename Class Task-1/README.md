# HTML Practical Task – 01

## 📌 Task Title
**Create Your First Personal Profile Webpage**

---

## 🎯 Objective

Create a simple personal profile webpage using **HTML only**.

You must use the HTML tags and concepts learned in today's class.

---

## 📁 Project Name

Create a project folder named:

```text
my-profile
```

Inside the folder, create:

```text
my-profile/
│
├── index.html
├── my-photo.jpg
│
└── images/
    ├── hobby.jpg
    └── favorite-place.jpg
```

---

# 📝 Requirements

## 1. Basic HTML Structure

Create an `index.html` file using the standard HTML structure.

Your page must contain:

- `<!DOCTYPE html>`
- `<html>`
- `<head>`
- `<meta charset>`
- `<meta name="viewport">`
- `<title>`
- `<body>`

---

## 2. Page Title

Set the browser title to:

**My Personal Profile**

Example:

```html
<title>My Personal Profile</title>
```

If you have a favicon, add it to your webpage.

---

## 3. Heading Tags

Use **all six heading tags**:

```text
<h1>
<h2>
<h3>
<h4>
<h5>
<h6>
```

Use meaningful headings related to your profile.

For example:

- My Personal Profile
- About Me
- My Education
- My Skills
- My Hobbies
- My Goals

---

## 4. About Me

Write at least **3 paragraphs** about yourself.

Your paragraphs should include:

- Your name
- Where you live
- Your educational background
- Your future goal

Example:

```html
<p>
    My name is __________. I am from __________.
</p>
```

Do not copy the example exactly. Write your own information.

---

## 5. Hyperlinks

Add at least **3 hyperlinks**.

You must include:

1. Google
2. Your Institute/College website
3. Any learning website

At least **one link must open in a new tab**.

Example:

```html
<a href="https://www.google.com/" target="_blank">
    Google
</a>
```

---

## 6. Ordered List

Create an ordered list titled:

### My Daily Routine

Include at least **5 items**.

Example:

```text
1. Wake up
2. Freshen up
3. Have breakfast
4. Attend class
5. Study
6. Sleep
```

Use:

```html
<ol>
    <li>...</li>
</ol>
```

---

## 7. Unordered List

Create an unordered list titled:

### My Hobbies

Include at least **5 hobbies**.

Example:

```text
■ Reading
■ Traveling
■ Watching Movies
■ Playing Games
■ Sports
```

Use a different list style:

```html
<ul style="list-style-type: square;">
    <li>Reading</li>
    <li>Traveling</li>
    <li>Playing Games</li>
</ul>
```

---

## 8. Text Formatting

Write a paragraph about yourself or your course.

You must use all of the following tags:

```text
<b>
<strong>
<i>
<em>
<mark>
```

Example:

```html
<p>
    HTML is an important technology for
    <b>web development</b>.
</p>
```

Use the tags appropriately instead of simply adding them without meaning.

---

## 9. Superscript

Add the following mathematical equation:

```text
(a+b)² = a² + 2ab + b²
```

Use the `<sup>` tag.

Example:

```html
<p>
    (a+b)<sup>2</sup> = a<sup>2</sup> + 2ab + b<sup>2</sup>
</p>
```

---

## 10. Subscript

Add the following chemical formula:

```text
H₂O
```

Use the `<sub>` tag.

Example:

```html
<p>
    H<sub>2</sub>O
</p>
```

---

# 🖼️ 11. Images

Add **3 images** to your webpage.

### Image 1 – Parent Folder

Place an image in the same folder as `index.html`.

```html
<img src="./my-photo.jpg" alt="My Photo">
```

---

### Image 2 – Child Folder

Place an image inside the `images` folder.

```html
<img src="./images/hobby.jpg" alt="My Hobby">
```

---

### Image 3 – Online Image

Use an image from an online source.

```html
<img
    src="ONLINE_IMAGE_URL"
    alt="My Favorite Place">
```

Every image must contain a meaningful `alt` attribute.

---

# ⭐ 12. Challenge Task

Create a section called:

## My Favorite Things

Create an unordered list containing:

- Favorite Food
- Favorite Movie
- Favorite Sport
- Favorite Color
- Favorite Place

Then use the `<mark>` tag to highlight your favorite item.

Example:

```html
<li><mark>My Favorite Food</mark></li>
```

---

# 📋 13. Required HTML Tags

Your webpage must use at least the following tags:

```text
<!DOCTYPE html>
<html>
<head>
<meta>
<title>
<body>

<h1>
<h2>
<h3>
<h4>
<h5>
<h6>

<p>

<a>

<ol>
<ul>
<li>

<b>
<strong>
<i>
<em>
<mark>

<sup>
<sub>

<img>
```

---

# 🚫 Rules

1. ❌ Do not use CSS.
2. ❌ Do not use Bootstrap.
3. ❌ Do not use Tailwind CSS.
4. ❌ Do not copy another student's code.
5. ❌ Do not copy the teacher's exact content.
6. ✅ Write your own personal information.
7. ✅ Use proper indentation.
8. ✅ Every image must have an `alt` attribute.
9. ✅ Use meaningful headings.
10. ✅ Use at least **10 different HTML tags** from today's lesson.

---

# 📂 Final Folder Structure

Your final project should look like this:

```text
my-profile/
│
├── index.html
├── my-photo.jpg
│
└── images/
    ├── hobby.jpg
    └── favorite-place.jpg
```

---

# 🎯 Expected Webpage Structure

Your webpage should contain sections similar to:

```text
========================================

        MY PERSONAL PROFILE

========================================

About Me

My name is __________.
I am from __________.
I am currently studying __________.

----------------------------------------

My Education

...

----------------------------------------

My Skills

...

----------------------------------------

My Daily Routine

1. Wake up
2. Freshen up
3. Breakfast
4. Attend class
5. Study
6. Sleep

----------------------------------------

My Hobbies

■ Reading
■ Traveling
■ Sports
■ Watching Movies
■ Playing Games

----------------------------------------

My Favorite Things

■ Favorite Food
■ Favorite Movie
■ Favorite Sport
■ Favorite Color
■ Favorite Place

----------------------------------------

My Photo

[Image]

----------------------------------------

Useful Links

Google
My Institute
Learning Website

----------------------------------------

(a+b)² = a² + 2ab + b²

H₂O

========================================
```

---

# 📤 Submission

Submit the complete project folder:

```text
my-profile
```

Make sure that:

- `index.html` works correctly.
- All images are included.
- Image paths are correct.
- All links work.
- No broken images exist.
- Your HTML code is properly indented.

---

## 🏆 Bonus Challenge

Students who finish the main task can additionally add:

- A second page named `about.html`
- A link from `index.html` to `about.html`
- A link from `about.html` back to `index.html`

**Remember:** No CSS. Focus only on HTML structure and the tags learned in class.