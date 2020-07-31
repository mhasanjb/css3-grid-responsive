# css3-grid-responsive
Css3 Grid System - Responsive

# Media List
  @media (min-width: 0px)    (ns) = not standard
  @media (min-width: 320px)  (vs) = very small
  @media (min-width: 576px)  (xs) = extra small
  @media (min-width: 768px)  (sm) = small
  @media (min-width: 992px)  (md) = medium
  @media (min-width: 1200px) (lg) = large
  @media (min-width: 1400px) (xl) = extra large
  @media (min-width: 1600px) (hg) = huge
*/
 # Usage 
```html
<!-- Example for xs (ns,vs,xs,sm,md,lg,xl,hg)-->
<div class="grid col-xs-1">
  <div>Item1</div>
  <div>Test</div>
  <p>Paragraph Test</p>
  <h1>etc.</h1>
</div>

<!-- Example for all media -->
<div class="grid col-ns-1 col-vs-2 col-xs-3 col-sm-4 col-md-5 col-lg-6 col-xl-7 col-hg-8">
  <div>Item1</div>
  <div>Item2</div>
  <div>Item3</div>
  <div>Item4</div>
  <div>Item5</div>
  <div>Item6</div>
  <div>Item7</div>
  <div>Item8</div>
</div>

<!-- Example for not responsive situations -->
<div class="grid col-1">
  <div>Item1</div>
  <div>Item2</div>
  <div>Item3</div>
</div>
```
