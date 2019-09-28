# animateOnScroll
Lightweight pure javascript library to animate content on scroll. 

## Installation
Download or clone repo to your project. Include animateScroll.css inside <header> and then animateScroll.js before body tag.
  
## Usage 
```html
    <div class="wrapper">
        <div class="box animateScroll animateScroll--arrival-up"></div>
        <div class="box animateScroll animateScroll--arrival-down"></div>
        <div class="box animateScroll animateScroll--arrival-left-right"></div>
        <div class="box animateScroll animateScroll--arrival-right-left"></div>
    </div>

    <script src="js/scrollAppear.js"></script>
    <script>
        let scrollEvent = new ScrollAppear('box');
        scrollEvent.scrollListener();
    </script>
</body>

```
Take a look at demo.html file :) 
