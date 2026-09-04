# Personal Portfolio Website

## Student Information

**Student Name:** Lukumo Kibela
**Project Title:** Personal Portfolio Website
**Technology Used:** HTML5
**Version Control:** Git and GitHub

---

# Introduction

This project is a personal portfolio website created using **HTML5 only**. The purpose of the website is to demonstrate my understanding of HTML elements, attributes, semantic structure, hyperlinks, tables, forms, images, and proper organization of web content.

The website presents information about me, my education, skills, projects, services, gallery, and contact information.

The project was also managed using **Git and GitHub** to demonstrate the use of version control during web development.

---

# Question 1: Website Creation

## What type of website will you create and what content will it contain?

I created a **Personal Portfolio Website**.

A personal portfolio website is suitable for this project because it allows me to demonstrate many different HTML elements and attributes while presenting information about myself and my skills.

The website contains the following main sections:

### 1. Home

The Home section introduces me by displaying my name, professional interest, a short introduction, and navigation links to other sections of the website.

### 2. About Me

This section provides information about myself, my interests, goals, and personal background.

### 3. Education

The Education section contains a table showing my educational background and qualifications.

### 4. Skills

This section presents the technical and personal skills that I have developed.

### 5. Projects

The Projects section displays examples of projects I have worked on and provides descriptions of each project.

### 6. Services

This section describes services that I can provide based on my skills and experience.

### 7. Gallery

The Gallery section contains images related to my work and interests.

### 8. Contact

The Contact section provides ways for visitors to get in touch with me. It also contains a contact form.

### 9. Footer

The footer contains copyright information and a link that allows the visitor to return to the top of the page.

The website was created using HTML5 without external CSS or JavaScript because the assignment specifically focuses on demonstrating HTML elements and attributes.

---

# Question 2: HTML Elements

## 1. Five challenging HTML elements

The five HTML elements that I found most challenging were:

### `<table>`

I used the `<table>` element to organize my educational information into rows and columns. Creating the table required understanding elements such as `<tr>`, `<th>`, and `<td>`.

### `<form>`

The `<form>` element was challenging because it contains different form controls such as text inputs, email inputs, telephone inputs, text areas, labels, and buttons.

### `<figure>`

I used `<figure>` to organize images together with their captions. The `<figcaption>` element was used to describe each image.

### `<nav>`

The `<nav>` element was used to create the navigation section of the website. The navigation links connect to different sections using `href` attributes and section `id` attributes.

### `<fieldset>`

The `<fieldset>` element was used to group related contact form fields together. I also used `<legend>` to provide a title for the group of fields.

---

## 2. Semantic HTML structure

I used semantic HTML elements to give the website a meaningful structure.

The main semantic elements I used include:

* `<header>` – Contains the website introduction and navigation.
* `<nav>` – Contains navigation links.
* `<main>` – Contains the main content of the website.
* `<section>` – Separates the website into logical sections.
* `<article>` – Contains independent content such as information about me and projects.
* `<footer>` – Contains the bottom section of the website.

The general structure of my website is:

```text
<header>
    <nav>
        Navigation links
    </nav>
</header>

<main>
    <section>
        About Me
    </section>

    <section>
        Education
    </section>

    <section>
        Skills
    </section>

    <section>
        Projects
    </section>

    <section>
        Services
    </section>

    <section>
        Gallery
    </section>

    <section>
        Contact
    </section>
</main>

<footer>
    Footer information
</footer>
```

Using semantic HTML makes the website easier to understand, maintain, and access.

---

## 3. Most useful layout element

The `<table>` element was particularly useful for organizing information because the assignment required the website to be created using HTML only.

I also used HTML attributes such as `width`, `align`, `cellpadding`, and `cellspacing` to help organize and align some of the content.

However, in modern web development, CSS Flexbox and CSS Grid would normally be preferred for page layout. Tables should generally be used for tabular data rather than overall page layout.

---

# Question 3: HTML Attributes

## 1. Three essential HTML attributes

The three important attributes I used were `href`, `src`, and `id`.

### `href`

The `href` attribute specifies the destination of a hyperlink.

For example:

```html
<a href="#about">About Me</a>
```

This allows users to navigate to the About Me section.

### `src`

The `src` attribute specifies the location of an image.

For example:

```html
<img src="images/profile.jpg" alt="Profile photograph">
```

This tells the browser where to find the image.

### `id`

The `id` attribute uniquely identifies an HTML element.

For example:

```html
<section id="about">
```

The ID works together with the `href` attribute:

```html
<a href="#about">About Me</a>
```

This allows the navigation link to jump directly to the About Me section.

---

## 2. Difference between `class` and `id`

The `id` attribute is used to identify a **unique element** on a page.

For example:

```html
<section id="about">
```

The `class` attribute is used to group multiple elements that share the same characteristics.

For example:

```html
<article class="project">
```

Multiple project articles could use the same class:

```html
<article class="project">
    Project 1
</article>

<article class="project">
    Project 2
</article>
```

Therefore, an `id` is normally used for one unique element, while a `class` can be shared by multiple elements.

