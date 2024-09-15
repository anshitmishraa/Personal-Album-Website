# Personal Album Website

## Overview
This is a personal album website showcasing a variety of images across multiple categories, such as **birthday**, **reception**, **engagement**, and more. The project leverages basic **HTML** and **CSS** to display the images in a visually appealing grid layout, using modern CSS techniques like **Flexbox** to structure the gallery. The project was a collaborative effort with my colleagues **Aryant** and **Amandeep**.

## Features
- **Image Gallery**: The website features multiple image categories, including:
  - Birthday
  - Reception
  - Engagement
  - Miscellaneous Events
- **Grid Layout**: Images are displayed in a responsive grid structure using CSS **Flexbox**, ensuring a consistent layout across various screen sizes.
- **Responsive Design**: The gallery adapts to different screen resolutions, ensuring the images are neatly organized on both mobile devices and desktops.
- **Collaborative Project**: This project was developed in collaboration with my colleagues, Aryant and Amandeep, as part of a personal initiative to improve our front-end development skills.

## Technology Stack
- **HTML**: The basic structure of the website is built using semantic HTML elements for better accessibility and SEO.
- **CSS**: Custom styling has been applied to create the grid layout and add visual effects. Key CSS features include:
  - **Flexbox**: Used to align and distribute images within the grid, making the layout flexible and responsive.
  - **Grid-like Layout**: The images are neatly arranged into rows and columns, providing a clean and organized gallery.
  - **Media Queries**: CSS media queries ensure that the layout adjusts dynamically to different device widths (mobile-first approach).

## Usage
### Viewing the Website
To view the album website locally, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/anshitmishraa/personal-album.git
   ```
2. Navigate to the project directory:
   ```bash
   cd personal-album
   ```
3. Open the `index.html` file in your browser:
   ```bash
   open index.html
   ```

Alternatively, if the website is hosted via GitHub Pages, you can visit the live version [here](https://anshitmishraa.github.io/personal-album/).

### Folder Structure
```bash
/project-root
├── /static
│   ├── /css
│   │   └── styles.css   # Custom CSS styles
│   ├── /images          # All image assets used in the gallery
│   │   └── birthday/
│   │   └── engagement/
│   │   └── reception/
├── index.html           # Main HTML file
├── README.md            # Project documentation (this file)
```

### Contributions
This project was a joint effort between:
- **[Anshit Mishra]**
- **[Aryant Nigam]**
- **[Amandeep]**

Each of us contributed equally to the design, development, and styling of the website. We primarily focused on:
- **HTML structure**: Creating the skeleton of the website.
- **CSS styling**: Building the grid layout using Flexbox and media queries for responsiveness.
- **Collaboration**: Shared responsibilities for code review, testing, and debugging.

## Future Improvements
Here are some features we plan to add in the future:
1. **JavaScript Enhancements**: Add interactive elements like image modals (lightbox effect) and filtering options for the image categories.
2. **Image Lazy Loading**: Implement lazy loading to improve page performance, especially for large image galleries.
3. **Search Functionality**: Allow users to search for specific events or image categories within the album.
4. **Accessibility Improvements**: Ensure the website is accessible to all users by adding ARIA labels, improving keyboard navigation, and enhancing screen reader compatibility.
