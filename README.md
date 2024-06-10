# White Matrix Website Documentation

## Project Overview

The White Matrix website is designed to showcase the portfolio and services of our company White Matrix. It includes key features such as an interactive slider on the home page, detailed service pages, and a contact form.

## Project Structure

```plaintext
wm-portfolio/
├── public/
│   ├── assets/
│   │   ├── [images...]
│   ├── index.html
├── src/
│   ├── assets/
│   │   ├── [home page images...]
│   ├── components/
│   │   ├── slider/
│   │   │   ├── ai.jsx
│   │   │   ├── mobileapp.jsx
│   │   │   ├── software.jsx
│   │   │   ├── voip.jsx
│   │   ├── styled/
│   │   │   ├── banner.jsx
│   │   │   ├── header.jsx
│   │   ├── career.jsx
│   │   ├── banner.jsx
│   │   ├── drawer.jsx
│   │   ├── header.jsx
│   │   ├── home_screen.jsx
│   │   ├── scheduleconvo.jsx
│   │   ├── style.css
│   ├── App.js
│   ├── index.css
│   ├── index.js
├── package.json
└── ...
```
### Directory and File Description

- **public/**: Contains the static assets and the main HTML file.
  - **assets/**: All images used throughout the website.
  - **index.html**: The main HTML file for the application.
- **src/**: Contains the source code of the application.
  - **assets/**: Images used specifically for the home page.
  - **components/**: Contains all React components and pages.
    - **slider/**: React components for the pages accessed via the home page slider.
      - **ai.jsx**: AI page component.
      - **mobileapp.jsx**: Mobile App Development page component.
      - **software.jsx**: Software Development page component.
      - **voip.jsx**: VOIP page component.
    - **styled/**: Styled components for the banner and header.
      - **banner.jsx**: Styled component for the banner.
      - **header.jsx**: Styled component for the header.
    - **career.jsx**: Career page component.
    - **banner.jsx**: Banner component.
    - **drawer.jsx**: Drawer component.
    - **header.jsx**: Header component.
    - **home_screen.jsx**: Home screen component.
    - **scheduleconvo.jsx**: Schedule a conversation component.
    - **style.css**: Contains styling for all React components.
  - **App.js**: Main application component.
  - **index.css**: Global CSS styles.
  - **index.js**: Entry point of the application.

## Installation and Setup

### Prerequisites

- Node.js
- npm or yarn
  
### Dependencies

- **React**: Ensure that you have React installed to use React components and hooks.
- **Slick Carousel**: Install `slick-carousel` for the carousel functionality and its CSS.
- **React Slick**: Install `react-slick` to integrate Slick Carousel with React.

### Steps to Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/username/wm-portfolio.git
   cd wm-portfolio
2. Install Dependencies
   ```bash
   npm install
3. Install React and React DOM if not already installed:
   ```bash
   npm install react react-dom
4. Install Slick Carousel:
   ```bash
   npm install slick-carousel
5. Install React Slick:
   ```bash
   npm install react-slick
6. Install Styled Components:
   ```bash
   npm install styled-components

### Usage 

Running the Deployment Server
```bash
npm start
```

## Code Style Guide


### Font Family : Use 'Popppins', sans-serif for all elements.
   ```bash
   @import url('https://fonts.googleapis.com/css?family=Poppins:200,300,400,500,600,700,800,900&display=swap');
```
### Class Naming Conventions
- Use BEM (Block Element Modifier) naming conventions where appropriate
- Prefix class names related to specific sections (e.g. `c-` for classes in careers page, `a-` for ai page)

### Layout and Structure 
- Use flexbox for layout and alignment
- Ensure responsive design using media queries for different screen sizes mainly desktop, tablet and mobile view.



