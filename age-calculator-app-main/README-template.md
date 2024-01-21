# Frontend Mentor - Age calculator app solution

This is a solution to the [Age calculator app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/age-calculator-app-dF9DFFpj-Q).Age calculator an application that help in calculating your age, saving you the stress of calculating manually. 
## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

Users should be able to:

- View an age in years, months, and days after submitting a valid date through the form
- Receive validation errors if:
  - Any field is empty when the form is submitted
  - The day number is not between 1-31
  - The month number is not between 1-12
  - The year is in the future
  - The date is invalid e.g. 31/04/1991 (there are 30 days in April)
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: See the age numbers animate to their final number when the form is submitted
- The calculated age is stored in the local storage

### the-challenge
i was not able to save the calculated age to local storage 

### Screenshot

![](./assets/images/finished-age-calculator%201.png)
![](./assets/images/finished-age-calculator%202.png)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Javascript

### What I learned

During the course of this project i learnt how well to make use of the object and arrays in javascript, i also learnt how to use dark and light mood.

To see how you can add code snippets, see below:


```css
input:checked + .slider:before {
    -webkit-transform: translateX(26px);
    -ms-transform: translateX(26px);
    transform: translateX(26px);
}
```
```js
modeToggle.addEventListener('change', function () {
        if (modeToggle.checked) {
            body.classList.add('dark-mode');
        } else {
            body.classList.remove('dark-mode');
        }
    });
```

### Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.


### Useful resources

- youtube was of great help whenever i'm strucked on a problem, with their numerous solutions on diffrent problem i was able to scale through
- ChatGPT was also very useful for this project.
- W3school materials came in handy for me on this project

## Author

- Frontend Mentor - [ajayiflorence93@gmail.com](https://www.frontendmentor.io/profile/ajayiflorence93@gmail.com)

