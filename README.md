# Interactive Web Components

This JavaScript code implements various interactive components for a web page, including modal windows, scrolling buttons, tabbed content, navigation menu animations, sticky navigation, lazy loading images, and a slider.

## Features

- Modal window: Users can open and close a modal window with overlay.
- Button scrolling: Clicking a button scrolls to a specific section of the page.
- Page navigation: Users can navigate to different sections of the page using the navigation menu.
- Tabbed component: Displays different content based on the selected tab.
- Menu fade animation: Navigation menu items fade out when not hovered over.
- Sticky navigation: The navigation menu sticks to the top of the page on scroll.
- Reveal sections: Sections of the page are revealed as the user scrolls.
- Lazy loading images: Images are loaded only when they come into view.
- Slider: Users can navigate through a series of slides.

## How to Use

1. Open the `index.html` file in your browser.
2. Explore the different interactive components:
   - Click buttons with the class `.btn--show-modal` to open a modal window.
   - Click the button with the class `.btn--scroll-to` to scroll to a specific section of the page.
   - Click navigation menu items to navigate to different sections of the page.
   - Click tabs in the tabbed component to view different content.
   - Hover over navigation menu items to see a fade animation.
   - Scroll down the page to reveal hidden sections.
   - Observe lazy loading of images as you scroll.
   - Navigate through slides using the slider.

## Code Explanation

- Various event listeners are used to handle user interactions and trigger specific actions.
- Intersection Observer API is utilized for lazy loading images and sticky navigation.
- Functions are defined to handle opening/closing modal windows, scrolling to sections, switching tabs, animating navigation menu, implementing sticky navigation, revealing sections, and navigating slides in the slider.
