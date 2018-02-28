
### PROJECT Website Optimization

#### Part 1: Optimize PageSpeed Insights score for index.html

1. Minified and inlined style.css file .
1. Minified JS .
1. Added async to javscript.
1. Added media print to print css file .
1. Optimized images (profilepic.jpg , pizzeria) .
1. Moved the google webfont link at the end of the page.

 To run the project Open the Index.html File  
 
#### Part 2: Optimize Frames per Second in pizza.html
1. deleted sizeSwitcher function and optmize changePizzaSizes (line 430 ).
1. replaced querySelector with getElementById (lines 409,413,419,532 ).
1. replaced querySelector with getElementsByClassName (lines 496 ,444 ).
1.  save the array length in a local variable (line 446)
1. moved scrollTop out from for loop (line 499 ).
1. change  loop counter from 200 to 24 and Declaring the elem variable (var elem;) in the initialisation of the for-loop (line 523 ).
1. declared the pizzasDiv variable outside the loop (line 464)
1. Added "will-change: transform" on style.css file . 
1. Added "  transform: translateZ(0); and backface-visibility: hidden;" on style.css file . 

 #####To run the project Open the pizza File  in view/pizza.html 
 #####To show javascript code open file main.js  in views/js/main.js

### Optimization Tips and Tricks
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html "nav timing api"). We didn't cover the Navigation Timing API in the first two lessons but it's an incredibly useful tool for automated page profiling. I highly recommend reading.
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/eliminate-downloads.html">The fewer the downloads, the better</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer.html">Reduce the size of text</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization.html">Optimize images</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching.html">HTTP caching</a>

### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>
