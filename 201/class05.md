## HTML Images

   - Images can improve the design and the appearance of a web page.

   Example  
```
<img src="pic_trulli.jpg" alt="Italian Trulli">
```

HTML Images Syntax
- The HTML ```<img>``` tag is used to embed an image in a web page.

- Images are not technically inserted into a web page; images are linked to web pages. The ```<img>``` tag creates a holding space for the referenced image.

- The ```<img>``` tag is empty, it contains attributes only, and does not have a closing tag.

- The ```<img>``` tag has two required attributes:

```
src - Specifies the path to the image
alt - Specifies an alternate text for the image
```

## The src Attribute
**The required src attribute specifies the path (URL) to the image.**

Note: When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.

## The alt Attribute
**The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).**

## Image Size - Width and Height
You can use the style attribute to specify the width and height of an image.

Example
```
<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">
```

Images in Another Folder
If you have your images in a sub-folder, you must include the folder name in the src attribute:

Example:
```
<img src="/images/html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">
```

### Summary:
1. Use the HTML ```<img>``` element to define an image
2. Use the HTML src attribute to define the URL of the image
3. Use the HTML alt attribute to define an alternate text for an image, if it cannot be displayed
4. Use the HTML width and height attributes or the CSS width and height properties to define the size of the image
5. Use the CSS float property to let the image float to the left or to the right


CSS Color Values
In CSS, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values:

Same as color name "Tomato":
```
rgb(255, 99, 71)
#ff6347
hsl(9, 100%, 64%)
```

Text Color
The color property is used to set the color of the text. The color is specified by:

a color name - like "red"
a HEX value - like "#ff0000"
an RGB value - like "rgb(255,0,0)"

![img](https://th.bing.com/th/id/R.15c54ad56595dc391709c9a4066697bc?rik=4ymA67iO%2bnk3IA&pid=ImgRaw)

Example:
```
body {
  color: blue;
}

h1 {
  color: green;
}
```
Example:
```
body {
  background-color: lightgrey;
  color: blue;
}

h1 {
  background-color: black;
  color: white;
}
```

### Text Alignment
  - The text-align property is used to set the horizontal alignment of a text.
  - A text can be left or right aligned, centered, or justified.

  Example:
  ```
h1 {
  text-align: center;
}

h2 {
  text-align: left;
}

h3 {
  text-align: right;
}
```

### Text Direction
The direction and unicode-bidi properties can be used to change the text direction of an element:

Example
```
p {
  direction: rtl;
  unicode-bidi: bidi-override;
}
```