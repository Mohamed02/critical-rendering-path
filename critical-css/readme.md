# Critical CSS

## Steps 

- Open the index.html in an new page
- open the network tab and reload the page , 
    you will see first request to index.html , and when you preview the response, you will see the response with first
    div content is styled and second div with the class "alert-content" are not styled.

    thats because only when the style.css is loaded, the browser will combine the domtree and cssom tree to do the first paint.
- How do we write html so our html pages render quickly?

## Notes

> The Critical Rendering Path is the sequence of steps the browser goes through to convert the HTML, CSS, and JavaScript into pixels on the screen. - [1]
