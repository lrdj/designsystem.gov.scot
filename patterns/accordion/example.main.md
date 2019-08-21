---
layout: example
parent: pattern.accordion
type: example
scripts:
  - /patterns/accordion/script.js
---

<style>
    
</style>

<div class="accordion">
    <div class="accordion-item">
        <input type="checkbox" class="visually-hidden  accordion-item__control" id="panel-1" aria-labelledby="panel-1-heading">
        <div class="accordion-item__header">
            <h3 id="panel-1-heading" class="accordion-item__title">
                Accordion (<abbr title="Graphical user interface">GUI</abbr>)
            </h3>
            <span class="accordion-item__indicator"></span>
            <label class="accordion-item__label" for="panel-1"><span class="visually-hidden">Show this section</span></label>
        </div>
        <div class="accordion-item__body">
            <p>The accordion is a graphical control element comprising a vertically stacked list of items, such as labels or thumbnails. Each item can be "expanded" or "collapsed" to reveal the content associated with that item. There can be zero expanded items, exactly one, or more than one item expanded at a time, depending on the configuration.</p>

            <p>The term <a href="foo">stems</a> from the musical accordion in which sections of the bellows can be expanded by pulling outward.</p>

            <p>A common example of an accordion is the Show/Hide operation of a box region, but extended to have multiple sections in a list.</p>

            <p>An accordion is similar in purpose to a tabbed interface, a list of items where exactly one item is expanded into a panel (i.e. list items are shortcuts to access separate panels).</p>
        </div>
    </div>

    <div class="accordion-item">
        <input type="checkbox" class="visually-hidden  accordion-item__control" id="panel-2" aria-labelledby="panel-2-heading">
        <div class="accordion-item__header">
            <h3 id="panel-2-heading" class="accordion-item__title">
                User definition
            </h3>
            <span class="accordion-item__indicator"></span>
            <label class="accordion-item__label" for="panel-2"><span class="visually-hidden">Show this section</span></label>
        </div>
        <div class="accordion-item__body">
            <p>Several windows are stacked on each other. All of them are "shaded", so only their captions are visible. If one of them is clicked, to make it active, it is "unshaded" or "maximized". Other windows in accordion are displaced around top or bottom edge.</p>
        </div>
    </div>

    <div class="accordion-item">
        <input type="checkbox" class="visually-hidden  accordion-item__control" id="panel-3" aria-labelledby="panel-3-heading">
        <div class="accordion-item__header">
            <h3 id="panel-3-heading" class="accordion-item__title">
                Examples
            </h3>
            <span class="accordion-item__indicator"></span>
            <label class="accordion-item__label" for="panel-3"><span class="visually-hidden">Show this section</span></label>
        </div>
        <div class="accordion-item__body">
            <p>A common example using a GUI accordion is the Show/Hide operation of a box region, but extended to have multiple sections in a list.</p>

            <p>SlideVerse is an accordion interface providing access to web content.</p>

            <p>The list view of Google Reader also features this.</p>

            <p>Apple has some roll-over accordions. For example (as of December 2008), the left column of the page includes three categories that expand on roll-over: "All Downloads", "Top Apple Downloads", and "Top Downloads".</p>
        </div>
    </div>
</div>



<p><em>Example content from <a href="https://en.wikipedia.org/wiki/Accordion_(GUI)">Wikipedia</a></em></p>