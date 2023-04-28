---
keywords: fastai
title: WGET this file and complete fully and thoroughly in order to be graded
toc: true
comments: true
badges: false
nb_path: _notebooks/2023-04-22-studentfile.ipynb
layout: notebook
---

### What are 5 Basic UI Elements?:

**Color: The color UI element refers to the use of different colors in user interfaces to communicate information or enhance the visual appeal of a design. Color can be used to create contrast, hierarchy, and mood in a design, and can also be used to represent branding or identity.**

**Font: The font UI element refers to the style of the text used in user interfaces. The font can impact the readability, tone, and style of a design, and can be used to reinforce a brand or identity.**

**Layout: The layout UI element refers to the arrangement of visual elements on a screen or page in a user interface. An effective layout can improve the usability, organization, and visual appeal of a design, and can help guide the user's attention to important information.**

**Icons: The icons UI element refers to small graphical representations of concepts, actions, or objects that are used in user interfaces. Icons can help communicate information quickly and efficiently, and can also enhance the visual appeal and brand identity of a design.**

**Accessibility: The accessibility UI element refers to the design of user interfaces that are usable and understandable by people with disabilities or limitations. This can include considerations such as color contrast, text size, keyboard navigation, and screen reader compatibility, among others.**


### In your own words, explain what SASS does:

**SASS is a preprocessor for CSS that allows developers to write CSS more efficiently and with more advanced features. It adds functionality such as variables, nesting, mixins, and functions, making it easier to write and maintain complex stylesheets. Ultimately, SASS helps streamline the CSS development process and improve the organization and scalability of stylesheets.**

### What are some benefits to SASS: 

**SASS provides features like variables, nesting, and mixins, which increase efficiency and productivity in CSS development. It also allows for improved organization and scalability of stylesheets, code reusability, and better readability.**


### Describe/Explain one of the more "advanced" SASS properties below in detail:

**One of the more advanced SASS properties is the @extend directive, which allows developers to share a set of CSS properties from one selector to another. The @extend directive is used to create a relationship between two selectors, where the second selector inherits all the properties of the first.**

**For example, suppose we have a button element with a default set of properties:**

```
.button {
  background-color: blue;
  color: white;
  padding: 10px;
  border-radius: 5px;
}
```
**Now, let's say we want to create a special variation of this button with a green background color. Instead of duplicating the code for the default button, we can use the @extend directive to inherit the properties of the default button and only override the background color:**

```
\.button--special {
  @extend .button;
  background-color: green;
}
```

**This will create a new selector called .button--special that inherits all the properties of .button and adds a green background color. The resulting CSS will look like this:**

```
.button, .button--special {
  background-color: blue;
  color: white;
  padding: 10px;
  border-radius: 5px;
}

.button--special {
  background-color: green;
}
```
**Using @extend instead of duplicating code reduces redundancy and improves maintainability of the stylesheet. It also allows for more flexibility in creating variations of existing styles without having to start from scratch.**

# Hacks - Insert any screenshots, code segments, etc. that you need to

## Hacks Part 1


## Hacks Part 2

<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="/FastPages/assets/css/light-theme.css">
    <link rel="stylesheet" href="/FastPages/assets/css/dark-theme.css" id="theme-link">
</head>
<body>
    <button id="theme-toggle">Toggle Theme</button>
    <script>
        const toggleButton = document.querySelector('#theme-toggle');
        const themeLink = document.querySelector('#theme-link');
        toggleButton.addEventListener('click', () => {
            if (themeLink.getAttribute('href') === '/FastPages/assets/css/light-theme.css') {
                themeLink.setAttribute('href', '/FastPages/assets/css/dark-theme.css');
            } else {
                themeLink.setAttribute('href', '/FastPages/assets/css/light-theme.css');
            }
        });
    </script>
</body>



















