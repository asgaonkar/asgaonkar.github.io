---
layout: default_card
title: Research
nav_order: 3
permalink: /research/
description: "Atit Gaonkar | Research"
---

# Research
{: .no_toc }

"I grew up thinking that a research scientist was a natural thing to be." - Stephen Hawking
{: .fs-4 .fw-100}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Independent Research

### Computer Science (Security)
{: .d-inline-block }

In-Progress
{: .label .label-yellow .ml-3}

Tradeoff between Data availability and Data security: "Is there a need for Dynamic Security Implementation ?" ([Data Security](https://en.wikipedia.org/wiki/Data_security){: .target-blank})

Current Status: <strong>Literature Survey</strong>



### Mathematics
{: .d-inline-block }

Under Review
{: .label .label-green .ml-3}

Identification of unique patterns and sequences in the process of exponentiation. ([Number Theory](https://en.wikipedia.org/wiki/Number_theory){: .target-blank})

Current Status: <strong>Under Peer Review</strong>


<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
  AOS.init();
  $(window).on('load', function() {
        for(var i=0;i<document.getElementsByClassName('bootstrap-iso').length;i++)
        {
            document.getElementsByClassName('tags')[i].setAttribute("id", document.getElementsByClassName('bootstrap-iso')[i].getElementsByTagName('h3')[0].getAttribute('id'));
        }
        AOS.refresh();
        var $animation_elements = $('.bootstrap-iso');
        var $window = $(window);
        var window_height = $window.height();
        var window_top_position = $window.scrollTop();
        var window_bottom_position = (window_top_position + window_height);
        $('.target-blank').attr('target','blank');
        $('pre').addClass("mb-0");
        $('p > a.no-mb').parent().addClass("mb-0");
        $('a > img').parent().addClass("image-link");
        $('img.logo-link').parent().attr('target','blank');
        $('.main-content-wrap').on('scroll', function() {
            console.log("triggered");
            $.each($animation_elements, function() {
                var $element = $(this);
                var element_height = $element.outerHeight();
                var element_top_position = $element.offset().top;
                var element_bottom_position = (element_top_position + element_height);
                if ((element_bottom_position >= window_top_position) && (element_top_position <= window_bottom_position)) {
                    $element.addClass('aos-animate');
                } else {
                    $element.removeClass('aos-animate');
                }
            });
        });
        $('.main-content-wrap')[0].scrollTop += 1;
        $('.main-content-wrap')[0].scrollTop -= 1;
  });
</script>