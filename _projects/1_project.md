---
layout: page
title: TTC - Hackathon
description: to solve the problem of assaulting operators and user experience.
img: assets/img/ttclogo.jpg
importance: 1
category: work
---
    ---
    Technical requirements:
    1.Familiar with MERN(MongoDB,Express,React,Node.js)
    2.Familiar with Bootstrap.（design an passenger app and driver app）
    3.Familiar with Web API.
    4.Investigate with some passengers and TTC drivers.
    5.Knowledge of Git/GitHub
    ---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ttchomepage.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This screenshot is TTC passenger lost and found system, which has several functions, such as user information and fourm. In terms of user information, passengers tap the presto and the bus will be recorded, including bus number, bus contact phone number etc.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/travel_record.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Within 3 hours(this is for preventing scam phone calls), passengers can contact with driver to get their lost items. Also, as we can see in the screenshot, it would show time remaining(time for you to contact drivers), bus number, bus contact phone number, and when did you get in bus.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/signin1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/signin2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sign in page.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/signup.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
</div>
<div class="caption">
    Sign up page.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
