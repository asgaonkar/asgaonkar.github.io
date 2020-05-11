---
layout: default_card
title: Volunteering
nav_order: 8
permalink: /volunteering/
description: "Atit Gaonkar | Volunteering"
---

# Volunteering Experience
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---




## Full Stack Developer
{: .d-inline-block .mr-2 }

2018
{: .label .label-green}

Prem Ashram Charitable Trust, India
{: .mb-0}

Jul 2018 - Sep 2018

- Worked on developing a website following iterative SDLC approach to replace the old existing website. Front-end is supported by HTML, CSS (Bootstrap) and JS, whereas the Back-end was coded using PHP/MySQL.

- Interacting with people at various level indeed exposed me to situation where my abilities to prioritise and manage time effectively was tested It had a positive impact on me psychologically as well as physically. Taught me the importance of how a small good gesture can bring about a huge difference in others.

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
        $('.main-content-wrap')[0].scrollTop += 1;
        $('.main-content-wrap')[0].scrollTop -= 1;
  });
</script>