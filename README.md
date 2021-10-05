# googleClone

## Overview

### The challenge

Users should be able to:

- Build a website from scratch using very minimal assets to guide the process
- No googling (ironic)

### Screenshot

![pics/googleClone.png]()

### Links

- Live Site URL: https://henrysama58.github.io/googleClone/

## My process

- I just coded from top to bottom on my html and css. I started with the nav bar, and once I got that almost perfect, I moved on to the logo, search bar, etc. Finally, I did the media queries for mobile functionality.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

- I learned how to implement CSS Flexbox to layout elements on the page. Most of my CSS is lableled with display: flex; to make it easier, instead of using px dimensions to set width and height of my containers. I also learned how to use media queries to have better mobile functionality.

```css
@media (max-width: 630px) {

    #footer-nav {
        flex-direction: column;
    }

    #footer-left {
        justify-content: center;
    }

    #footer-right {
        justify-content: center;
    }

    .search_bar-container {
        width: 95vw;
    }

    .search_bar-input {
        width: 95vw;
    }
}
```

### Continued development

- I will be trying to implement JS for almost full functionality such as search suggestions and search links as I get more comfortable with web development.

### Useful resources

- google.com - This helped me for really seeing what my layout should look like. I used it a lot as reference and I think I will be using it in the industry. I really liked this pattern and will use it going forward.
- https://flexboxfroggy.com/ - This helped me practice laying elements out on a page before I got to work on this mini project.

## Author

- Website - [Henry Le] https://henryle.org/
