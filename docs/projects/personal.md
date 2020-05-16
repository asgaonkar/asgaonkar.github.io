---
layout: default_card
title: Personal
nav_order: 3
parent: Projects
permalink: /projects/personal
description: "Atit Gaonkar | Personal Projects"
---

<link rel="stylesheet" href="..\..\assets\css\bootstrap-iso.css" crossorigin="anonymous">
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
}
.down:hover {
  animation: none;
  opacity: 0.75;
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
.non-blinking {
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
.horizontal-rule{
    border-top: 1px solid #DDD;
}
</style>

![Direction](../../assets/images/arrow-down.png){: .img-responsive .blinking .direction .down}

# Personal Projects
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

## Secure Audit Logs
{: .top-project .d-inline-block .in-progress}

Logging System
{: .label .label-green .ml-3}

In-Progress
{: .label .label-yellow .ml-3}

```yaml
May 2020 - Present
```

Implementing and maintaining a ﬁle of **Secure** [Audit Log](https://en.wikipedia.org/wiki/Audit_trail){: .target-blank} system through computationally cheap methods. So in the event of log compromise, it should be impossible for the attacker to read and modify without being detectable.

> [#Security](){: .target-blank} [#Forensics](){: .target-blank}

<!-- <a href="javascript:void(0)" class="btn mr-2" style="color:white; background-color: gray; cursor: no-drop !important" disabled>Github</a> -->




## Classifile
{: .d-inline-block .top-project .completed }

Automation
{: .label .label-green }

Automating the process of [File Segregation](){: .target-blank} in a file system based on user defined categories. Folders such as Downloads, Desktop and Documents easily become mixed-up and all over the place. Classifile provides ability to systematically organize such Folders.

> [#Automation](){: .target-blank} [#Python-WatchDog](){: .target-blank}

<a href="https://github.com/asgaonkar/Classifile" class="btn btn-purple mr-2" style="color:white">Github</a>
<!-- [Github](https://github.com/asgaonkar/Classifile){: .btn .btn-purple .mr-2} -->
<!-- [Demo](){: .btn .btn-green .disabled} -->



## Multi-fi
{: .d-inline-block .top-project .completed }

Network Utility
{: .label .label-green }

A network utility that enables a Windows wifi recipient to also act as a wifi hotspot for other devices. **Wifi and Hotspot** at the same time.

> [#Networks](){: .target-blank} [#Scripting](){: .target-blank}

<a href="#" class="btn btn-purple mr-2" style="color:white">Github</a>
<!-- [Github](https://github.com/asgaonkar/Scrap-on-Campus){: .btn .btn-purple } -->


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
          $(event.target).hasClass('direction');
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