# Hans Soni - Personal Portfolio
A high-performance, interactive personal portfolio website showcasing my software engineering projects, skills, and experience. This project uses a uniquely built, lightweight reactive frontend runtime (support.js) that seamlessly parses and renders custom HTML templates (<x-dc>) into efficient React components.

## 🌐 Live Preview
You can view the live portfolio deployed on either of the following platforms:

[GitHub](https://hans-soni.github.io/Hans-Soni/)

[Netlify](https://hanssoni.netlify.app/)

## 📂 Complete Repository Structure
This repository is structured into a few key files and folders, each serving a distinct role in keeping the portfolio interactive, performant, and stylish:

## 1. Root Files

### index.html
Description: The main entry point and single-page template of the portfolio.
Contents: It contains the complete structure of the website, including sections for Hero, About, Skills, Projects, Certifications, Education, and Contact. It utilizes a custom declarative tag syntax (e.g., <x-dc>, <helmet>, <sc-if>) and embedded JavaScript component logic (DCLogic) to manage states like theming (Light/Dark mode) and mobile navigation.

### support.js
Description: The powerhouse custom runtime engine of the application.
Contents: A bespoke JavaScript runtime that acts as the bridge between the custom declarative HTML in index.html and React/ReactDOM. It manages template compilation, data binding (resolving {{ ... }} expressions), DOM updates, scroll observers, event handling, and rendering the custom cursor.

## 2. assets/ Folder
Contains all the static media and documents served on the website.

### Hans_Soni_Resume.pdf: 
The downloadable version of my latest resume linked in the Hero section.

### hans-soni.png: 
The primary profile picture displayed inside the interactive 3D-tilt hero card.

## 3. ds/ (Design System) Folder
Contains the styling, theming, and foundational design configurations.

### styles.css: The core stylesheet. 
It implements the "Glassmorphism" UI, responsive breakpoints, layout grids, and global utilities used across the portfolio.

### _ds_bundle.js: 
A minified JavaScript bundle associated with the design system components.

### _ds_manifest.json: 
The metadata and configuration manifest for the design system tokens and definitions.

### _adherence.oxlintrc.json: 
The linter configuration to maintain strict code quality and formatting rules within the design system.

### README.md: 
Specific documentation and guidelines detailing the usage of the design system components.

## 🚀 Core Features

### Custom Reactive Runtime: 
No bulky frameworks were used for the UI—instead, support.js compiles <sc-if> and <sc-for> logic directly from HTML to highly optimized React elements.

### Dynamic UI & Animations: 
Includes smooth 3D tilt interactions on images, floating shape parallax effects, a custom interactive mouse cursor, and CSS keyframe micro-animations.

### Built-in Theming System: 
Robust support for Light and Dark modes managed by responsive CSS variables.

### Security-Focused Content: 
Highlights a security-first engineering approach, reflecting my background in end-to-end encryption, secure coding, and robust architecture.

## 👨‍💻 About Me
I am a Computer Science undergraduate engineering secure, full-stack software. My work spans from end-to-end encrypted messaging to RESTful API design and defensive input handling. I am passionate about building systems where encryption and secure coding are at the core of the architecture.

## LinkedIn: 
[Hans-Soni](https://www.linkedin.com/in/hans-soni-59b294352)
## LeetCode: 
[Hans-Soni](https://leetcode.com/u/hanssoni/)
## Email: 
[Hans-Soni](mailto:hanssureshsoni@gmail.com)
