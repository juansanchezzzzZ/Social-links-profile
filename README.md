# Frontend Mentor - Social Links Profile Solution

<div align="center">

![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![NEWBIE](https://img.shields.io/badge/Frontend_Mentor-NEWBIE-3DB8FF?style=for-the-badge)

</div>

A clean and responsive social links profile built as part of a Frontend Mentor challenge.  
This project focuses on semantic HTML structure, responsive layouts, accessibility basics, smooth hover animations, and modern CSS techniques without using JavaScript frameworks.

---

## Preview

![Design preview for the Social links profile coding challenge](./preview.jpg)

---

## Live Demo

- Live Site: https://juansanchezzzzz.github.io/social-links-profile/
- Frontend Mentor Challenge: https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ

---

# Overview

This project recreates a modern social profile card with attention to spacing, typography hierarchy, hover interactions, and responsive behavior across different screen sizes.

The main goal was to practice:

- Semantic HTML5
- Clean CSS architecture
- Responsive layouts
- Typography hierarchy
- Accessibility basics
- Smooth hover transitions
- Mobile-first workflow

---

# Built With

- HTML5
- CSS3
- Flexbox
- CSS Custom Properties
- Clamp()
- Mobile-First Workflow

---

# Hover Interaction Design

One of the main details implemented in this project was creating smooth and modern hover transitions for the social buttons.

Instead of abrupt color changes, transitions were added for background color, text color, movement, and shadows to create a cleaner user experience.

```css
.social{
    transition: 
        background-color 0.25s ease,
        color 0.25s ease,
        transform 0.25s ease,
        box-shadow 0.25s ease;
}

.social:hover{
    background: var(--Green);
    color: var(--Grey800);

    transform: translateY(-2px);

    box-shadow: 0 6px 14px rgba(0,0,0,0.18);
}