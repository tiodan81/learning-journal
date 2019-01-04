# Task 2: Rendering the ipsum posts

Steps

1. In your HTML, sketch out a template for a single blog post. Decide what kind of element you will use to render the title, body, etc and how they will fit together. Leave this template commented out so that it doesn't render in the browser. We'll use JS to create the actual HTML, but this template can serve as a reference so we have a fixed target to build in JS.
2. Write the JS to render a single blog post. Create a function that renders a whole BlogPost. There should be a `render` function for the whole post, as well as a series of individual functions to render each each property of the BlogPost object, for example `renderTitle`. The `render` function will call the others. Each of these functions should be defined on the BlogPost prototype.
3. Render the entire blog by looping through all the posts and calling `render` on each one.
