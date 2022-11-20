---
layout: default
title: Contact
nav_order: 100
permalink: /contact/
description: "Atit Gaonkar - Connect with me through eMail, LinkedIn, Github or Instagram"
---

<div class="bootstrap-iso">
    <div class="card" style="box-shadow:  0px 0px 15px 5px rgba(0, 0, 0, 0.075) !important; border-radius: 5px;">
        <div class="card-header text-center">
            <img src="../assets/images/logo.svg" class="img-fluid z-depth-1 logo" alt="Logo - Atit Gaonkar" height='75px' width='75px'>
        </div>
        <div class="card-body">
            <div class="row">                
                <div class="col-xl-5 col-md-5 mb-3 text-center my-auto">
                  <!-- <img alt='Logo - Atit Gaonkar' src="/assets/images/logo.svg" width="100px"> -->
                  <img src="/assets/images/atit-gaonkar-profile.jpg" class="img-fluid z-depth-1 rounded-circle shadow atit-intro" alt="Atit Gaonkar" style="box-shadow: 0 5px 10px 0 rgba(0,0,0,0.16),0 8px 15px 0 rgba(0,0,0,0.12) !important;">
                  <div class='col-12 text-center mt-5'>
                  <a href="mailto:atit.sgaonkar@gmail.com" class="fas fa-envelope fs-6 mb-4 mb-md-0 mr-4" target="_blank" alt="Email"></a>
                  <a href="https://www.linkedin.com/in/atit-gaonkar/" class="fab fa-linkedin fs-6 mb-4 mb-md-0 mr-4 " target="_blank" style="" alt="LinkedIn"></a>
                  <a href="https://github.com/asgaonkar" class="fab fa-github fs-6 mb-4 mb-md-0 mr-4" target="_blank" alt="Github"></a>
                  <a href="https://www.instagram.com/atit.sgaonkar/" class="fab fa-instagram fs-6 mb-4 mb-md-0" target="_blank" alt="Instagram"></a>                  
                  </div>
                  <!-- <img src="assets/images/logo.png" class="img-fluid z-depth-1" width="10%" alt="Atit-Gaonkar"> -->
                </div>
                <div class="col-xl-6 col-lg-6 col-md-6 col-sm-6 mt-8 my-auto" style="padding-bottom: 20px">
                    <!-- <img src="../assets/images/atit-gaonkar.jpg" class="ml-5 img-fluid z-depth-1 rounded-circle shadow atit-intro" alt="Atit Gaonkar" style="box-shadow: 0 5px 10px 0 rgba(0,0,0,0.16),0 8px 15px 0 rgba(0,0,0,0.12) !important;" width='75%'> -->
                    <div class='row map mb-0 ml-2 mr-2 mt-2 mb-2'>      
                        <iframe style='display: block; box-shadow:  0px 0px 15px 10px rgba(0, 0, 0, 0.075) !important;' src="https://maps.google.com/maps?q=Tempe+85281&t=&z=11&ie=UTF8&iwloc=&output=embed" frameborder="0" width='100%' height='300px' allowfullscreen></iframe>
                    </div>
                </div>
            </div>
        </div>
        <div class="card-footer text-center" style='display: none'>
            <a href="javascript:void(0)" onclick='show_location()' class="btn btn-blue mb-2 mr-2 mt-0 location" style="color:white;" title="View Location">Hide Location</a>
        </div>
    </div>
</div>

<script src="https://kit.fontawesome.com/a773360a89.js" crossorigin="anonymous"></script>
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
<script>
    function show_location()
    {
        var current = document.getElementsByClassName('location')[0].innerHTML;
        if (current=='Show Location')
        {
            document.getElementsByClassName('map')[0].style.display = "block";
            document.getElementsByClassName('location')[0].innerHTML = "Hide Location";
        }
        else
        {
            document.getElementsByClassName('map')[0].style.display = "none";
            document.getElementsByClassName('location')[0].innerHTML = "Show Location";
        }
    }
    $(window).on('load', function() {
        $(window).scrollTop(0);
        $('.main-content-wrap').scrollTop(0);
    });
</script>