---

## 3. Best attribute for user experience

The `alt` attribute was one of the most important attributes for improving user experience.

For example:

```html
<img src="images/project1.jpg" alt="Personal portfolio project">
```

The `alt` attribute provides a description of an image.

It is useful because:

* It helps users understand an image if it fails to load.
* It supports screen readers.
* It improves accessibility.
* It provides additional information about images.

Overall, attributes such as `href`, `src`, and `id` provide functionality, while `alt` improves accessibility and user experience.

---

# Question 4: Development Process

## 1. How did you plan your website before coding?

Before writing the HTML code, I planned the type of website I wanted to create and the information it would contain.

I chose a Personal Portfolio Website because it provides opportunities to demonstrate a wide range of HTML elements and attributes.

I planned the following sections:

1. Home
2. About Me
3. Education
4. Skills
5. Projects
6. Services
7. Gallery
8. Contact
9. Footer

I then created the project folder and organized my files.

The project structure was:

```text
Personal-Portfolio-Website/
│
├── index.html
├── README.md
│
└── images/
    ├── profile.jpg
    ├── programming.jpg
    ├── project1.jpg
    └── project2.jpg
```

After planning the structure, I selected appropriate semantic HTML elements for each section.

---

## 2. How did you test and debug your website?

I tested the website by opening `index.html` in a web browser after making changes.

I checked:

* Headings
* Paragraphs
* Navigation links
* Tables
* Images
* Lists
* Project sections
* Services
* Contact form
* Footer

I tested every navigation link to ensure that it connected to the correct section.

For example:

```html
<a href="#about">About Me</a>
```

was checked against:

```html
<section id="about">
```

I also checked image paths to make sure that images were loading correctly.

When debugging, I looked for common HTML problems such as:

* Missing closing tags
* Incorrect nesting
* Incorrect image paths
* Incorrect IDs
* Incorrect `href` values
* Missing quotation marks
* Spelling errors
* Incorrect file names
* Unnecessary Markdown code fences

I also used browser developer tools when necessary to identify problems.

---

## 3. What challenges did you face?

One of the main challenges was creating a reasonably organized layout without using CSS.

Since the assignment required HTML only, I used HTML attributes such as `align`, `width`, `cellpadding`, and `cellspacing` where appropriate.

Another challenge was making sure that images were referenced correctly. I solved this by placing all images inside the `images` folder and using relative paths such as:

```html
src="images/profile.jpg"
```

I also had to ensure that the navigation links and section IDs matched correctly.

