---
layout: default_card
title: Projects @ASU
nav_order: 1
parent: Academic
grand_parent: Projects
permalink: /projects/academics/@arizona-state-university
description: "Atit Gaonkar - Undertook several projects in the field of Software Security, Computer and Network Forensics, Data Visualization and Number Theory"
extra: "Arizona State University (ASU) Projects"
---

<style>
  .hidden{
    color: white;
    user-select: none;
  }
  .down {
  position: fixed;
  bottom: 20px;
  right: 30px;
  z-index: 99;
  font-size: 18px;
  border: none;
  outline: none;
  padding: 10px;
  border-radius: 25px;
  background-image: linear-gradient(#4593fb, #227efa);
  background-color: #227efa;
  opacity: 0.75;
}
.direction{
  opacity: 0.5;
}
.down:hover {
  animation: none;
  /* opacity: 0.75; */
  box-shadow:
  0 2.8px 2.2px rgba(0, 0, 0, 0.034),
  0 6.7px 5.3px rgba(0, 0, 0, 0.048),
  0 12.5px 10px rgba(0, 0, 0, 0.06),
  0 22.3px 17.9px rgba(0, 0, 0, 0.072),
  0 41.8px 33.4px rgba(0, 0, 0, 0.086),
  0 100px 80px rgba(0, 0, 0, 0.12);
}
.blinking {
  animation: blinkingText 1.0s infinite;
  cursor: pointer;
}
.no-blinking {
  animation: none;
  cursor: pointer;
}
@keyframes blinkingText {
  0% {
    opacity: 0.35;
  }
  25% {
    opacity: 0.5;
  }
  50% {
    opacity: 0.70;
  }
  75% {
    opacity: 0.5;
  }
  100% {
    opacity: 0.35;
  }
}
a img
{
  border: 0 none;
}
.image-link
{
  text-decoration: none;
}

.horizontal-rule{
    border-top: 1px solid #DDD;
}

.last-item{
  -webkit-mask-image: -webkit-gradient(linear, left top, left bottom, from(rgba(0,0,0,0.5)), to(rgba(0,0,0,0))) !important;
}

</style>


![Direction](../../assets/images/arrow-down.png){: .img-responsive .blinking .direction .down}


# Projects @Arizona State University
{: .no_toc }

#### Display
{: .no_toc }

[Top Projects](#filter){: .btn .btn-blue .mr-4 .mb-2 .filter} [Completed](#filter){: .btn .btn-blue .mr-4 .mb-2 .filter} [Current (In-Progress)](#filter){: .btn .btn-blue .mr-4 .mb-2 .filter}


## Table of contents
{: .no_toc .text-delta }

[Hide](#){: .mt-2 .btn .toc-toggle}

1. TOC
{:toc}

---



## Food Explorer
{: .top-project .d-inline-block .completed}

Recommendation System
{: .label .label-green .ml-3}

<!-- In-Progress
{: .label .label-yellow .ml-3} -->

```yaml
Feb 2020 - April 2020
```

Unlike conventional recommendation system, Food Explorer recommends restaurants to foodies based on the quality of food. Used techniques like [Named Entity Recognition (NER)](){: .target-blank}, [Fuzzy Logic](){: .target-blank} and [Sentiment Analysis](){: .target-blank} to extract the quality of food from user reviews.

<!-- [![Food-Explorer][food-explorer-img]{: .img-responsive .noDecoration .logo .logo-link height="auto" width="150px"}][food-explorer-link]

[food-explorer-img]:  ../../assets/images/food-explorer.png
[food-explorer-link]:  https://asgaonkar.github.io/The-Hungry-Customer/ "Redirect to Food Explorer"  -->

> [#Data-Visualization](){: .target-blank} [#Machine-Learning](){: .target-blank}

<a href="https://github.com/asgaonkar/The-Hungry-Customer" class="btn btn-purple mr-2" target="blank" style="color:white">Github</a>
<a href="https://asgaonkar.github.io/The-Hungry-Customer/" class="btn btn-green mr-2" target="blank" style="color:white;">Demo</a>




## Blockchain-of-Custody 
{: .top-project .d-inline-block .completed}

Utility
{: .label .label-green .ml-3}

<!-- In-Progress
{: .label .label-yellow .ml-3} -->

```yaml
March 2020 - April 2020
```

Maintains logs for actions performed on every evidence in custody. For these evidence to be admissible in court, integrity of the evidences should be intact and hence the need for [Blockchain](){: .target-blank} to keep track of the same.

> [#Security](){: .target-blank} [#Computer-Forensics](){: .target-blank}

<a href="https://github.com/asgaonkar/Blockchain-of-Custody" class="btn btn-purple mr-2" style="color:white">Github</a>
<!-- [Github](){: .btn .btn-purple .disabled} -->




## Road to Glory
{: .top-project .d-inline-block .completed}

Analysis and Visualization
{: .label .label-green .ml-3}

<!-- In-Progress
{: .label .label-yellow .ml-3} -->

```yaml
Feb 2020 - March 2020
```

Visual Analysis to understand why [Roger Federer](){: .target-blank} is the most **Aggressive**(An aggressive player is one who is willing to put pressure on an opponent on every shot) tennis player using [Interactive Visualization](){: .target-blank}, and [Comparative Analysis](){: .target-blank}. A simple analysis of [2017 and 2018 Aus Open Finals](../../assets/images/Roger-Federer.jpg){: .target-blank} demonstrate the playing style of Roger Federer.

> [#Data-Visualization](){: .target-blank}

<a href="https://github.com/asgaonkar/Road-to-Glory" target='blank' class="btn btn-purple mr-2" style="color:white">Github</a>
<a href="https://asgaonkar.github.io/Road-to-Glory/" target='blank' class="btn btn-green" style="color:white;">Demo</a>


<!-- [Github](https://github.com/asgaonkar/Road-to-Glory){: .btn .btn-purple .mr-2} -->
<!-- [Demo](https://asgaonkar.github.io/Road-to-Glory/){: .btn .btn-green} -->


## MBR Analysis
{: .top-project .d-inline-block .completed}

Utility
{: .label .label-green .ml-3}

<!-- In-Progress
{: .label .label-yellow .ml-3} -->

```yaml
Jan 2020 - Feb 2020
```

A python utility to analyze [Master Boot Record (MBR)](){: .target-blank}. Provides important information such as Partition Type, Starting Address Value, Size of Partition.

> [#Computer-Forensics](){: .target-blank}

<a href="https://github.com/asgaonkar/Read-MBR" class="btn btn-purple mr-2" style="color:white">Github</a>
<!-- [Github](https://github.com/asgaonkar/Read-MBR){: .btn .btn-purple } -->



## Binary Exploitation 
{: .top-project .d-inline-block .completed}

Offensive Security
{: .label .label-green .ml-3}

<!-- In-Progress
{: .label .label-yellow .ml-3} -->

```yaml
Nov 2019 - Dec 2019
```

We were tasked to [pawn](){: .target-blank} as many [Binaries](){: .target-blank} (Application) as possible. This project required to utilize skills such as [Buffer Overflow](), [Format Strings](){: .target-blank}, [Arbitrary Code Execution](){: .target-blank} etc

> [#Cryotography](){: .target-blank} [#Security](){: .target-blank} [#Reverse-Engineering](){: .target-blank}


<a href="javascript:void(0)" class="btn mr-2" style="color:white; background-color: gray; cursor: no-drop !important" disabled>Github</a>
<!-- [Github](https://github.com/asgaonkar/MAC-Encryption){: .btn .btn-purple } -->


## Connsplit 
{: .top-project .d-inline-block .completed}

Utility
{: .label .label-green .ml-3}

<!-- In-Progress
{: .label .label-yellow .ml-3} -->

```yaml
Oct 2019 - Nov 2019
```

To ease the process of analyzing network traffic, Connsplit helps in segregation meaningful TCP/UDP converstaions into single files.

> [#Security](){: .target-blank} [#Reverse-Engineering](){: .target-blank}


<a href="javascript:void(0)" class="btn mr-2" style="color:white; background-color: gray; cursor: no-drop !important" disabled>Github</a>
<!-- [Github](https://github.com/asgaonkar/MAC-Encryption){: .btn .btn-purple } -->



## Crypto-Certificate Reader
{: .top-project .d-inline-block .completed}

Utility
{: .label .label-green .ml-3}

<!-- In-Progress
{: .label .label-yellow .ml-3} -->

```yaml
Oct 2019 - Nov 2019
```

A python utilty to validate the integrity of a [Crypto-Certificate](){: .target-blank} for example a [SSL Certificate](){: .target-blank}.

> [#Security](){: .target-blank} [#Cryptography](){: .target-blank}

<a href="https://github.com/asgaonkar/Crypto-Certificate-Reader" class="btn btn-purple mr-2" style="color:white">Github</a>
<!-- [Github](https://github.com/asgaonkar/Crypto-Certificate-Reader){: .btn .btn-purple } -->



## Web Exploitation
{: .top-project .d-inline-block .completed}

Offensive Security
{: .label .label-green .ml-3}

<!-- In-Progress
{: .label .label-yellow .ml-3} -->

```yaml
Nov 2019 - Dec 2019
```

Tasked to exploit various websites and extract secret-key using offensive techniquies like [SQL Injection](){: .target-blank}, [XSS (Cross-Site Scripting)](){: .target-blank}

> [#Security](){: .target-blank} [#Web-Security](){: .target-blank} [#Networking](){: .target-blank}

<a href="javascript:void(0)" class="btn mr-2" style="color:white; background-color: gray; cursor: no-drop !important" disabled>Github</a>
<!-- [Github](https://github.com/asgaonkar/MAC-Encryption){: .btn .btn-purple } -->


## MAC-Encryption
{: .top-project .d-inline-block .completed}

Algorithm Engineering
{: .label .label-green .ml-3}

<!-- In-Progress
{: .label .label-yellow .ml-3} -->

```yaml
Sep 2019 - Oct 2019
```

In order to understand the core concepts of [Block Ciphers](){: .target-blank}, we developed our own Encryption and Decryption Algorithm. Performed [Cryptanalysis](){: .target-blank} on our system to find various drawback of our system. Based on these vulnerabilities, we further improved upon our Algorithm.

> [#Security](){: .target-blank} [#Cryptography](){: .target-blank}

<a href="https://github.com/asgaonkar/MAC-Encryption" class="btn btn-purple mr-2" style="color:white">Github</a>
<!-- [Github](https://github.com/asgaonkar/MAC-Encryption){: .btn .btn-purple } -->



<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
  function moveDown()
  {
    document.getElementsByClassName('main-content-wrap')[0].scrollTop = $("#display").position().top;
    console.log($("#display").position().top);
    $(window).scrollTop($("#display").position().top);
  }
  function direction_movement()
  {
    if(document.getElementsByClassName('direction')[0].getAttribute("src").split('-')[1].split('.')[0] == "down")
      {
        moveDown();
      }
      else{
        document.getElementsByClassName('main-content-wrap')[0].scrollTop = 0;
        $(window).scrollTop(0);
      }
  }
  try {
    AOS.init();
    $(window).on('load', function() {
      document.getElementsByClassName('filter')[0].click();
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
      $('a > img').parent().addClass("image-link");
      $('img.logo-link').parent().attr('target','blank');
      document.getElementsByClassName('direction')[0].parentNode.setAttribute('onclick','direction_movement()');
      document.getElementsByClassName('direction')[0].setAttribute('onclick','direction_movement()');
      $('.direction').on('click', function() {
        direction_movement()
        });
      document.addEventListener('click', function (event) {
          if ($(event.target).hasClass('direction'))
          {
            console.log('Clicked');
            direction_movement()
          }
      }, true /*Capture event*/);
      $('.target-blank').attr('target','blank');
      $('pre').addClass("mb-0");
      $('p > a.no-mb').parent().addClass("mb-0");
      $('a > img').parent().addClass("image-link");
      $('img.logo-link').parent().attr('target','blank');
      $('.main-content-wrap').on('scroll', function() {
          console.log("triggered");
          if(document.getElementsByClassName('direction')[0].getAttribute("src").split('-')[1].split('.')[0] == "up")
          {
            document.getElementsByClassName('direction')[0].classList.remove("blinking");
            document.getElementsByClassName('direction')[0].classList.add("no-blinking");
          }
          if ($('.main-content-wrap').scrollTop() >= $("#display").position().top) {
            document.getElementsByClassName('direction')[0].setAttribute("src","../../assets/images/arrow-up.png");
          }
          else
          {
            document.getElementsByClassName('direction')[0].setAttribute("src","../../assets/images/arrow-down.png");
          }
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
    });
    $(window).on('scroll', function() {
      if(document.getElementsByClassName('direction')[0].getAttribute("src").split('-')[1].split('.')[0] == "up")
      {
        document.getElementsByClassName('direction')[0].classList.remove("blinking");
        document.getElementsByClassName('direction')[0].classList.add("no-blinking");
      }
      if ($(window).scrollTop() >= $("#display").position().top) {
        document.getElementsByClassName('direction')[0].setAttribute("src","../../assets/images/arrow-up.png");
      }
      else
      {
        document.getElementsByClassName('direction')[0].setAttribute("src","../../assets/images/arrow-down.png");
      } 
      var $animation_elements = $('.bootstrap-iso');
      var $window = $(window);
      var window_height = $window.height();
      var window_top_position = $window.scrollTop();
      var window_bottom_position = (window_top_position + window_height);
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
    $('.toc-toggle').on('click', function () {
      var toc = document.getElementById('markdown-toc');
      if($(this)[0].innerHTML=="Hide")
      {
        $(this)[0].innerHTML="Show";
        toc.style.display = "none";
      }
      else
      {
        $(this)[0].innerHTML="Hide";
        toc.style.display = "block";
      }
      $('.main-content-wrap')[0].scrollTop += 1;
      $('.main-content-wrap')[0].scrollTop -= 1;
    });
    $('a.filter').on('click', function () {  
      document.getElementsByClassName('direction')[0].classList.remove("no-blinking");
      document.getElementsByClassName('direction')[0].classList.add("blinking");
      var action = $(this)[0];
      for(var i=0;i<$('.filter').length;i++)
      {
        $('.filter')[i].classList.add('btn-blue');
      }
      if($('.toc-toggle')[0].innerHTML=="Hide" && action.innerHTML != "All")
      {
        $('.toc-toggle')[0].click();
      }
      action.classList.remove('btn-blue');
      var class_name; 
      if(action.innerHTML=="Completed")
      {
        class_name = "completed";
      }
      else if(action.innerHTML=="Top Projects")
      {
        class_name = "top-project";
      }      
      else
      {
        class_name = "in-progress";
      }
      for(var i=0;i<$('.tags').length;i++)
      {
        $('.tags')[i].style.display = "none";
      }
      var class_object = document.getElementsByClassName(class_name);
      for(var i=0;i<class_object.length;i++)
      {
        class_object[i].parentNode.parentNode.parentNode.style.display = "block";
      }
      $('.main-content-wrap')[0].scrollTop += 1;
      $('.main-content-wrap')[0].scrollTop -= 1;
    });
}
catch(error) {
  location.reload()
}
</script>