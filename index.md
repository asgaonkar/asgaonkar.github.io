---
layout: default
title: Home
nav_order: 1
description: "Atit Gaonkar | Home"
permalink: /
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
a img
{
  border: 0 none;
}
.image-link
{
  text-decoration: none;
}


</style>

![Direction](../../assets/images/arrow-down.png){: .img-responsive .blinking .direction .down}


<div class="bootstrap-iso">
    <div class="card" style="box-shadow:  0px 0px 15px 5px rgba(0, 0, 0, 0.075) !important; border-radius: 5px;">
        <div class="text-center card-header">
            <h4><span style="font-size: 20px"><strong>Atit Gaonkar</strong></span></h4>
        </div>
        <div class="card-body">
            <div class="row">
                <div class="col-xl-5 col-md-5 mb-3 text-center my-auto">
                    <img src="assets/images/atit-gaonkar.jpg" class="img-fluid z-depth-1 rounded-circle shadow atit-intro" alt="Atit Gaonkar" style="box-shadow: 0 5px 10px 0 rgba(0,0,0,0.16),0 8px 15px 0 rgba(0,0,0,0.12) !important;">
                    <div class='col-12 text-center mt-5'>
                    <a href="mailto:atit.sgaonkar@gmail.com" class="fas fa-envelope fs-6 mb-4 mb-md-0 mr-4" target="_blank"></a>
                    <a href="https://www.linkedin.com/in/atit-gaonkar/" class="fab fa-linkedin fs-6 mb-4 mb-md-0 mr-4 " target="_blank" style=""></a>
                    <a href="https://github.com/asgaonkar" class="fab fa-github fs-6 mb-4 mb-md-0 mr-4" target="_blank"></a>
                    <a href="https://www.instagram.com/atit.sgaonkar/" class="fab fa-instagram fs-6 mb-4 mb-md-0" target="_blank"></a>
                    </div>
                    <!-- <img src="assets/images/logo.png" class="img-fluid z-depth-1" width="10%" alt="Atit-Gaonkar"> -->
                </div>
                <div class="col-xl-7 col-md-7 mb-3">        
                    <!-- <h5 class="card-title">Special title treatment</h5> -->
                    <!-- <p class="card-text">With supporting text below as a natural lead-in to additional content.</p> -->
                    <p class="card-text"><a href="education">Computer Science Graduate student</a> at Arizona State University with focus on <a href="certification">Cyber-Security</a>. I passionate about Binary Analysis, Web security and Data Visualization. I am currently <a href="research">researching</a> on "The need for dynamic security Implementations". I have <a href="work_experience">worked</a> on System Security, Reverse Engineering Binaries, Web Security.</p>
                    <p class="card-text">Along with interest in Cyber-Security, I also involve myself in <a href="research">Mathematics</a>, specifically Number Theory. I am investigating on ways to identify unique patterns and sequences in the process of exponentiation.</p>
                    <p class="card-text">I keep myself productive working on personal <a href="education">projects</a>. My <a href="what-else">hobbies</a> include travelling, logo designing, photo manipulation and <a href="volunteering">volunteering</a></p>
                    <a href="#" class="btn btn-blue mb-2 mr-2 mt-0 resume" target="blank" style="color:white; background-color: gray" title="View Resume">Resume (Online)</a>
                    <a href="#" class="btn btn-blue mb-2 mr-2 mt-0 resume" target="blank" style="color:white; background-color: gray" title="Download Resume">Resume (PDF)</a>
                </div>
            </div>
        </div>
    </div>
</div>

<script src="https://kit.fontawesome.com/a773360a89.js" crossorigin="anonymous"></script>

<!-- You will often find me <span id="typewriter"></span>
{: .fs-5} -->


<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
    $(window).on('load', function() {
        $('.main-content-wrap').on('scroll', function() {
          if(document.getElementsByClassName('direction')[0].getAttribute("src").split('-')[1].split('.')[0] == "up")
          {
            document.getElementsByClassName('direction')[0].classList.remove("blinking");
            document.getElementsByClassName('direction')[0].classList.add("no-blinking");
          }
          if ($('.main-content-wrap').scrollTop() >= 100.0) {
            document.getElementsByClassName('direction')[0].setAttribute("src","../../assets/images/arrow-up.png");
          }
          else
          {
            document.getElementsByClassName('direction')[0].setAttribute("src","../../assets/images/arrow-down.png");
          }
          console.log("Scrolled");
      });
    });
</script>
