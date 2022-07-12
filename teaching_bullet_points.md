# BNTA Assessment Centre - Demo Notes

High-level notes for people delivering content at an assessment centre. The aim of the session is to build a small web page with header, main and footer. Header will include title and nav bar, main will have an image and three posts, footer will have a copyright notice. Basic styling and a JS file adding functionality to the "Dark Mode" button.

## HTML

- Start point will include an empty HTML file. Demo keyboard shortcuts with `!`/`html` + `tab` to add boilerplate.

- Brief explanation of `head` - add title

- Opening/Closing tags

- Semantic HTML and why it's important

- `header` with `h1`

- `nav` > `ul` > `li`

- `main` > first `section` > `p`

- `img` - Placebear link in notes, could use something else

- Sections for posts - `header` and `main` again

- `h2` in header, `h3`, `h4`, `p` with lorem ipsum in post sections

- Copyright notice in `footer` (link in notes)


## CSS

- Empty file in start point

- Add link to HTML file

- Add background colour to body - can use colour palette in notes

- Google font

- _[Optional]_ Explain importance of colours in accessibility

- Colour `h3` tags

- Add `.post` class and style

- Add `#title-section` id and style


## JavaScript

- Brief discusion of JS - event driven, designed to run in the browser

- Add link to HTML file

- Add `button`s to header:

```html
<button id="dark-mode-button">Dark Mode</button>
```

- Explain action flow

- Add event listener to button to `console.log` message

- Expand listener to:
	- Change `body` background colour and text colour
	- Change title section border
	- Change post section border
	- Change `h3` text colour

- Briefly give high-level explanation of variables, functions and for-loops at appropriate time, provided there is time.