<!-- # LAB | CSS - Recipes Clone -->

## Learning Goals

- Create a webpage using basic HTML tags (head, body, headings, paragraphs, images and lists)
- Create and link an external CSS stylesheet with an HTML document.
- Use id and class selectors to apply CSS styles to elements on a webpage.
- Display images in a webpage using HTML image tags or a CSS background property.

## Introduction

So far, we have learned the basics of CSS (selectors, box-model and styling fonts). We have also covered Variables, a more advanced concept.

You are now going to put into practice all of this with the Apple Pie recipe page. You will add styling to the `index.html` you coded in the previous Lab. The goal is to use CSS to present the content in a more organized (think Information Architecture) and appealing way (think UI).

<br>

## Requirements

<br>

- Make sure you use `class` and `id` selectors throughout your exercise. Remember, only use type selectors if you want to modify *every* element of that type
- Use [normalize.css](https://necolas.github.io/normalize.css/) to reset the browser styles
- Use an external CSS stylesheet called `style.css` to style the HTML page
- Submit the link to your GitHub repo with the solution in the student portal

<br>

## Instructions

<br>

You will be working in the `apple-pie` folder. 

First, you need to create a folder called `css` where you will store the CSS files.

The first CSS file you need to create will be used to reset the browser default styles. For that, we are going to use [normalize.css](https://necolas.github.io/normalize.css/). Normalize.css is a small CSS file that provides better cross-browser consistency in the default styling of HTML elements.

The second file you need to create is `style.css`. You will add your custom CSS styles in this one. The folder structure now looks like this:

```shell
apple-pie       
    ├── index.html
    └── css
        ├── normalize.css
        └── style.css
```   

After creating this file, you should connect both CSS files to your HTML using the `<link>` tag in the `<head>` of your `index.html` document.

```html
<link rel="stylesheet" href="css/normalize.css">
<link rel="stylesheet" href="css/style.css">
```

<br>

#### Images

<br>

- [Apple Pie](https://education-team-2020.s3.eu-west-1.amazonaws.com/uxui/lab-recipes-apple-pie.jpeg)
- [Recipe Info - 1](https://education-team-2020.s3.eu-west-1.amazonaws.com/uxui/lab-recipes-recipe-info.png)
- [Recipe Info - 2](https://education-team-2020.s3.eu-west-1.amazonaws.com/uxui/lab-recipes-recipe-info-2.png)

<br>

## Deliverable

<br>

Please find a screenshot of the expected results below:
<br>

![Apple Pie](https://ih-materials.s3-eu-west-1.amazonaws.com/java/apple-pie-recipe-css.jpg)

<br>

## Extra Resources

<br>

- [CSS - Reference from MDN](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [CSS - How to set up a background image](https://developer.mozilla.org/en/docs/Web/CSS/background-image)

<br>

**Happy coding!** 