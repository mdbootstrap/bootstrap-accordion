# Free Bootstrap Accordion Component

Responsive accordion built with the latest Bootstrap 5. Accordion is a vertically collapsing element to show and hide content via class changes.

Build vertically collapsing accordions in combination with our Collapse JavaScript plugin.

<p><strong>How to use it?</strong></p>
<p class="mb-2">
<strong>1. </strong>Download<a target="_blank" href="https://mdbootstrap.com/docs/standard/"> MDB 5 - free UI KIT</a></p>
<p class="mb-2"><strong>2. </strong>Choose your favourite customized example and click <code>show code</code> to see the code</p>
<p class="mb-3"><strong>3. </strong>Copy & paste the code into your MDB project</p>

--------------------

[📄 **Documentation & usage guide**](https://mdbootstrap.com/docs/standard/components/accordion/)

These components were built with a **free Material Design UI Kit for the latest Bootstrap 5**.

<img height="25" src="https://mdbootstrap.com/img/Marketing/general/logo/medium/mdb-r.png">  [![GitHub Stars](https://img.shields.io/github/stars/mdbootstrap/mdb-ui-kit?label=Star%20now&style=social)](https://github.com/mdbootstrap/mdb-ui-kit/)

---------------------

 <h2 class="mb-4">Basic example</h2> 
 
```html
<div class="accordion" id="accordionExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingOne">
      <button
        data-mdb-collapse-init
        class="accordion-button"
        type="button"
        data-mdb-toggle="collapse"
        data-mdb-target="#collapseOne"
        aria-expanded="true"
        aria-controls="collapseOne"
      >
        Accordion Item #1
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-mdb-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the first item's accordion body.</strong> It is hidden by default,
        until the collapse plugin adds the appropriate classes that we use to style each
        element. These classes control the overall appearance, as well as the showing and
        hiding via CSS transitions. You can modify any of this with custom CSS or
        overriding our default variables. It's also worth noting that just about any HTML
        can go within the <strong>.accordion-body</strong>, though the transition does
        limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingTwo">
      <button
        data-mdb-collapse-init
        class="accordion-button collapsed"
        type="button"
        data-mdb-toggle="collapse"
        data-mdb-target="#collapseTwo"
        aria-expanded="false"
        aria-controls="collapseTwo"
      >
        Accordion Item #2
      </button>
    </h2>
    <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-mdb-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the second item's accordion body.</strong> It is hidden by
        default, until the collapse plugin adds the appropriate classes that we use to
        style each element. These classes control the overall appearance, as well as the
        showing and hiding via CSS transitions. You can modify any of this with custom CSS
        or overriding our default variables. It's also worth noting that just about any
        HTML can go within the <strong>.accordion-body</strong>, though the transition
        does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingThree">
      <button
        data-mdb-collapse-init
        class="accordion-button collapsed"
        type="button"
        data-mdb-toggle="collapse"
        data-mdb-target="#collapseThree"
        aria-expanded="false"
        aria-controls="collapseThree"
      >
        Accordion Item #3
      </button>
    </h2>
    <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-mdb-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the third item's accordion body.</strong> It is hidden by default,
        until the collapse plugin adds the appropriate classes that we use to style each
        element. These classes control the overall appearance, as well as the showing and
        hiding via CSS transitions. You can modify any of this with custom CSS or
        overriding our default variables. It's also worth noting that just about any HTML
        can go within the <strong>.accordion-body</strong>, though the transition does
        limit overflow.
      </div>
    </div>
  </div>
</div>
```

```javascript
// Initialization for ES Users
import { Collapse, initMDB } from 'mdb-ui-kit';

initMDB({ Collapse });
```
 
 <hr class="my-5">
 
 <h2 class="mb-4">Flush
</h2> 
 
```html
<div class="accordion accordion-flush" id="accordionFlushExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="flush-headingOne">
      <button
        data-mdb-collapse-init
        class="accordion-button collapsed"
        type="button"
        data-mdb-toggle="collapse"
        data-mdb-target="#flush-collapseOne"
        aria-expanded="false"
        aria-controls="flush-collapseOne"
      >
        Accordion Item #1
      </button>
    </h2>
    <div
      id="flush-collapseOne"
      class="accordion-collapse collapse"
      aria-labelledby="flush-headingOne"
      data-mdb-parent="#accordionFlushExample"
    >
      <div class="accordion-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry
        richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor
        brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor,
        sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch
        et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt
        sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat
        craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't
        heard of them accusamus labore sustainable VHS.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="flush-headingTwo">
      <button
        data-mdb-collapse-init
        class="accordion-button collapsed"
        type="button"
        data-mdb-toggle="collapse"
        data-mdb-target="#flush-collapseTwo"
        aria-expanded="false"
        aria-controls="flush-collapseTwo"
      >
        Accordion Item #2
      </button>
    </h2>
    <div
      id="flush-collapseTwo"
      class="accordion-collapse collapse"
      aria-labelledby="flush-headingTwo"
      data-mdb-parent="#accordionFlushExample"
    >
      <div class="accordion-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry
        richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor
        brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor,
        sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch
        et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt
        sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat
        craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't
        heard of them accusamus labore sustainable VHS.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="flush-headingThree">
      <button
        data-mdb-collapse-init
        class="accordion-button collapsed"
        type="button"
        data-mdb-toggle="collapse"
        data-mdb-target="#flush-collapseThree"
        aria-expanded="false"
        aria-controls="flush-collapseThree"
      >
```

```javascript
// Initialization for ES Users
import { Collapse, initMDB } from 'mdb-ui-kit';

initMDB({ Collapse });
```
         
 <hr class="my-5">
 
 <h2 class="mb-4">Borderless</h2> 
 
```html
<div class="accordion accordion-borderless" id="accordionFlushExampleX">
  <div class="accordion-item">
    <h2 class="accordion-header" id="flush-headingOneX">
      <button data-mdb-collapse-init class="accordion-button" type="button" data-mdb-toggle="collapse"
        data-mdb-target="#flush-collapseOneX" aria-expanded="true" aria-controls="flush-collapseOneX">
        Accordion Item #1
      </button>
    </h2>
    <div id="flush-collapseOneX" class="accordion-collapse collapse show"
      aria-labelledby="flush-headingOneX" data-mdb-parent="#accordionFlushExampleX">
      <div class="accordion-body">
        Placeholder content for this accordion, which is intended to demonstrate the
        <code>.accordion-flush</code> class. This is the first item's accordion body.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="flush-headingTwoX">
      <button data-mdb-collapse-init class="accordion-button collapsed" type="button" data-mdb-toggle="collapse"
        data-mdb-target="#flush-collapseTwoX" aria-expanded="false" aria-controls="flush-collapseTwoX">
        Accordion Item #2
      </button>
    </h2>
    <div id="flush-collapseTwoX" class="accordion-collapse collapse" aria-labelledby="flush-headingTwoX"
      data-mdb-parent="#accordionFlushExampleX">
      <div class="accordion-body">
        Placeholder content for this accordion, which is intended to demonstrate the
        <code>.accordion-flush</code> class. This is the second item's accordion body.
        Let's imagine this being filled with some actual content.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="flush-headingThreeX">
      <button data-mdb-collapse-init class="accordion-button collapsed" type="button" data-mdb-toggle="collapse"
        data-mdb-target="#flush-collapseThreeX" aria-expanded="false" aria-controls="flush-collapseThreeX">
        Accordion Item #3
      </button>
    </h2>
    <div id="flush-collapseThreeX" class="accordion-collapse collapse" aria-labelledby="flush-headingThreeX"
      data-mdb-parent="#accordionFlushExampleX">
      <div class="accordion-body">
        Placeholder content for this accordion, which is intended to demonstrate the
        <code>.accordion-flush</code> class. This is the third item's accordion body.
        Nothing more exciting happening here in terms of content, but just filling up
        the space to make it look, at least at first glance, a bit more representative
        of how this would look in a real-world application.
      </div>
    </div>
  </div>
</div>

```

```javascript
// Initialization for ES Users
import { Collapse, initMDB } from 'mdb-ui-kit';

initMDB({ Collapse });
```
 <hr class="my-5">
 <h2 class="mb-4">With icons</h2> 
 
```html
<div class="accordion" id="accordionExampleY">
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingOneY">
      <button data-mdb-collapse-init class="accordion-button" type="button" data-mdb-toggle="collapse"
        data-mdb-target="#collapseOneY" aria-expanded="true" aria-controls="collapseOneY">
        <i class="fas fa-question-circle fa-sm me-2 opacity-70"></i>Accordion Item #1
      </button>
    </h2>
    <div id="collapseOneY" class="accordion-collapse collapse show" aria-labelledby="headingOneY"
      data-mdb-parent="#accordionExampleY">
      <div class="accordion-body">
        <strong>This is the first item's accordion body.</strong> It is hidden by
        default, until the collapse plugin adds the appropriate classes that we use to
        style each element. These classes control the overall appearance, as well as
        the showing and hiding via CSS transitions. You can modify any of this with
        custom CSS or overriding our default variables. It's also worth noting that
        just about any HTML can go within the <code>.accordion-body</code>, though the
        transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingTwoY">
      <button data-mdb-collapse-init class="accordion-button collapsed" type="button" data-mdb-toggle="collapse"
        data-mdb-target="#collapseTwoY" aria-expanded="false" aria-controls="collapseTwoY">
        <i class="fas fa-question-circle fa-sm me-2 opacity-70"></i>Accordion Item #2
      </button>
    </h2>
    <div id="collapseTwoY" class="accordion-collapse collapse" aria-labelledby="headingTwoY"
      data-mdb-parent="#accordionExampleY">
      <div class="accordion-body">
        <strong>This is the second item's accordion body.</strong> It is hidden by
        default, until the collapse plugin adds the appropriate classes that we use to
        style each element. These classes control the overall appearance, as well as
        the showing and hiding via CSS transitions. You can modify any of this with
        custom CSS or overriding our default variables. It's also worth noting that
        just about any HTML can go within the <code>.accordion-body</code>, though the
        transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingThreeY">
      <button data-mdb-collapse-init class="accordion-button collapsed" type="button" data-mdb-toggle="collapse"
        data-mdb-target="#collapseThreeY" aria-expanded="false" aria-controls="collapseThreeY">
        <i class="fas fa-question-circle fa-sm me-2 opacity-70"></i>Accordion Item #3
      </button>
    </h2>
    <div id="collapseThreeY" class="accordion-collapse collapse" aria-labelledby="headingThreeY"
      data-mdb-parent="#accordionExampleY">
      <div class="accordion-body">
        <strong>This is the third item's accordion body.</strong> It is hidden by
        default, until the collapse plugin adds the appropriate classes that we use to
        style each element. These classes control the overall appearance, as well as
        the showing and hiding via CSS transitions. You can modify any of this with
        custom CSS or overriding our default variables. It's also worth noting that
        just about any HTML can go within the <code>.accordion-body</code>, though the
        transition does limit overflow.
      </div>
    </div>
  </div>
</div>

```

```javascript
// Initialization for ES Users
import { Collapse, initMDB } from 'mdb-ui-kit';

initMDB({ Collapse });
```
 <hr class="my-5">
 <h2 class="mb-4">Always open</h2> 
 
```html
<div class="accordion" id="accordionPanelsStayOpenExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingOne">
      <button data-mdb-collapse-init class="accordion-button" type="button" data-mdb-toggle="collapse"
        data-mdb-target="#panelsStayOpen-collapseOne" aria-expanded="true" aria-controls="panelsStayOpen-collapseOne">
        Accordion Item #1
      </button>
    </h2>
    <div id="panelsStayOpen-collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne">
      <div class="accordion-body">
        <strong>This is the first item's accordion body.</strong> It is shown by default,
        until the collapse plugin adds the appropriate classes that we use to style each
        element. These classes control the overall appearance, as well as the showing and
        hiding via CSS transitions. You can modify any of this with custom CSS or overriding
        our default variables. It's also worth noting that just about any HTML can go within
        the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingTwo">
      <button data-mdb-collapse-init class="accordion-button collapsed" type="button" data-mdb-toggle="collapse"
        data-mdb-target="#panelsStayOpen-collapseTwo" aria-expanded="false"
        aria-controls="panelsStayOpen-collapseTwo">
        Accordion Item #2
      </button>
    </h2>
    <div id="panelsStayOpen-collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo">
      <div class="accordion-body">
        <strong>This is the second item's accordion body.</strong> It is hidden by default,
        until the collapse plugin adds the appropriate classes that we use to style each
        element. These classes control the overall appearance, as well as the showing and
        hiding via CSS transitions. You can modify any of this with custom CSS or overriding
        our default variables. It's also worth noting that just about any HTML can go within
        the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingThree">
      <button data-mdb-collapse-init class="accordion-button collapsed" type="button" data-mdb-toggle="collapse"
        data-mdb-target="#panelsStayOpen-collapseThree" aria-expanded="false"
        aria-controls="panelsStayOpen-collapseThree">
        Accordion Item #3
      </button>
    </h2>
    <div id="panelsStayOpen-collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree">
      <div class="accordion-body">
        <strong>This is the third item's accordion body.</strong> It is hidden by default,
        until the collapse plugin adds the appropriate classes that we use to style each
        element. These classes control the overall appearance, as well as the showing and
        hiding via CSS transitions. You can modify any of this with custom CSS or overriding
        our default variables. It's also worth noting that just about any HTML can go within
        the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
</div>```

```javascript
// Initialization for ES Users
import { Collapse, initMDB } from 'mdb-ui-kit';

initMDB({ Collapse });
```
 
