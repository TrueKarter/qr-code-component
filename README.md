# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](/design/screenshot.png)

### Links

- [Solution](https://github.com/TrueKarter/qr-code-component-main)
- [Live Site](https://truekarter.github.io/qr-code-component-main/)

## My process

### Built with

- Flexbox
- [SASS](https://sass-lang.com/) - CSS preprocessor
- [Next.js](https://nextjs.org/) - React framework
- [Prettier](https://prettier.io/) - For formatting

### What I learned

I used this project as an opportunity to learn SASS, a CSS preprocessor. It allowed me to nest some of my CSS selectors.

To see an example, see below:

```scss
#qr-code-container {
  padding-top: 0.938rem;
  padding-left: 0.938rem;
  padding-right: 0.938rem;

  img {
    max-width: 100%;
    border-radius: 0.625rem;
  }
}
```

While this challenge did not require a responsive design, I tried to practice using rem instead of px units, as showcased above.

In addition to nesting, I also took advantage and learned SASS variables:

```scss
$white: hsl(0, 0%, 100%);
$light-gray: hsl(212, 45%, 89%);
$grayish-blue: hsl(220, 15%, 55%);
$dark-blue: hsl(218, 44%, 22%);

body {
  font-family: "Outfit", sans-serif;
  background-color: $light-gray;
}
```

### Continued development

For the future, I want to continue to focus on using `rem` and `em` units, rather than `px`. Creating a responsive design is a factor I am working on to improve in future projects.

### Useful resources

- [ChatGPT](https://chat.openai.com/) - This helped me understand flexbox and file structure for a front-end development project. The example code snippets it provides are useful.
- [nekoCalc](https://nekocalc.com/px-to-rem-converter) - This is an amazing resource for converting `px` into `rem` and vice-versa. I recommend it to anyone who is still not well accustomed to `rem` units.

## Author

- GitHub - [TrueKarter](https://github.com/TrueKarter)
- Frontend Mentor - [@TrueKarter](https://www.frontendmentor.io/profile/TrueKarter)
- Discord - [Karter#2960]
