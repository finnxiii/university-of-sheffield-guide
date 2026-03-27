# University of Sheffield Guide

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-2E2E2E?logo=github&logoColor=white)](https://github.com/finnxiii/university-of-sheffield-guide)
[![Live Demo](https://img.shields.io/badge/Live-Demo-00C7B7?logo=netlify&logoColor=white)](https://uos-guide-finnxiii.netlify.app/)

A responsive campus guide website designed to help students explore food spots, picnic areas, and key locations around the University of Sheffield.

Developed as part of the COM1008 Web and Internet Technology module, this project focuses on building a fully functional website using **pure HTML and CSS**, without relying on frameworks.

<br>

> [!NOTE]
> This project intentionally avoids JavaScript frameworks to emphasise strong fundamentals in semantic HTML, responsive design, and accessibility.

<br>

## Overview

The website provides a structured and user-friendly guide to campus life, including:

- Food & drink locations around campus  
- Picnic spots and green spaces  
- An interactive quiz experience built with HTML and CSS  
- Supporting pages covering accessibility, design, legal considerations, and testing  

The project demonstrates how core front-end technologies can be used to build a complete, multi-page responsive website.

<br>

## System Structure

```mermaid
flowchart LR

A[User] --> B[Multi-Page Website]
B --> C[HTML Pages]
B --> D[CSS Stylesheets]
B --> E[Assets Images and Icons]
B --> F[External Services]

F --> G[Google Maps Embed]
F --> H[Google Fonts]

subgraph Frontend
C
D
E
end
```

**Flow Summary**
- Users navigate across multiple static HTML pages
- Layout and responsiveness are controlled through modular CSS files
- External services enhance presentation and usability through embedded maps and custom fonts

<br>

## Key Features

- Mobile-first responsive design
- Multi-page campus guide experience
-	Food and drink recommendations
-	Picnic and outdoor location guide
-	Interactive quiz built without JavaScript
-	Contact form UI for user feedback
-	Accessibility-focused semantic structure
-	Embedded maps for key locations
-	Consistent navigation and layout across pages  

<br>

## Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white)
![Responsive](https://img.shields.io/badge/Mobile--First-Responsive-6A5ACD?style=for-the-badge)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

<br>

## Design Considerations

- Mobile-first development: The layout was designed for smaller screens first, then progressively enhanced for tablet and desktop devices
- Separation of concerns: Styling is split into multiple CSS files for easier maintenance and clearer structure
- Performance optimisation: JPEG images were used where appropriate to reduce file size, and embedded maps use lazy loading
- Scalable structure: The project can be extended later with JavaScript or migrated into a framework such as React or Next.js

<br>

## Motivation

This project was built to strengthen my understanding of core front-end development principles through a real multi-page website.

Rather than relying on libraries or frameworks, the goal was to build a clean, accessible, and responsive experience using foundational web technologies only.
