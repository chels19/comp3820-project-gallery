# COMP3820 Project Gallery

A project gallery for COMP3820 showcasing student projects built with SMART-on-FHIR framework. The gallery includes project details, descriptions, and links to live applications.

## Features
- Filter projects by year, category, or audience (`Designed For`).
- View detailed project pages with video, descriptions, and screenshots.
- Dynamic project data management using Markdown files in `_projects`.
- Responsive layout with Bootstrap-inspired design.

## Technologies Used
- **Jekyll**: Static site generator for creating the gallery.
- **HTML/CSS**: Custom layout and styles for the gallery and project pages.
- **JavaScript**: Client-side filtering functionality.
- **GitHub Pages**: Hosting the project online.

## Project Structure
├── _projects          # Markdown files for individual projects
├── assets             # Static assets (images, videos, etc.)
├── _layouts           # Customised HTML layout templates
└── index.html         # Home page
## Getting Started
To run the project locally:
1. Install Ruby and Jekyll:
   ```bash
   gem install jekyll bundler
2.	Clone the repository:
git clone https://github.com/jacznguo/comp3820-project-gallery.git
3.	Navigate to the project directory and serve the site:
cd comp3820-project-gallery
bundle exec jekyll serve
4.	Open your browser and navigate to:
http://127.0.0.1:4000