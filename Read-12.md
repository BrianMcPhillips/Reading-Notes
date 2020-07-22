"Easily Create Stunning Animated Charts With Chart.js"
    -Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They're easier to look at and convey data quickly, but they're not always easy to create. 
    -Drawing a line chart, to draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page. Next we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element.
    -Drawing a pie chart, our line chart is complete, so let's move on to our pie chart. First, we need the canvas element. Next we need to get the context to instantiate the chart.
    -Drawing a bar chart, finally let's add a bar chart to our page. Happile the syntax for the bar chart is very similiar to the line chart we've already added. First, we add the canvas element: next we need to retrieve the element and create the graph
"Basic Usage"
    -The <canvas> element, At first sight a <canvas> looks like the <img> element, with the only clear difference being that it doesn't have the src and alt attributes.
    -Fallback content, The <canvas> element differs from an <img> tag in that, like for <video>, <audio> or <picture> elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, you should always provide fallback content to be displayed by those browsers.
    -The rendering context, the <canvas> element creates a fixed-size drawing surfave that exposes one or more rendering contexts, which are used to create and manipulate the content shown.
    -Checking for support, the fallback content is displayed in browsers which do not support <canvas>
"Drawing shapes with Canvas"
    -Before we can start drawing, we need to talk about the canvas grid or coordinate space. 