---
layout: default_project
title: Personal
nav_order: 3
parent: Projects
permalink: /projects/personal
---

<link rel="stylesheet" href="..\..\assets\css\bootstrap-iso.css" crossorigin="anonymous">


# Personal Projects
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Classifile
{: .d-inline-block }

python Watch-dog
{: .label .label-blue }

Enhancing
{: .label .label-yellow }


Code can be rendered inline by wrapping it in single back ticks.

<div class="code-example" markdown="1">
Lorem ipsum dolor sit amet, `<inline code snippet>` adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
</div>
```markdown
Lorem ipsum dolor sit amet, `<inline code snippet>` adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
```
<a href="https://github.com/asgaonkar/Classifile" class="btn btn-purple mr-2" style="color:white">Github</a>
<!-- [Github](https://github.com/asgaonkar/Classifile){: .btn .btn-purple .mr-2} -->
<!-- [Demo](){: .btn .btn-green .disabled} -->



## Scrap-on-Campus
{: .d-inline-block }

Python Scrapper
{: .label .label-blue }


Code can be rendered inline by wrapping it in single back ticks.

<div class="code-example" markdown="1">
Lorem ipsum dolor sit amet, `<inline code snippet>` adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
</div>
```markdown
Lorem ipsum dolor sit amet, `<inline code snippet>` adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
```
<a href="https://github.com/asgaonkar/Scrap-on-Campus" class="btn btn-purple mr-2" style="color:white">Github</a>
<!-- [Github](https://github.com/asgaonkar/Scrap-on-Campus){: .btn .btn-purple } -->



## US-AZ-2012 Election Visualization
{: .d-inline-block }

Data Visualization
{: .label .label-blue }
Stable
{: .label .label-green }


Code can be rendered inline by wrapping it in single back ticks.

<div class="code-example" markdown="1">
Lorem ipsum dolor sit amet, `<inline code snippet>` adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
</div>
```markdown
Lorem ipsum dolor sit amet, `<inline code snippet>` adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
```
<a href="https://github.com/asgaonkar/US-AZ-2012Election-Viz" class="btn btn-purple mr-2" style="color:white !important;">Github</a>
<a href="https://asgaonkar.github.io/US-AZ-2012Election-Viz" class="btn btn-green" style="color:white !important;">Demo</a>
<!-- [Github](https://github.com/asgaonkar/US-AZ-2012Election-Viz){: .btn .btn-purple .mr-2} -->
<!-- [Demo](https://asgaonkar.github.io/US-AZ-2012Election-Viz/){: .btn .btn-green } -->

<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
  AOS.init();
  $(window).on('load', function() {
        for(var i=0;i<document.getElementsByClassName('bootstrap-iso').length;i++)
        {
            document.getElementsByClassName('tags')[i].setAttribute("id", document.getElementsByClassName('bootstrap-iso')[i].getElementsByTagName('h2')[0].getAttribute('id'))
        }
        AOS.refresh();
        var $animation_elements = $('.bootstrap-iso');
        var $window = $(window);
        var window_height = $window.height();
        var window_top_position = $window.scrollTop();
        var window_bottom_position = (window_top_position + window_height);
        $('.main-content-wrap').on('scroll', function() {
            console.log("triggered");
            $.each($animation_elements, function() {
                var $element = $(this);
                var element_height = $element.outerHeight();
                var element_top_position = $element.offset().top;
                var element_bottom_position = (element_top_position + element_height);
                if ((element_bottom_position >= window_top_position + 100) && (element_top_position <= window_bottom_position - 50)) {
                    $element.addClass('aos-animate');
                } else {
                    $element.removeClass('aos-animate');
                }
            });
        });
  });
</script>