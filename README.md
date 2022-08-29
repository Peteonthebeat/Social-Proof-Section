# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA).

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/Peteonthebeat/Social-Proof-Section.git]
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The main thing I learned is positioning different background images and creating media queries for them. I also tried to not go overboard with the media queries like I used to for previous challenges.

@media only screen and (max-width: 800px) {
body {
background-image: url(/images/bg-pattern-top-mobile.svg),
url(/images/bg-pattern-bottom-mobile.svg);
background-position: left top, right bottom;
background-repeat: no-repeat, no-repeat;
}
}

@media only screen and (min-width: 800px) {
body {
background-image: url(/images/bg-pattern-top-desktop.svg),
url(/images/bg-pattern-bottom-desktop.svg);
background-position: left top, right bottom;
background-repeat: no-repeat, no-repeat;

    padding: 5em;

}
}

---

I am also happy that I figured out how to position items inside a flex div, as it was required for the challenge.

.name-and-verification {
display: flex;
flex-direction: column;
}

.irene {
position: relative;
top: 1.5em;
}

.anne {
position: relative;
top: 3em;
}

### Continued development

I plan to continue my learning via real-life application.

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- Website - [peteonthebeat.com]
- Frontend Mentor - [@peteonthebeat](https://www.frontendmentor.io/profile/peteonthebeat)

## Acknowledgments

My girl who gave me some tips on the background image.
