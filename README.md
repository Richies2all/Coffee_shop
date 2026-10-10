# Training project: Coffee Shop Landing Page ☕

## Overview

This project is a responsive coffee shop landing page developed as part of the workshop assignment for the Nucamp coding bootcamp.

The goal of this project is to design and build an attractive, user-friendly website for a coffee shop using HTML5, CSS3, and Bootstrap 5. The website showcases the coffee shop's brand, products, and atmosphere while providing visitors with an engaging browsing experience across desktop, tablet, and mobile devices.

The project focuses on applying front-end web development skills, creating responsive layouts, incorporating Bootstrap components, and organizing project files using industry-standard practices.

## Features

### Required Features

- **HTML5 Structure:** Semantic HTML elements for the header, main content, and footer.
- **Responsive Design:** Bootstrap 5 grid system and responsive utility classes for different screen sizes.
- **Custom Styling:** CSS styles for background colors, typography, spacing, borders, headers, footers, and modal components.
- **Bootstrap Components:** Responsive navigation, cards, and other components to enhance the user experience.
- **Image Gallery:** Coffee shop, beverages, or food images displayed using appropriate Bootstrap components.
- **Interactive Modal:** A Bootstrap modal featuring a coffee shop menu or a table reservation form.
- **Social Media Icon:** Social media icon links to help visitors connect with the coffee shop.

### Optional Features

Depending on the implementation, the project may also include:

- Deployment to Firebase Hosting.
- Additional images or background imagery.
- A working reservation, feedback, or review form.
- A location map and contact information.
- Detailed menu descriptions and pricing.
- Additional animations or interactive elements.

## Technologies Used

- **HTML5** — Page structure and semantic markup.
- **CSS3** — Custom styling, typography, colors, and layout refinements.
- **Bootstrap 5** — Responsive grid, navigation, cards, modals, and other UI components.
- **JavaScript** — Interactive Bootstrap components.
- **npm** — Package management.
- **Parcel** — Development server and production build tool, if using the npm setup.
- **Git** — Version control.
- **Firebase Hosting** — Optional website deployment.

## Project Structure

The project may be organized as follows:

```text
coffeeshop/
├── index.html
├── package.json
├── package-lock.json
├── .gitignore
├── README.md
├── css/
│   └── styles.css
├── img/
│   └── [coffee shop images]
├── node_modules/
└── dist/
```

**Note:** The `node_modules/` and `dist/` directories are generated or managed by the development tools and should generally be excluded from Git. The `dist/` directory is generated during the production build.

## Getting Started

### Prerequisites

To run or develop this project locally, you may need:

- A modern web browser.
- Visual Studio Code or another code editor.
- Node.js and npm, if using the Parcel build workflow.
- Git, for version control.

### Installation

1. Clone the repository:

   ```bash
   git clone <your-repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd coffeeshop
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

4. Start the development server using the script configured in `package.json`:

   ```bash
   npm start
   ```

5. Open the local development URL displayed in the terminal.

**Alternative:** If the project uses the Bootstrap CDN and does not require Parcel, open `index.html` directly in a browser or use a local development server.

## Running the Project

During development, the HTML, CSS, and JavaScript files can be updated and tested in the browser.

If using Parcel, run the configured development script to preview changes. Check the browser console and test the website at different viewport sizes to identify layout or functionality issues.

## Building for Production

If Parcel is configured, generate the production build by running:

```bash
npm run build
```

The optimized production files should be generated in the `dist/` directory.

## Deployment (Optional)

The website can optionally be deployed using Firebase Hosting.

1. Install the Firebase CLI and sign in to your Firebase account.
2. Initialize Firebase Hosting in the project directory:

   ```bash
   firebase init
   ```

3. Configure the public directory to match the production output directory, such as `dist`.
4. Build the project:

   ```bash
   npm run build
   ```

5. Deploy the website:

   ```bash
   firebase deploy
   ```

6. Open the hosting URL provided by Firebase and verify that the deployed website works correctly.

## Testing and Responsiveness

The website should be tested to verify that:

- The page displays correctly on desktop, tablet, and mobile devices.
- The navigation and layout adapt to different screen sizes.
- Images display correctly without distortion or broken links.
- Bootstrap modals open and close as expected.
- Interactive components function correctly.
- Text remains readable and appropriately spaced.
- Links and social media icons point to the intended destinations.
- The production build runs correctly, if applicable.

## Learning Outcomes

Through this project, I practiced:

- Building a complete landing page using semantic HTML5.
- Applying custom CSS styling and consistent visual design.
- Creating responsive layouts with Bootstrap 5.
- Implementing Bootstrap components such as cards, navigation, and modals.
- Organizing assets and source files in a structured project.
- Using npm, Parcel, and Git in a front-end development workflow.
- Building and deploying a website, if completing the optional deployment challenge.

## Future Improvements

Potential improvements include:

- Adding functional online reservations.
- Integrating a working contact or customer feedback form.
- Improving accessibility and keyboard navigation.
- Optimizing images and loading performance.
- Adding an interactive menu with detailed descriptions and prices.
- Integrating a map to display the coffee shop location.
- Expanding the site with additional pages.

## Acknowledgments

This project was completed as part of the Nucamp coding bootcamp workshop assignment.

Thanks to the Nucamp learning materials and documentation for guidance on HTML5, CSS3, Bootstrap 5, and front-end development workflows.

- Live Website: [Coffee Shop Landing Page](https://richienumcampsite.web.app/)

