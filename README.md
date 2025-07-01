# Odin admin dashboard

## Table of Contents

-   [Project Description](#project-description)
-   [Directory overview](#directory-overview)
-   [Color System](#color-system)
-   [Key Features](#key-features)
-   [Resources Used](#resources-used)
-   [To-Do and Ideas for Future](#to-do-and-ideas-for-future)
-   [Рublished Website](#published-website)

## Project Description

This project is a responsive admin dashboard user interface built with HTML and CSS. It features a sidebar navigation menu, a header with search and user account sections, and a main content area displaying projects, announcements, and trending users. The design emphasizes usability, clean layout, and adaptability across desktop and mobile devices using CSS Grid and media queries. Icons and visual elements enhance the user experience throughout the dashboard.

## Directory overview

-   `/assets`
    -   `/icons` - SVG icons used throughout the UI.
    -   `/styles`
        -   `/additional-styles` - Supplemental CSS for sidebar, header, main content, cards, buttons, and other components.
        -   `/media-queries` - Responsive design CSS breakpoints.
        -   `/reset-modern` - CSS reset files for cross-browser consistency.
        -   `/variables` - CSS custom properties (global variables that define the color palette of a project and its fonts).
        -   `general-styles.css` - Base styles including font imports, and base layout.
-   `index.html` - Main HTML markup file containing the dashboard structure.

## Color System

The project uses a cohesive color palette defined as CSS variables (located in `variables` folder).
This color system provides a clean, modern, and visually accessible interface.

## Key Features

-   **Responsive Layout:** Utilizes CSS Grid and media queries to adjust layout for desktop, tablets, and mobile devices.
-   **Sidebar Navigation:** Collapsible sidebar with icons and labels, optimized for both large and small screens.
-   **Header with Search and User Info:** Includes a search input, notification icon, user avatar, and user greeting with action buttons.
-   **Project Cards:** Display of multiple project summaries with interactive icons (star, eye, fork) to represent favorites, views, and forks.
-   **Announcements & Trending Sections:** Sidebar widgets showing recent announcements and trending users with avatars.
-   **Burger Menu:** Mobile-friendly toggle button to show/hide sidebar on small screens.
-   **Clean Typography:** Uses Google Fonts (Roboto) for modern and readable text.
-   **Hover Interactions:** Visual feedback on cards and icons for better user engagement.

## Resources Used

-   A freely distributed Font for clean and versatile typography from a free library [Google Fonts - Roboto](https://fonts.google.com/specimen/Roboto).
-   SVG icons for avatars and content sources for user interface elements (stored locally in `/assets/icons`) from free packages:
    -   [Material Design Icons](https://pictogrammers.com/library/mdi/) by [Michael Richins](https://pictogrammers.com/contributor/MrGrigri/) on [Pictogrammers](https://pictogrammers.com/).
    -   [Flatflow icons](https://www.iconfinder.com/search/icons?family=flatflow) by [Anna Litviniuk](https://www.iconfinder.com/Naf_Naf) on [Iconfinder](https://www.iconfinder.com/).
-   CSS Grid and Flexbox — for layout structuring.
-   CSS Variables — for easy theming and maintainability.
-   Media Queries — for responsive design.

## To-Do and Ideas for Future

-   **JavaScript Enhancements:** Add dynamic interactivity such as filtering projects, notifications badge updates, and animated transitions.
-   **Accessibility Improvements:** Implement ARIA roles, keyboard navigation support, and focus management.
-   **Dark Mode:** Provide an alternate dark theme switch using CSS variables.
-   **Backend Integration:** Connect with an API or database to load real user/project data.
-   **User Authentication:** Add login/logout functionality and personalized user settings.
-   **Performance Optimization:** Minify CSS and optimize images/icons for faster load times.

## Published Website
