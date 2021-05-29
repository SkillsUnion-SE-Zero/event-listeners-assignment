[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# Event Listeners: Assignment

## Problems

### 1: Creating Random Images

Start of with the following HTML:

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Random Images</title>
</head>
<body>
    <div>
        <label>
            Width:
            <input type="number" class="width" />
        </label>
      
        <label>
            Height:
            <input type="number" class="height" />
        </label>

        <button id="randomize">Get random image!</button>
    </div>

    <img src="" class="random-img" />

    <script src=""> </script>
</body>
</html>
```

1. Create and link a JavaScript file
1. When someone clicks the `#randomize` button:
    1. Create a URL based on this [documentation](https://source.unsplash.com/)

        e.g. It might look something like this: `https://source.unsplash.com/1600x900`
    1. Update the `img` element with the new image

#### Optional Bonuse

Using the two inputs allow the user to select the width and the height!

Tips:

- Using a search engine, research how to get the value of an inout element using javascript.

    Example: `javascript get input value`
- Consider using JavaScript Template Literals

### 2: Mouseover and Mouseout

 Your goal is to add two events `mouseover` and `mouseout` to the same element. Such that, if the text is hovered over then “mouseover” event occur and RespondMouseOver function invoked, similarly for “mouseout” event RespondMouseOut function invoked. The corresponding event name `mouseover event` or `mouseover event` is displayed in the element with `id` effect.

 1. Under the `src` directory, create files `index2.js` and `index2.html`. Link `js` file to the `html` file, and test if it's working correctly.
 1. Use the given HTML mark up provided

```HTML
<!DOCTYPE html>

    <head>
        <title>Mouseover and Mouseout</title>

    </head>

    <body>
          <button id="clickIt">Click here</button>

          <p id="hoverPara">Hover over this Text !</p>

          <b id="effect"></b>


          <script src=""> </script>
    </body>

  </html>
```






## Submission Guidelines

- Cite any relevant sources consulted during your research
- Solve the problems using your own code
- Do not copy and paste solutions from the source material
