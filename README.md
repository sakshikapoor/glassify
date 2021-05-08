# GLASSIFY
glassify your HTML components!

# HOW TO USE:

1. To install the package using NPM use the following command <br/> ``npm install glassify``
2. To use the CSS from Glassify that was installed from NPM, import it directly in src/style.css or src/style.scss <br/>
```@import url('glassify/styles.css');```


# NPM Link:
https://www.npmjs.com/package/glassify
  
# Simple Glass effect usage:

use css class `glassify` in css styles

```
<div class="glassify">
    Random HTML here!
</div>
```

![Example](https://drive.google.com/uc?export=view&id=1zLke-4oyithawCsuMbGUTigmOWlE8_E9)


# Dark Glass effect usage:

use css class `glassify-dark` to make the glass darker 

```
<div class="glassify glassify-dark">
  Random HTML in a dark glass!
</div>
```

![Example](https://drive.google.com/uc?export=view&id=1z7B2gESm6Abr-QdX7ONsLk9ZnOnFfI0J)


# Glass Shapes

import shapes like star, arrows and message boxes with simple css:

css classes for shapes:

- `glassify-star` for Star 
- `glassify-left` for Left Arrow 
- `glassify-right` for Right Arrow 
- `glassify-cicle` for Circle 
- `glassify-message` for message box

* Use any of the above CSS classes along with `glassify-shapes` to transform your HTML div into a shape

Usage:

```
<div class="glassify-shapes {{css class}}"></div>
```

The Final Result will look like this:

![Example](https://drive.google.com/uc?export=view&id=1kstzjQFoS9wPuKVmRSp586BOW3gXzWbf)

To use shapes with a dark tint use `glassify-dark` class along with the shapes class.

Example:

```
<div class="glassify-shapes glassify-star glassify-dark"></div>
```

![Example](https://drive.google.com/uc?export=view&id=1idu5H4iHhnB2au6P9ugaVdiAYePryC9a)
