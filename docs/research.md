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

Completed
{: .label .label-green .ml-3}

[Blockchain Research Lab, Arizona State University](https://blockchain.asu.edu/){: .target-blank}, Tempe, USA
{: .mb-0}

Nov 2020 - Present
{: .mb-2}

<div class="horizontal-rule mb-4"></div>

<!-- {: .d-inline-block } -->


Worked with [Dr. Dragan Boscovic](https://scholar.google.com/citations?user=axO13E4AAAAJ&hl=en) on "Cybersecurity Considerations for Blockchain Systems".

Assess levels of cybersecurity risks of blockchain-based systems by developing a light-weight “Monitoring Client” on an IoT device to monitor and log device states, feature set, handshake protocol, etc through Hyperledger Fabric. Create a private hyperledge fabric blockchain infrastructure to record static information as well as dynamic changes to the IoT devices.

Using Hyperledger Fabric, we created an application that gathers both static information (the hardware attributes of a device, such as manufacturer, version number, MAC address, and so on) and dynamic information (network communication information, such as encryption keys, IP addresses, and so on). This system along with infrastructure and application was used to simulate servers utilized in IT infrastructure. In addition to monitoring all network traffic into and out of the device, the CMC sent data to a cloud-based ledger.

More specifically, the application used key-value pairs allocated to static and dynamic information to move cyberactivity records to a permissioned blockchain. This resulted in the creation of a "Digital Twin" block of cyberactivity data that was updated at regular intervals in accordance with a smart contract.

([Network Cybersecurity](https://blockchain.asu.edu/research-initiatives/network-cybersecurity/){: .target-blank})


### Mathematics (Individual Research)
{: .d-inline-block }

Confidential
{: .label .label-green .ml-3}

<div class="horizontal-rule mb-4"></div>

Identification of unique patterns and sequences in the process of exponentiation. ([Number Theory](https://en.wikipedia.org/wiki/Number_theory){: .target-blank})

```yaml
Email for more information
```




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