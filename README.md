# Apple Website Clone

This project is a **responsive clone** of the Apple website, built with modern technologies such as **Vite**, **React**, **Tailwind CSS**, and **GSAP** for smooth animations. The design replicates Apple's clean and minimalist aesthetic, optimized for all devices.

![Apple Website Homepage]([./screenshots/homepage.png](https://github.com/SiddheshJagdale/Apple-Website/blob/master/images/homepage.png))

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [License](#license)

## Features

- **Responsive Design**: Fully responsive and works seamlessly across desktops, tablets, and mobile devices.
- **Smooth Animations**: Uses GSAP for creating smooth animations and interactions.
- **Optimized for Performance**: Fast load times and efficient rendering with Vite's optimized build process.
- **Modern UI**: Clean, minimalistic design similar to Apple's official website.

## Technologies Used

| Technology     | Description                                        | Icon                                                                 |
|----------------|----------------------------------------------------|----------------------------------------------------------------------|
| Vite           | Next-generation build tool for fast development.   | ![Vite](https://img.shields.io/badge/-Vite-646CFF?logo=vite&logoColor=white&style=for-the-badge) |
| React          | Frontend library for building user interfaces.     | ![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=white&style=for-the-badge) |
| Tailwind CSS   | Utility-first CSS framework for rapid styling.     | ![TailwindCSS](https://img.shields.io/badge/-Tailwind_CSS-38B2AC?logo=tailwindcss&logoColor=white&style=for-the-badge) |
| GSAP           | High-performance JavaScript animation library.     | ![GSAP](https://img.shields.io/badge/-GSAP-88CE02?logo=greensock&logoColor=white&style=for-the-badge) |

## Installation

Follow these steps to set up and run the project locally.

### Prerequisites

Ensure you have the following tools installed:

- [Node.js](https://nodejs.org/) (version 14+)
- [Git](https://git-scm.com/)

### Steps

1. Clone the repository:

    ```bash
    git clone https://github.com/SiddheshJagdale/Apple-Website.git
    cd Apple-Website
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Start the development server:

    ```bash
    npm run dev
    ```

4. Open the project in your browser at `http://localhost:3000`.

### Build for Production

To build the project for production:

```bash
npm run build
├── public/                    # Public assets like images and fonts
│   ├── apple-logo.png
│   └── ...
├── src/
│   ├── assets/                # Static images and other assets
│   ├── components/            # Reusable React components
│   │   ├── Header.jsx         # Header component
│   │   ├── Footer.jsx         # Footer component
│   │   ├── HeroSection.jsx    # Hero section component
│   │   └── ...
│   ├── pages/                 # Pages like Home, Products
│   │   ├── HomePage.jsx       # Main homepage
│   │   └── ProductPage.jsx    # Product detail page
│   ├── styles/                # Tailwind and global styles
│   ├── App.jsx                # Main application file
│   ├── main.jsx               # Entry point for React
│   └── ...
├── .gitignore                 # Git ignore file
├── tailwind.config.js         # Tailwind CSS configuration
├── vite.config.js             # Vite configuration
└── package.json               # Project dependencies and metadata
