Learning to use Owl Carousel.
* Technologies:
* jQuery
* CSS
* HTML
* Owl Carousel

```javascript
// HTML
<div class="services owl-carousel">

// JS
$(".services").owlCarousel({
    margin:20,
    loop: true,
    autoplay: true,
    autoplayTimeout:2000,
    autoplayHoverPause:true,
    responsive: {
        0:{
            items:1
        },
        600:{
            items:2
        },
        1000:{
            items:3
        }
    }
});
```
