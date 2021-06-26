---
layout: default_card
title: Research
nav_order: 3
permalink: /research/
description: "Atit Gaonkar - Currently researching on Data Availability vs Data Security. Also takes interest in Number Theory and it's Application"
---

<style>

.horizontal-rule{
    border-top: 1px solid #DDD;
}

</style>

# Research
{: .no_toc }

"I grew up thinking that a research scientist was a natural thing to be." - Stephen Hawking
{: .fs-4 .fw-100}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

### Blockchain
{: .d-inline-block .mr-2}

In-Progress
{: .label .label-yellow .ml-3}

[Blockchain Research Lab, Arizona State University](https://blockchain.asu.edu/){: .target-blank}, Tempe, USA
{: .mb-0}

Nov 2020 - Present
{: .mb-2}

<div class="horizontal-rule mb-4"></div>

<!-- {: .d-inline-block } -->


Currently working with [Dr. Dragan Boscovic]() on "Cybersecurity Considerations for Blockchain Systems".

Assess levels of cybersecurity risks of blockchain-based systems by developing a light-weight “Monitoring Client” on an IoT device to monitor and log device states, feature set, handshake protocol, etc through Hyperledger Fabric. Create a private dash blockchain infrastructure to record static information as well as dynamic changes to the IoT devices. Use Petri nets to model cybersecurity risks of the system.

Current Status: <strong>Under Developement</strong>



### Mathematics (Individual Research)
{: .d-inline-block }

Under Review
{: .label .label-green .ml-3}

<div class="horizontal-rule mb-4"></div>

Identification of unique patterns and sequences in the process of exponentiation. ([Number Theory](https://en.wikipedia.org/wiki/Number_theory){: .target-blank})

Current Status: <strong>Under Peer Review</strong>





<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
  AOS.init();
  $(window).on('load', function() {
        $(window).scrollTop(0);
        $('.main-content-wrap').scrollTop(0);
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