Another issue was accidentally including Markdown code fences inside the HTML file. I removed the ` ``` ` markers because they are not part of HTML and would appear as text in the browser.

The development process was therefore:

1. Choose the website type.
2. Plan the website sections.
3. Create the project folder.
4. Create `index.html`.
5. Create the `images` folder.
6. Add the HTML structure.
7. Add semantic HTML elements.
8. Add images and attributes.
9. Add navigation and contact form.
10. Open the website in a browser.
11. Test links and images.
12. Fix errors.
13. Review and finalize the website.

---

# Question 5: Git & GitHub Implementation

## 1. What Git commands did you use during development?

I used Git to track changes and manage different versions of my portfolio website.

The main Git commands I used were:

### `git init`

Used to initialize Git in my project folder.

```bash
git init
```

### `git status`

Used to check the current status of files in the repository.

```bash
git status
```

### `git add .`

Used to add project files to the staging area.

```bash
git add .
```

### `git commit`

Used to save a version of the project with a descriptive message.

```bash
git commit -m "Initial commit - create portfolio website"
```

### `git log`

Used to view previous commits and the development history.

```bash
git log
```

### `git branch`

Used to view or manage Git branches.

```bash
git branch
```

### `git remote add origin`

Used to connect the local repository to the GitHub repository.

```bash
git remote add origin YOUR_GITHUB_REPOSITORY_URL
```

### `git push`

Used to upload my local commits to GitHub.

```bash
git push -u origin main
```

### `git pull`

Used to retrieve the latest changes from the remote GitHub repository when necessary.

```bash
git pull origin main
```

These commands helped me manage and track the development of my website.

---

## 2. How many commits did you make and what was your commit message strategy?

I used multiple commits during the development of my website. My commit strategy was to create a commit whenever I completed an important stage of development.

Example commit messages include:

```text
Initial commit - create portfolio website structure
Add personal portfolio content
Add images and gallery section
Add contact form and navigation
Finalize HTML portfolio website
Add comprehensive project README
```

I used short and descriptive commit messages so that each commit clearly explained what had changed.

Instead of using vague messages such as:

```text
changes
update
new stuff
```

I used messages that described the actual development task.

This makes the Git history easier to understand and maintain.

> **Note:** The exact number of commits in this README should match the actual commit history shown in my GitHub repository.

---

## 3. Why is version control important for web development projects?

Version control is important because it allows developers to track changes to a project over time.

Git provides several important benefits:

* It tracks changes made to files.
* It allows developers to restore previous versions.
* It provides a backup of project files when using GitHub.
* It helps developers work together on the same project.
* It allows developers to create branches for new features.
* It records who made changes and when they were made.
* It makes project development easier to manage.
* GitHub allows projects to be shared with lecturers, employers, and other developers.

For my portfolio website, Git and GitHub helped me maintain a history of my development process and safely store my project online.

---

# Question 6: Code Quality & Best Practices

## 1. How did you ensure your HTML was valid and error-free?

I ensured that my HTML was valid and error-free by reviewing my code carefully and testing the website regularly in a web browser.

I checked that:

* Opening tags had appropriate closing tags.
* HTML elements were correctly nested.
* Attributes were correctly written.
* Image paths were correct.
* Navigation links matched their corresponding section IDs.
* Images contained descriptive `alt` attributes.
* Headings were organized logically.
* The page contained the correct HTML document structure.
* The contact form and other interactive elements were displayed correctly.

I also used browser developer tools to help identify errors when necessary.

I tested the website after making changes rather than waiting until the end of development. This made it easier to identify and fix problems.

---

## 2. What best practices did you follow for writing clean, readable code?

I followed several HTML coding best practices.

### Proper indentation

I used indentation to make nested HTML elements easier to read.

### Semantic HTML

I used semantic elements such as:

```html
<header>
<nav>
<main>
<section>
<article>
<footer>
```

These elements make the purpose of different parts of the website clear.

### Meaningful headings

I used headings such as `<h1>`, `<h2>`, and `<h3>` to organize content logically.

### Descriptive attributes

I used descriptive `alt` text for images and meaningful IDs for navigation.

### Organized files

I separated images from the main HTML file by storing them in an `images` folder.

### Consistent structure

I tried to maintain a consistent structure and indentation throughout the HTML document.

### Avoiding unnecessary code

Since the assignment required HTML only, I avoided adding unnecessary CSS or JavaScript and focused on demonstrating HTML elements and attributes.

### Testing regularly

I opened the website in a browser regularly to check whether the code was working as expected.

These practices made my code easier to read, understand, maintain, and troubleshoot.

---

## 3. How would you improve your website if you had more time?

If I had more time, I would improve my website in several ways.

### Add CSS styling

The first major improvement would be adding CSS to create a more professional design.

I would add:

* A professional color scheme
* Better typography
* Improved spacing
* Responsive layouts
* Styled navigation
* Project cards
* Better image presentation
* Improved contact form styling
* Hover effects

The current website intentionally uses HTML only because of the assignment requirements.

### Make the website responsive

I would make the website responsive so that it works properly on:

* Desktop computers
* Tablets
* Mobile phones

### Add JavaScript

If JavaScript were allowed, I would add interactive features such as:

* Form validation
* Mobile navigation
* Interactive image galleries
* Smooth scrolling
* Dynamic content

### Improve the contact form

I would connect the contact form to a backend system so that visitors could send actual messages.

### Add more projects

I would add more real projects and provide links to live websites and GitHub repositories.

### Improve accessibility

I would continue improving accessibility by using:

* Descriptive alternative text
* Proper heading structures
* Clear form labels
* Good color contrast
* Keyboard-friendly navigation

### Improve SEO

I would add additional search engine optimization features such as descriptive metadata, improved page descriptions, and structured content.

---

# Project Structure

The project is organized as follows:

text
Personal-Portfolio-Website/
│
├── index.html
├── README.md
│
└── images/
    ├── profile.jpg
    ├── programming.jpg
    ├── project1.jpg
    └── project2.jpg


### `index.html`

This is the main webpage containing the complete HTML structure and content.

### `README.md`

This document explains the project and provides answers to Questions 1–6.

### `images/`

This folder contains the images used throughout the website.

---

# Technologies Used

The following technologies and tools were used:

* **HTML5** – Used to create the structure and content of the website.
* **Git** – Used for version control and tracking changes.
* **GitHub** – Used to host the Git repository and share the project.

No external CSS or JavaScript was used because the assignment required the website to be created using HTML only.

---

# Conclusion

This project helped me develop a better understanding of HTML elements, attributes, semantic structure, navigation, forms, tables, images, and website organization.

I also gained practical experience using Git and GitHub to track changes and manage a web development project.

Through this project, I learned that writing clean and well-organized HTML is important for creating websites that are easier to maintain, understand, and improve.

If the project were developed further, I would add CSS for professional styling, JavaScript for interactivity, backend functionality for the contact form, and additional projects to make the portfolio more comprehensive.

---

# GitHub Repository

**Repository:** Personal-Portfolio-Website

**GitHub Repository Link:**
`[Paste your GitHub repository link here]`

---

# Submission Checklist

* [ ] GitHub repository created
* [ ] `index.html` pushed to GitHub
* [ ] `images` folder pushed to GitHub
* [ ] `README.md` added
* [ ] Questions 1–6 answered in README
* [ ] Instructor **Billy Peter Munyenyembe (`Billypeterlennards`)** added as collaborator
* [ ] Instructor followed on GitHub
* [ ] Repository link tested
* [ ] Repository link submitted through Google Classroom
