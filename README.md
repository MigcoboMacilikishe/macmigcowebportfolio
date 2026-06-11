# Migcobo Macilikishe — Personal Portfolio Website

A personal portfolio website built from scratch using plain HTML and CSS.



## Purpose

To create an online presence that showcases who I am, my skills, my projects, and my interests — all in one place.



## Features

- Fixed pill-shaped navigation bar that stays at the top while scrolling
- Responsive design that adapts to mobile and desktop screens
- Fade-in animations on page load
- Hover effects on buttons, cards, and links
- Project cards with images and links
- Skills table with visual progress bars
- Contact form
- Social media links in the footer



## HTML Concepts Used

- Semantic structure with `<nav>`, `<body>`, `<footer>`
- Linking between multiple pages using `<a href="">`
- Lists with `<ul>` and `<li>`
- Forms with `<input>` and `<textarea>`
- Tables with `<table>`, `<tr>`, `<td>`, `<th>`
- Embedding external fonts and icon libraries via `<link>`
- Using `<span>` for responsive text swapping



## CSS Concepts Used

- Flexbox for layout and alignment
- CSS custom animations with `@keyframes`
- Media queries for responsive design
- CSS transitions for hover effects
- `position: fixed` for the sticky navbar
- `border-radius` for pill and card shapes
- `box-shadow` for glowing effects
- Importing Google Fonts with `@import`



## How to View the Project

1. Clone or download the repository
2. Open `index.html` in any browser
3. No installation or setup required

Or visit the live site: [migcobomacilikishe.github.io/my-portfolio-website](https://migcobomacilikishe.github.io/my-portfolio-website)


## Folder Structure

my-portfolio-website/
├── index.html
├── style.css
└── pages/
    ├── about.html
    ├── projects.html
    ├── skills.html
    ├── contact.html
    └── interests.html
```



## Challenges Faced

- Getting the navigation bar to stay horizontal on mobile without collapsing into a column
- Making the nav links fit on small screens without overflowing
- Managing multiple CSS media queries without them conflicting with each other
- Understanding how `position: fixed` interacts with the rest of the page layout



## What I Learned

- How to structure a multi-page website with linked HTML files
- How to use Flexbox to build clean, aligned layouts
- How media queries work and how to write mobile-first responsive CSS
- How small bugs like a missing closing bracket can break an entire stylesheet
- How to use GitHub and GitHub Pages to deploy a live website



## Future Improvements

- Add a working contact form with email functionality
- Add a dark/light mode toggle
- Animate the project cards on scroll
- Add a back-to-top button
- Make the navbar a shared component so changes only need to be made in one place



## Project Reflection

What website did you build?
I built a personal portfolio website with multiple pages including an About page, Projects page, Skills page, Contact page, and Interests page.

Why did you choose this design or theme?
I chose a dark theme with neon green accents because it gives the site a modern, tech-focused feel that reflects my personality and interest in development.

What does your website say about you?
It shows that I pay attention to detail, I care about presentation, and I am someone who takes their craft seriously even as a beginner.

What HTML concepts did you use?
I used semantic tags, multi-page linking, forms, tables, lists, and external resource linking for fonts and icons.

What CSS concepts did you use?
I used Flexbox, media queries, animations, transitions, fixed positioning, and box shadows.

What challenge did you face?
The biggest challenge was getting the navigation bar to stay in one row on mobile screens instead of stacking vertically. I also had a bug where a missing closing bracket in my CSS broke all my media queries.

How did you overcome the challenge?
I went through the CSS line by line to find the unclosed bracket. For the navbar, I removed the `flex-direction: column` rule from the media query and instead reduced padding and font size to keep everything in one row.

What are you proud of?
I am proud of how the overall design looks and that I built it entirely from scratch without any frameworks or templates.

What would you improve next?
I would make the navbar a reusable component so I don't have to update it manually on every page, and I would add scroll animations to make the site feel more dynamic.

How has this project helped you grow as a beginner developer?
It taught me that small details matter a lot in code — one missing bracket can break everything. It also gave me confidence that I can build something real and deploy it live for anyone to see.



## Author

Migcobo Macilikishe
- GitHub: [MigcoboMacilikishe](https://github.com/MigcoboMacilikishe)
- LinkedIn: [Migcobo Macilikishe](https://www.linkedin.com/in/migcobo-macilikishe-1354111b5/)
- Email: migcob73@gmail.com