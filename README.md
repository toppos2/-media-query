/*------------------------------------------
  Responsive Grid Media Queries - 1280, 1024, 768, 480
   1280-1024   - desktop (default grid)
   1024-768    - tablet landscape
   768-480     - tablet 
   480-less    - phone landscape & smaller
--------------------------------------------*/
@media all and (min-width: 1024px) and (max-width: 1280px) { }
 
@media all and (min-width: 768px) and (max-width: 1024px) { }
 
@media all and (min-width: 480px) and (max-width: 768px) { }
 
@media all and (max-width: 480px) { }
 
/*------------------------------------------
  Foundation Media Queries 
   http://foundation.zurb.com/docs/media-queries.html
--------------------------------------------*/
 
/* Small screens - MOBILE */
@media only screen { } /* Define mobile styles - Mobile First */
 
@media only screen and (max-width: 40em) { } /* max-width 640px, mobile-only styles, use when QAing mobile issues */
 
/* Medium screens - TABLET */
@media only screen and (min-width: 40.063em) { } /* min-width 641px, medium screens */
 
@media only screen and (min-width: 40.063em) and (max-width: 64em) { } /* min-width 641px and max-width 1024px, use when QAing tablet-only issues */
 
/* Large screens - DESKTOP */
@media only screen and (min-width: 64.063em) { } /* min-width 1025px, large screens */
 
@media only screen and (min-width: 64.063em) and (max-width: 90em) { } /* min-width 1024px and max-width 1440px, use when QAing large screen-only issues */
 
/* XLarge screens */
@media only screen and (min-width: 90.063em) { } /* min-width 1441px, xlarge screens */
 
@media only screen and (min-width: 90.063em) and (max-width: 120em) { } /* min-width 1441px and max-width 1920px, use when QAing xlarge screen-only issues */
 
/* XXLarge screens */
@media only screen and (min-width: 120.063em) { } /* min-width 1921px, xlarge screens */
 
/*------------------------------------------*/
 
 
 
/* Portrait */
@media screen and (orientation:portrait) { /* Portrait styles here */ }
/* Landscape */
@media screen and (orientation:landscape) { /* Landscape styles here */ }
 
 
/* CSS for iPhone, iPad, and Retina Displays */
 
/* Non-Retina */
@media screen and (-webkit-max-device-pixel-ratio: 1) {
}
 
/* Retina */
@media only screen and (-webkit-min-device-pixel-ratio: 1.5),
only screen and (-o-min-device-pixel-ratio: 3/2),
only screen and (min--moz-device-pixel-ratio: 1.5),
only screen and (min-device-pixel-ratio: 1.5) {
}
 
/* iPhone Portrait */
@media screen and (max-device-width: 480px) and (orientation:portrait) {
} 
 
/* iPhone Landscape */
@media screen and (max-device-width: 480px) and (orientation:landscape) {
}
 
/* iPad Portrait */
@media screen and (min-device-width: 481px) and (orientation:portrait) {
}
 
/* iPad Landscape */
@media screen and (min-device-width: 481px) and (orientation:landscape) {
}
 
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no" />


/*------------------------------------------
  Live demo samples
   - http://andrelion.github.io/mediaquery/livedemo.html
--------------------------------------------*/
