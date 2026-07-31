---
layout: default_card_modal
title: What Else
nav_order: 98
permalink: what-else/
description: "Atit Gaonkar | What Else"
nav_exclude: true
---

<style>

/* [1] The container */
.img-hover-zoom {
  /* height: 300px; [1.1] Set it as per your need */
  overflow: hidden; /* [1.2] Hide the overflowing of child elements */
}

/* [2] Transition property for smooth transformation of images */
.img-hover-zoom a img {
  transition: transform .5s ease;
}

/* [3] Finally, transforming the image when container gets hovered */
.img-hover-zoom:hover a img {
  transform: scale(0.9);
  box-shadow:  0px 0px 10px 10px rgba(0, 0, 0, 0.075) !important;
}

</style>

# What Else
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Photo Maniupluation

A good photo manipulation technique invovles but not limited to taking care of color-blending, lights and shadow, along with a perspective to put the result into.

<div class="bootstrap-iso">
    <div class="row text-center text-lg-left">
        <div class="col-lg-4 col-md-4 col-sm-12 img-hover-zoom">
        <a href="javascript:void(0)" class="d-block mb-4 h-100 image-href">
                <img class="img-fluid img-thumbnail" src="../assets/images/what_else/manipulation/birds.jpg" alt="">            
            </a>
        </div>
        <div class="col-lg-4 col-md-4 col-sm-12 img-hover-zoom">
        <a href="javascript:void(0)" class="d-block mb-4 h-100 image-href">
                <img class="img-fluid img-thumbnail" src="../assets/images/what_else/manipulation/butterfly.jpg" alt="">
            </a>
        </div>
        <div class="col-lg-4 col-md-4 col-sm-12 img-hover-zoom">
        <a href="javascript:void(0)" class="d-block mb-4 h-100 image-href">
                <img class="img-fluid img-thumbnail" src="../assets/images/what_else/manipulation/dolphin.jpg" alt="">
            </a>
        </div>
    </div>
</div>

## Logo Designing

Logo designing brings about creativity and imagination to identify the values, cultre and the behaviour of a product and convey the same using either graphical representation, textual representation or both.

<div class="bootstrap-iso">
    <div class="row text-center text-lg-left">
        <div class="col-lg-4 col-md-4 col-sm-12 img-hover-zoom">
        <a href="javascript:void(0)" class="d-block mb-4 h-100 image-href">
                <img class="img-fluid img-thumbnail" src="../assets/images/what_else/designing/invisible.jpg" alt="">
            </a>
        </div>
        <div class="col-lg-4 col-md-4 col-sm-12 img-hover-zoom">
        <a href="javascript:void(0)" class="d-block mb-4 h-100 image-href">
                <img class="img-fluid img-thumbnail" src="../assets/images/what_else/designing/motion.jpg" alt="">
            </a>
        </div>
        <div class="col-lg-4 col-md-4 col-sm-12 img-hover-zoom">
        <a href="javascript:void(0)" class="d-block mb-4 h-100 image-href">
                <img class="img-fluid img-thumbnail" src="../assets/images/what_else/designing/record.jpg" alt="">
            </a>
        </div>
    </div>
</div>

<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
<script>
  $(window).on('load', function() {
        $(window).scrollTop(0);
        $('.main-content-wrap').scrollTop(0);
        $('.target-blank').attr('target','blank');
        $('pre').addClass("mb-0");
        $('p > a.no-mb').parent().addClass("mb-0");
        $('a > img').parent().addClass("image-link");
        $('img.logo-link').parent().attr('target','blank');
        $('.main-content-wrap')[0].scrollTop += 1;
        $('.main-content-wrap')[0].scrollTop -= 1;
    });
    $('a.image-href').on('click', function() {
        console.log($(this)[0],document.getElementsByClassName('modal-button')[0].click());
        var source = $(this)[0].getElementsByTagName('img')[0].getAttribute('src');
        document.getElementsByClassName('current-image')[0].setAttribute('src',source);
    });
</script>