# Single Page CV with Semantic HTML

A well-structured, single-page CV built with semantic HTML5 elements. This project demonstrates the use of HTML5's semantic tags to improve accessibility, readability, and SEO.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Semantic HTML Structure](#semantic-html-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project provides a single-page CV template designed with semantic HTML5. The template organizes the content into meaningful sections to make the CV accessible and readable by both people and search engines.
https://roadmap.sh/projects/single-page-cv 
The HTML5 structure follows best practices by using elements such as `<header>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>`. 

## Technologies Used
- **HTML5** - For structuring the content.
- **CSS** - For styling the CV template.
- **Git** - Version control for collaborative development.

## Semantic HTML Structure
The following semantic HTML elements are used in the CV:

- **`<header>`**: Contains the candidate's name, title, and contact information at the top of the page.
- **`<main>`**: Encloses the main content of the CV, including various sections like experience and education.
- **`<section>`**: Organizes different parts of the CV, such as **Experience**, **Education**, and **Skills**.
- **`<article>`**: Represents individual entries within sections, like specific job roles or educational qualifications.
- **`<aside>`**: Can be used for side information like language proficiency or personal interests.
- **`<footer>`**: Contains links to the candidate's social profiles or portfolio websites.

### Sample Code Structure
Below is an example of the file structure and key sections in the `index.html` file.

```html
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>CV - [Your Name]</title>
</head>
<body>
   <header>
       <h1>[Your Name]</h1>
       <p>Front-End Developer</p>
       <p>Email: [Your Email]</p>
   </header>

   <main>
       <section id="summary">
           <h2>Summary</h2>
           <p>A brief introduction to your professional background.</p>
       </section>

       <section id="experience">
           <h2>Experience</h2>
           <article>
               <h3>Job Title</h3>
               <p>Description of your role and achievements.</p>
           </article>
       </section>

       <section id="education">
           <h2>Education</h2>
           <article>
               <h3>Degree</h3>
               <p>Institution and graduation year.</p>
           </article>
       </section>

       <section id="skills">
           <h2>Skills</h2>
           <p>List of relevant skills.</p>
       </section>
   </main>

   <footer>
       <p>Connect with me on [LinkedIn](https://linkedin.com/in/yourprofile) | [GitHub](https://github.com/yourusername)</p>
   </footer>
</body>
</html>
