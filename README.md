# Bankist Marketing Website

This project is a marketing website for the Bankist banking app. It is built using vanilla JavaScript to manipulate the DOM directly. The website features a modal window, cookie message, smooth scrolling, page navigation, tabbed component, menu fade animation, sticky navigation, section reveal on scroll, lazy loading images, and a slider.

## Key Features

### Modal Window
- Opens and closes a modal window using JavaScript to add or remove CSS classes.
- Listens for click events on buttons and keyboard events to provide a smooth user experience.

### Cookie Message
- Displays a cookie consent message at the top of the page.
- Allows users to dismiss the message, which removes the element from the DOM.

### Smooth Scrolling
- Implements smooth scrolling for in-page navigation.
- Uses the `scrollIntoView` method for smooth transitions.

### Page Navigation
- Utilizes event delegation for efficient event handling on navigation links.
- Smoothly scrolls to sections when navigation links are clicked.

### Tabbed Component
- Provides a tabbed interface for different content sections.
- Handles tab switching using event delegation and CSS class manipulation.

### Menu Fade Animation
- Adds a fade effect to menu items when hovering over them.
- Uses event delegation to handle hover effects efficiently.

### Sticky Navigation
- Implements sticky navigation using the Intersection Observer API.
- Adds a sticky class to the navigation when the header is not intersecting the viewport.

### Reveal Sections on Scroll
- Reveals sections with a fade-in effect as the user scrolls down the page.
- Uses the Intersection Observer API to trigger animations.

### Lazy Loading Images
- Implements lazy loading for images to improve page load times.
- Replaces the `src` attribute of images with the `data-src` attribute when they enter the viewport.

### Slider
- Creates a responsive image slider with navigation dots.
- Handles slide navigation using buttons and keyboard events.
- Adds and removes active classes for the current slide and dot.

## Technical Details

- **DOM Manipulation**: Direct manipulation of the DOM using JavaScript to create interactive elements and dynamic content.
- **Event Handling**: Efficient event handling using event delegation, which improves performance by reducing the number of event listeners.
- **CSS Class Manipulation**: Adding and removing CSS classes to control visibility and styles of elements based on user interactions.
- **Intersection Observer API**: Used for implementing sticky navigation, revealing sections on scroll, and lazy loading images.
- **Responsive Design**: Ensures the website is responsive and works well on different screen sizes.

## How to Run

1. Clone the repository.
2. Open the `index.html` file in your preferred web browser.

## Getting Started with JavaScript

For help getting started with JavaScript and DOM manipulation, view the online [documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Introduction).

Check out the code to explore more about vanilla JavaScript and DOM manipulation!
