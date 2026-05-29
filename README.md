# GitHub Pages Resume Website Report

## Introduction

This assignment required creating a personal website using GitHub Pages and adding a dedicated resume page. The website serves as an online portfolio that can be continuously updated with projects, academic activities, achievements, and experiences throughout the years.

The main objectives of this assignment were:

* Create a GitHub repository
* Build a GitHub Pages website
* Add a resume page
* Publish the website online
* Document the entire process in Markdown format

---

# Step 1: Creating a GitHub Repository

First, I logged into my GitHub account and created a new repository.

## Repository Setup

* Repository Name: `my-portfolio-site`
* Visibility: Public
* Initialized with a `README.md` file

After creating the repository, GitHub generated the repository URL.

Example:

```bash
https://github.com/your-username/my-portfolio-site
```

---

# Step 2: Cloning the Repository

Next, I cloned the repository to my local computer using Git.

```bash
git clone https://github.com/your-username/my-portfolio-site.git
```

Then I moved into the project directory:

```bash
cd my-portfolio-site
```

---

# Step 3: Creating Website Files

I created the basic structure for the website.

## Files Created

```text
my-portfolio-site/
│
├── index.html
├── resume.html
├── style.css
└── README.md
```

---

# Step 4: Designing the Homepage

The `index.html` file acts as the homepage of the website.

## Features Included

* Personal introduction
* Navigation bar
* Links to resume page
* Simple responsive layout

Example structure:

```html
<h1>Welcome to My Portfolio</h1>
<p>This website contains my resume and projects.</p>
<a href="resume.html">View Resume</a>
```

---

# Step 5: Creating the Resume Page

A separate page called `resume.html` was created to display my resume.

## Information Included

* Personal Information
* Education
* Skills
* Projects
* Activities
* Achievements
* Contact Information

Example:

```html
<h2>Education</h2>
<p>Ho Chi Minh City University of Science</p>

<h2>Skills</h2>
<ul>
  <li>C++</li>
  <li>Java</li>
  <li>HTML/CSS</li>
</ul>
```

---

# Step 6: Adding CSS Styling

To improve the appearance of the website, I created a CSS file named `style.css`.

## Styling Features

* Clean layout
* Readable typography
* Navigation styling
* Responsive spacing
* Consistent colors

Example:

```css
body {
    font-family: Arial, sans-serif;
    margin: 40px;
}

h1 {
    color: #2c3e50;
}
```

---

# Step 7: Uploading Files to GitHub

After completing the website files, I uploaded them to GitHub using Git commands.

## Git Commands Used

```bash
git add .
git commit -m "Create GitHub Pages resume website"
git push origin main
```

---

# Step 8: Enabling GitHub Pages

To publish the website online, I enabled GitHub Pages.

## Steps

1. Open the repository on GitHub
2. Go to **Settings**
3. Select **Pages**
4. Under **Source**, choose:

   * Branch: `main`
   * Folder: `/root`
5. Click **Save**

After a few minutes, GitHub generated a public website URL.

Example:

```text
https://your-username.github.io/my-portfolio-site/
```

---

# Step 9: Testing the Website

I tested the website by opening the GitHub Pages URL in a browser.

## Testing Checklist

* Homepage loads correctly
* Resume page is accessible
* Navigation links work
* CSS styling appears properly
* Website works on different screen sizes

All pages functioned successfully.
