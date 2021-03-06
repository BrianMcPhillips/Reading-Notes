Html Chapter 5 - "Images"
    -The <img> element is used to add images to a web page.
    -You must always specify an src attribute to indicate the source of an image and an alt attribute to describe the content of an image.
    -You should save images at the size you will be using them on the web page and in the appropriate format.
    -Photographs are best saved as JPEGs; illustrations or logos that use flat olors are better saved as GIFs.
    -Choosing Images for your site, A picture can say a thousand words, and great images help make the difference between an average-looking site and a really engaging one.
    -Storing your images on site, If you are building a site from screatch, it is good practice to create a folder for all of the images the site uses. As a website grows, keeping images in a seperate folder helps you understand how the site is organized. Here you can see an example of the files for a website; all of the images are stored in a folder called images.
    -Adding images, to add an image into the page you need to use an <img> element. This is an empty element (which means there is no closing tag). It must carry the following two attributes: src and alt.
    -Height and Width of images: Height, this specifies the height of the image in pixels. Width, this specifies the width of the image in pixels.
    -Where to place images in your code, where an image is placed in the code will affect how it is displayed. Here are three examples of image placement that produce different results: Before paragraph, the paragraph starts on a new line after the image. Inside the start of a paragraph, the first row of text aligns with the bottom of the image. In the middle of a paragraph, the image is placed between the words of the paragraph that it appears in. 
    -Old Code Aligning images horizontally, the align attribute was commonly used to indicate how the other parts of a page should flow around an image. It has been removed from HTML5 and new websites should use CSS to control the alignment of images(as you will see on pages 411-412). 
    -Three rules for creating images, there are three rules to remember when creating images for your website: Save images in the right format, websites mainly use images in jpeg, gif, or png format. If you choose the wrong image format then your image might not look as sharp as it should and can make the web page slower to load. Save images at the right size, you should save the image at the same width and height it will appear on the website(measured in pixels). Measure images in pixels, computer screens are made up of tiny squares known as pixels. The number of pixels shown per inch of screen can vary if the user increases or decreases the resolution. Therefore, when you are saving images at the right size for use on the web you should always measure the image in terms of the width and height in pixels.
CSS Chapter 11 - "Color"
    -Color not only brings your site to life, but also helps convey the mood and avokes reactions.
    -There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
    -Color pickers can help you find the color you want.
    -It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
    -CSS3 had introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
    -CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.
    -Foreground color, the color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways: RGB value, these express color in terms of  how much red, green and blue are used to make it up. For example, rgb (100.100,90)
    -Hex codes, these are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80
    -Color names, there are 147 predefined color names that are recognized by browsers. For example: Dark Cyan.
    -Background color, CSS treats HTML elements as if it appears in a box, and the background-color property sets the color of the background for that box. You can specify your choice of background color in the same three ways you can specify foreground colors. RGB values, hex codes and color names.
    -Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker. 
    -CSS3 opacity, allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).
    -CSS3 HSL colors CSS3 introduces and entirely new and intuitive way to specify colors using hue, astruation, and lightness values.
CSS Chapter 12 - "Text"
    -There are properties to control the choice of font, size, wieght, style and spacing.
    -There is a limited choice of fonts that you can assume most people will have installed.
    -If you want to use a wider range of typefaces there are several options, but you need to have the right license to use them.
    -You can control the space between lines of text, individual letters, and words. Text can also be aligned to the left, right, center or justified. It can also be indented.
    -You can use psuedo-classes to change the style of an element when a user hovers over or clicks on a text, or when the have visited a link.
    -Choosing a typeface for your website, when choosing a typeface, it is important to understand that a browser will usually only display if it's installed on that user's computer. 
    -Techniques that offer a wider choice of typefaces, there are several ways to use fonts other than those listed on the previous page. However, typefaces are subject to copyright, so the techniques you can choose from are limited by their respective licenses.
    -If you style on a Mac, it is important to check what the typefaces look like on a PC because PC's can render type less smoothly but if you design on a PC, then it should look fine on a MAC.
    -Specifying Typefaces, The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies. 
    -Size of type, the font-size property enables you to specify a size for the font. There are several ways to specify the size of a font. The most common are: Pixels, Percentages, EMS.
    -Alignment, The text-align property allows, you to control the alignment of text. THe property can take one of four values: left, right, center, justify.
    -Vertical alignment, The vertical-align property is a common source of confusion. It is not intended to allow you to verticlaly align text in the middle of the block elements such as <p> and <div>, although it does have this effect when used with tabel cells (the<td> and <th> elements).
    -Styling links, browsers tend to show links in blue with an underline by default, and they will change the color of links that have been visited to help users know which pages they have been to.
