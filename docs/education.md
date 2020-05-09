---
layout: default_card
title: Education
nav_order: 2
permalink: /education/
description: "Atit Gaonkar | Education"
---

# Education
{: .no_toc }


"Mastering the ability to learn is the best thing you could ever learn" - Atit Gaonkar
{: .fs-4 .fw-100}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---


## Arizona State University
{: .d-inline-block }

Current
{: .label .label-green }

**2019 - 2021**
{: .label .label-yellow }

Master of Science in Computer Science
{:. mb-1}
GPA: 3.56/4.00

<div class="bootstrap-iso">
    <div class="row">
        <div class="col-4">A</div>
        <div class="col-4">A</div>
        <div class="col-4">A</div>
    </div>
</div>

### Interest

Computer Science: **Binary Analysis, Web security** and **Data Visualization**
<br>
Mathematics: **Number Theory**

### Courses

<div class="code-example" markdown="1">
1. Course 1
1. Course 2
1. Course 3
</div>
{% highlight markdown %}
Fall 2020
{% endhighlight %}
<br/>
<div class="code-example" markdown="1">
1. Computer and Network Forensics
1. Data Visualization
1. Statistical Machine Learning
</div>
{% highlight markdown %}
Spring 2020
{% endhighlight %}  
<br/>
<div class="code-example" markdown="1">
1. Software Security
1. Applied Cryptography
1. Foundation of Algorithm
</div>
{% highlight markdown %}
Fall 2019
{% endhighlight %}


### Projects

Projects undertook for successful completion of courses at Arizona State University

[Projects](/projects/academics/@ASU){: .btn .btn-blue }

### Co-Curricular Activities
```yaml
Co-Cirricular
```

---

## Vellore Institute of Technology
{: .d-inline-block }

2014 - 2018
{: .label .label-yellow }

![Vellore Institute of Technology](../../assets/images/vit.png){: .img-responsive .logo height="10%" width="10%"}

Bachelor of Technology in Computer Science and Engineering - CGPA: 8.98/10.0
```yaml
Overall Experience during Bachelors
Favourite Courses
Extra Curricular
```

<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" crossorigin="anonymous"></script>
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
  AOS.init();
  $(window).on('load', function() {
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