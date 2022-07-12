**Note: This is a README.md template file for you to use to describe the project you have completed. README's are used so that other developers can understand what your project is about. You will commonly see README's used on Github where they will be displayed on a project's repository. Delete this note after reading**

# BNTA - Shop landing page assessment day solution

This is a solution to the Shop landing page BNTA assessment day which will allow you to put the HTML and CSS you've learned in practice with a stretch goal of adding a Dark Mode to your site.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

**Your users should be able to:**

- Build your webpage correctly for viewing within a fullscreen desktop window using HTML & CSS

**Stretch goals:**

- Implement a Dark Mode button using HTML and JavaScript

The teaching from the first day of the assessment centre should put you in good stead for this project and what today aims to provide is a chance to put this learning into action.

### Screenshot

![](./design.websiteDoritos.jpeg)

Add a screenshot of your solution. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the sentences above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- JavaScript


### What I learned

The first thing I was able to learn was the DarkMode Feature. This was mentioned att he start of the 9am meeting and as it was okay with my team, I tasked myself with doing something that would test me to my limit. 
There were many resources for this, however as I have come to find with many peices of code, some version were much longer than they needed to be.

''''html

<div>
        <button onclick="darkMode()">Darkmode</button>
    </div>
     <script>
        function darkMode() {
          var element = document.body;
          element.classList.toggle("dark-mode");
        }
    </script>
    
  Line 65 shows the implementation of a button "onclick" meaning it reacts to a click, but what it does exactly we use on CSS. The button is entitled Darkmode as can also be seeen. The most difficult element was the toggle button, as my initial resources had either two seperate buttons or a button that doesn't allow you to revert back to light mode.
  
  ```css
  
  .dark-mode {
  background-color: black;
  color: white;
}

My Darkmode essentially changes the background colour to black, and the text colour to white, as can be seen above in the CSS Code.


  


To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```



### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

One area I would like to focus in on on more is making a more interactive website, with the use of the hover button for example. I know how to use this on a navbar but not in a flexbox and would like to be able to do this, however with more time I think it wouldn't be too much of a pressing issue.

I would really like to improve on my ability to combine text and images, and use them in combination with each other. This is something I need to work on as I am not quite at the level I should be with regards to that.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

https://www.w3schools.com/howto/howto_js_toggle_dark_mode.asp
https://www.w3schools.com/icons/

## Authors

- Website Name - [Ravi, Priscille, Arum, Faizan]

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

We had a really good team as everyone was extremely responsive, and eager to help each other. This allowed for one another to be comfortable in asking questions. 
Arum was our 'go to' for noticing errors in our code. She was really good at spotting what could be added and how it could be done, which encouraged us to help each other more.
