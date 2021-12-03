# Images, Color, Text

***

## Images

There are several things to consider when selecting images for your site:

- Include an image in your web pages using HTML
- Pick which image format to use
- Show an image at the right size
- Optimize an image for use on the web to make pages load faster

Images can be used to set the tone for a site. Images should:

- Be relevant
- Convey information
- Convey the right mood
- Be instantly recognizable
- Fit the color palette

Adding Images

- To add an image to a page you need to use the `<img>` element. Know when using the element there is no closing tag
- `src` is imputted intro the tag next. This tells the browser where it can find the image file
- `alt` provides a text description of the image which describes the image if you cannot see it
- `title` can also be used with the `<img>` element to provide additional information about the image. This description is usually dipsplayed when the user hovers over the image.
  - Example: `<img src="images.jpg" alt="This is the description" title="This description shows up when you hover over the image." />`

The `img` attribute also uses two other elements to specify it's size:

- `height` specifies the height of the image in pixels
- `width` speifies the width of the image in pixels
  - Example: `<img src="image.jpg" alt="This is the description" width="600" height="450" />`

Three rules for creating images:

1. Save images in the right format
2. Save images at the right size
3. Measure images in pixels

*There are several tools you can use to edit and save images: `Adobe Photoshop` is the most popular. Other software you can use is `adobe fireworks, pixelmator, paintshop pro, paint.net`*

*Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIF.*

***

## Color

Color brings love to your web page.

You can specify colors three different ways:

1. **RGB Values** which express colors in terms of how much red, green, and blue are used to make the color.
    - Example: `rgb(100,100,90)`
2. **Hex Codes** are six-digit that represent the ammount of red green and blue in a color and when written procedes by a has or pound sign.
    - Example: `#ee3e80`
3. **Color Names** are exactly what they sound like: names of colors. There are 147 predefined color names that are recognized by browsers.
    - Example: `DarkCyan`

It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content)

***

## Text

