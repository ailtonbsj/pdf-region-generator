Generate a modern Single Page Application. Follow the requisites:

# General requisites:

- All application needs to work on frontend using HTML, CSS and Javascript.
- Don't use frameworks like Angular, React or Vue.
- Always use beautiful fonts for web like Roboto, Helvetica, etc. Do not use fonts that diverge from Material UI Design.
- Always use free icons libraries like Material Symbols, Font Awesome, Bootstrap Icons, etc.
- By default the application will use brazilian portuguese language.
- Use a responsive layout to work on both desktop and mobile.
- The application needs to be a feature to enable and disable dark mode.

## Template Main Page

- Needs to have a toolbar on top this page with a sandwich menu button to show and hide side nav bar.
- The top toolbar needs to have the name of application: Gerador de região para PDF.
- This page need to have a sidenav for nagivate to others pages.
- A main content with show all others pages that exists in this app.

## PDF Region Generation

- This page will have a file input that accept only a pdf file.
- When select a pdf a canvas of the pdf will be load, show just first page in 100% of zoom. Just first page is load as an background static image.
- It will be possible of select a region of the canvas geneting a area with x, y, width and height value in pt.
- To activate the feature of select a region will be necessary set a name for region before using a input field.
- The regions created need to have a color and a text in the center of the region.
- A button will label "Generate code" will generate some snippets of code with values of the region.
- Here is a snippet of an region, for example:

`stripper.addRegion("nameOfTheRegion", new Rectangle(x, y, width, height));`

- the values x, y, width and height of the region need to be in integer.
- The snippet of all regions will be copy automatic when clicked in "Generate code" button.