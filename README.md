# GRIS DIOR Landing Page

## Overview

This is a landing page project inspired by the **GRIS DIOR** fragrance. The page is designed to provide an elegant and visually appealing experience using modern web technologies such as **HTML, CSS, and JavaScript**.

## Features

- **Responsive Design** – Ensures compatibility across different screen sizes.

- **SwiperJS Integration** – Implements interactive sliders for the hero section and the about section.

- **Accordion Component** – Expandable sections for additional content.

- **Smooth Animations** – Subtle effects to enhance user experience.

## Technologies Used

- **HTML5**

- **CSS3** (Including Reset Styles & Custom Styling)

- **JavaScript** (ES6+)

- **SwiperJS** for interactive sliders

- **Google Fonts** for typography styling

## Installation & Usage

1. Clone the repository:
```
 git clone https://github.com/anastasia2022be1/dior
```

2. Navigate to the project folder:

```
cd your-repo-name
```

3. Open index.html in your browser.

Alternatively, you can use Live Server in VSCode for a better experience.

## Deploy

[GRIS DIOR](https://anastasia2022be1.github.io/dior/)

## External Resources

- [Google Fonts](https://fonts.google.com/)

- [SwiperJS Documentation](https://swiperjs.com/)

- [SwiperJS Fade Effect](https://swiperjs.com/demos#effect-fade)

- [SwiperJS Autoplay](https://swiperjs.com/demos#autoplay)

- [Figma Template](https://www.figma.com/design/HuKeSMLnWYORnuaWPYhCqp/%D0%94%D0%B8%D0%BE%D1%80?node-id=0-1&p=f&t=aQwEeKUZjGYm7QFa-0)


## SwiperJS Configuration
### Hero Section Slider (top__swiper)

```
const swiperTop = new Swiper('.top__swiper', {
    effect: 'fade',
    autoplay: {
        delay: 3500,
        disableOnInteraction: false
    },
    navigation: {
        nextEl: '.swiper-button-next',
        prevEl: '.swiper-button-prev',
    }
});
```

### About Section Slider (about__slider)

```
const swiperAbout = new Swiper(".about__slider", {
    slidesPerView: 4,
    spaceBetween: 20,
    freeMode: true,
    navigation: {
        nextEl: '.swiper-button-next',
        prevEl: '.swiper-button-prev',
    }
});
```

### Accordion Functionality
```
document.querySelectorAll('.accordeon__trigger').forEach((item) => {
    item.addEventListener('click', () => {
        item.parentNode.classList.toggle('accordeon__item--active');
    });
});
```

## License
This project is for educational and portfolio purposes only. All trademarks and brand names belong to their respective owners.
