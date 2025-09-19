# 0x00-Semantic HTML Project

## Overview

This project is designed to help you learn and apply **semantic HTML** principles to create accessible, well-structured web pages. The project progresses from basic HTML structure to fully accessible forms using **ARIA roles**.

---

## Project Structure

```text
0x00-semantic_html/
├── 0-index.html       # Basic structured HTML document using semantic elements
├── 1-index.html       # Enhanced HTML with meta tags and title for SEO & accessibility
├── 2-index.html       # Blog post layout using semantic HTML elements
└── 3-index.html       # Contact form with ARIA roles and attributes for accessibility
```

## Learning Objectives

0-index.html
 - Create a structured HTML document using semantic elements: `<header>`, `<main>`, `<article>`, `<section>`, `<footer>`.
 - Include a navigation menu with at least three links.
 - Add an article with a title and content section.
 - Implement a footer with copyright information.

1-index.html
 - Enhance HTML document with meta tags for SEO and accessibility:
   - charset="UTF-8"
   - description, keywords, author, viewport
 - Set the document <title> for better SEO and clarity.

2-index.html
 - Apply semantic HTML elements to structure a blog post:
  - <h1> for main title, <h2> for article heading
  - Multiple <section> tags for Introduction, Main Content, and Conclusion
  - Use <figure> and <figcaption> for images
  - Include footer with author and published date
 - Ensure proper closing of all tags for valid HTML.

3-index.html
 - Implement ARIA roles and attributes to improve form accessibility:
  - Add a contact form with role="form" and aria-labelledby
  - Include input fields for Name and Email with aria-required="true"
  - Submit button with aria-label
  - Live region <div aria-live="polite" role="alert"> for dynamic updates

## Key Takeaways
 - Semantic HTML improves accessibility, SEO, and code readability.
 - Proper meta tags help search engines and assistive technologies understand your content.
 - ARIA roles and attributes make forms and interactive elements more accessible for screen readers.
 - Structuring your HTML using semantic elements ensures maintainable and scalable code.

## Author
 Dereje Masresha