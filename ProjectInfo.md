


https://www.freecodecamp.org/news/create-a-simple-website-with-html-css-javascript/

https://www.frontendmentor.io

https://codepen.io

https://css-tricks.com/updating-a-css-variable-with-javascript

# Functional Requirements and Notes

    Light/Dark Mode toggle -- takes system preference by default, but can override with toggle

    What HTML markup (accessible) -- https://scottaohara.github.io/a11y_styled_form_controls/src/radio-button--switch/

    Use fieldset, legend, radio inputs

    Switching between light/dark Mode via JS Prefers-color-scheme media query

    Three option toggle: light/dark/system pref -- https://codepen.io/renddrew/pen/bRomab?editors=1100

    CSS Variables (custom properties) https://css-tricks.com/updating-a-css-variable-with-javascript/

    let root = document.documentElement;

    root.addEventListener("mousemove", e => {
      root.style.setProperty('--mouse-x', e.clientX + "px");
      root.style.setPropert('--mouse-y', eclientY + "px");
    });

    

    Accessibility 
        - Use correct heading tags
        - Screenreader-only text for card titles/username
        https://accessible360.com