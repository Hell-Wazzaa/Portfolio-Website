# Portfolio Website

This is a responsive portfolio website built using **HTML** and **CSS**. The project showcases personal projects, skills, and a contact section while maintaining a visually appealing and user-friendly design.

## Technologies Used
- **HTML**: For structuring the webpage
- **CSS**: For styling and responsiveness

## Features
- Responsive navbar
- Animated gradient background
- Flexbox and Grid-based layout
- Hover and transition effects
- Responsive design for tablets and smartphones

## File Structure
```
portfolio-website/
│── index.html
│── styles.css
│── images/
│── README.md
```

## HTML Structure (index.html)
The main sections include:
- **Header & Navigation**: Contains a centered navbar with menu links.
- **Top Container**: Displays the main title and background effects.
- **Content Wrapper**: Includes an image and introductory text.
- **Projects Section**: Showcases projects using card components.
- **Contact Section**: Provides a form or contact details.
- **Footer**: Contains additional links and copyright information.

## CSS Classes Used
### General Styles
- `body` - Sets global styling for font, margin, and height.
- `h1, h2, p` - Styling for text elements.

### Layout & Containers
- `.top-container` - Defines the main header section with padding.
- `.content-wrapper` - Flexbox layout to align image and text.
- `.second-container` - Used for additional content sections.
- `.grid` - Grid layout for content arrangement.
- `.project-card` - Wrapper for project cards.

### Navbar
- `.navbar` - Styles the fixed navbar.
- `.navbar nav ul` - Styles the navigation list.
- `.navbar nav ul li` - Styles individual list items.
- `.navbar nav ul li a` - Styles navbar links.

### Cards & Buttons
- `.card` - Styles individual project cards.
- `.card-img` - Styles images inside cards.
- `.card-body` - Defines card content styling.
- `.card-title` - Styles the project title inside cards.
- `.btn` - Defines buttons used throughout the site.

### Footer
- `.footer-container` - Styles the footer section.
- `.footer-link` - Styles links in the footer.

### Responsive Design
- `@media (max-width: 1024px)` - Styles for tablets.
- `@media (max-width: 768px)` - Styles for smartphones.

## How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/portfolio-website.git
   ```
2. Open `index.html` in a browser.
3. Modify `styles.css` to customize the design.
