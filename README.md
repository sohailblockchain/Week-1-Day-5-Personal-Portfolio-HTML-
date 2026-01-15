📘 Week 1 – Day 5: Personal Portfolio (HTML)
📌 Lecture Topic

Project: Personal Portfolio Website (HTML Only)
Students will build a multi-page personal portfolio website using semantic HTML and accessible forms, which will later be styled using CSS.

This lecture is focused on project-based learning, practical coding, and mentoring.
Assignment 1 (A1) is released in this session.

🎯 Learning Objectives

By the end of this session, students will be able to:

Plan a multi-page website structure and navigation

Use semantic HTML tags:

header, nav, main, section, article, footer

Create an accessible contact form with validation

Organize content using headings and lists

Prepare HTML layout for future CSS styling

📄 Pages to Create

Students must create the following files:

index.html → Home / About page

projects.html → Projects showcase page

contact.html → Contact form page

Optional Page

resume.html → Skills and experience

📁 Recommended Folder Structure
portfolio/
│
├── index.html
├── projects.html
├── contact.html
├── resume.html   (optional)
│
└── assets/
    └── images/

✅ Key Requirements

Each portfolio must include:

✅ Same header and navigation on all pages

✅ One <h1> per page (main heading)

✅ Semantic layout using:

header, nav, main, section, article, footer

✅ Clear heading hierarchy (h1 → h2 → h3)

✅ Contact form with:

Labels connected using for and id

Required name and email fields

✅ Working navigation links between pages

🧩 Base Layout (Use on Every Page)
<header>
  <h1>Amna Khan</h1>
  <p>Frontend Developer | HTML | CSS | JavaScript</p>
  <nav>
    <a href="index.html">Home</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

🏠 Page 1: Home / About
Purpose

Introduce yourself and your skills.

Suggested Sections

About Me

Skills

Highlights

Example
<main>
  <section>
    <h2>About Me</h2>
    <p>I build clean, user-friendly websites and enjoy learning new tools.</p>
  </section>

  <section>
    <h2>Skills</h2>
    <ul>
      <li>HTML5</li>
      <li>CSS3</li>
      <li>Responsive Design</li>
    </ul>
  </section>
</main>

💼 Page 2: Projects
Purpose

Showcase 2–3 projects using semantic articles.

Example
<main>
  <section>
    <h2>Projects</h2>

    <article>
      <h3>Landing Page</h3>
      <p>A responsive landing page built with semantic HTML.</p>
      <a href="#">View project</a>
    </article>

    <article>
      <h3>Recipe Blog</h3>
      <p>A simple blog layout using sections and lists.</p>
      <a href="#">View project</a>
    </article>

  </section>
</main>

✉️ Page 3: Contact
Purpose

Collect messages from visitors using accessible forms.

Form Requirements

Labels must use for and id

Name and Email must be required

Message is optional

Example Form
<form>
  <label for="full-name">Full Name</label>
  <input id="full-name" name="full-name" type="text" required />

  <label for="email">Email</label>
  <input id="email" name="email" type="email" required />

  <label for="message">Message</label>
  <textarea id="message" name="message" rows="5"></textarea>

  <button type="submit">Send</button>
</form>

♿ Accessibility Checklist

Students must ensure:

✅ Only one <h1> per page

✅ Images have alt text

✅ All form inputs have labels

✅ Clear readable content structure

🧪 Practical Lab Tasks

Students must:

Build all pages using the structure above

Add real personal content

Test navigation between pages

Validate HTML using browser or online validator

Instructor will assist with:

Navigation linking issues

Semantic layout corrections

Form validation problems

📌 Assignment 1 (A1)
Submission Instructions

Students must submit:

Complete portfolio/ folder

All required HTML files

Assets folder if images are used

Evaluation Criteria

Correct HTML structure

Semantic tag usage

Navigation working

Accessibility rules followed

Clean readable layout

🏠 Homework (Optional Improvements)

Students may also add:

Resume page

Image gallery with alt text

Footer with contact/social links

🚀 What’s Next?

In the next class, students will begin CSS styling:

Colors

Layout

Fonts

Responsive design basics

This HTML portfolio will be fully styled using CSS in upcoming lectures.

👨‍🏫 Instructor

Sohail Ahmed
Senior Software Engineer & Full Stack Blockchain Engineer
Web Development Instructor
