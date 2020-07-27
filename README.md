# html_slider_1

An html slider taking advantage of css overflow manipulation via JavaScript.

---
## Algorithm - abstract
In short, the container overflows left and right with hidden elements. When user scrolls, a smooth scroll animation plays in the indicated direction. After animation plays, container snaps (smooth scroll off) back to default position in the middle, and html elements are shifted for an appearingly seamless transition. 

## Dynamic JavaScript - customizable settings
This slider html provides the ability to set the number of elements to be shown at once in the container (1-5, even numbers aren't exactly aesthetically pleasing). It also allows user to set container height. There is an experimental time customization, where the "time" controlls how quickly the html elements are repositioned in the container after the scroll takes place (actually controls the setTimeout function timeout). Higher time works better for less elements and vice versa.
