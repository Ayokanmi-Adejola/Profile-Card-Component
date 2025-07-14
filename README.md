# Frontend Mentor - Profile Card Component Solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ) Frontend Mentor challenges help you improve your coding skills by building realistic projects.



## Overview

### The challenge

- Build out the profile card component and get it looking as close to the design as possible

### Screenshot

![Profile Card Component](./design/desktop-preview.jpg)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Custom background patterns

### What I learned

This project helped me improve my skills with CSS positioning and creating visually appealing card components. I particularly enjoyed working with:

- CSS custom properties (variables) for consistent color themes
- Positioning background patterns for visual interest
- Creating a responsive card layout that works on different screen sizes
- Using flexbox for alignment and spacing

Some code snippets I'm proud of:

```html
<div class="profile-info">
  <img src="IMAGES/ayokanmi.jpg" alt="Ayokanmi Adejola" class="profile-img">
  <div class="name-age">
    <h1>Ayokanmi Adejola</h1>
    <span class="age">21</span>
  </div>
  <p class="location">Nigeria</p>
</div>
```

```css
body {
  font-family: 'Kumbh Sans', sans-serif;
  background-color: var(--dark-cyan);
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  font-size: 18px;
  background-image: url('./images/bg-pattern-top.svg'), url('./images/bg-pattern-bottom.svg');
  background-position: right 50vw bottom 50vh, left 50vw top 50vh;
  background-repeat: no-repeat;
  background-size: 100%;
}
```

### Continued development

In future projects, I want to focus more on:

- Advanced CSS animations to add subtle interactive elements
- Implementing more complex background patterns
- Improving accessibility features
- Exploring CSS Grid for more complex layouts

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - Comprehensive reference for HTML and CSS
- [CSS-Tricks](https://css-tricks.com/) - Great tutorials on flexbox and positioning
- [Google Fonts](https://fonts.google.com/) - For the Kumbh Sans font used in this project

## Author

- Frontend Mentor - [@Ayokanmi-Adejola](https://www.frontendmentor.io/profile/Ayokanmi-Adejola)
