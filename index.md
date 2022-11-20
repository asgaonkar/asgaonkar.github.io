---
layout: default
title: Home
nav_order: 1
description: "Security Researcher and Computer Science Graduate student at Arizona State University. A passionate Coder, Web developer, Cybersecurity Enthusiast and gamer."
type: website
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
.notification {
  animation: blinkingText 0.5s infinite;
  cursor: pointer;
}
@keyframes notification {
  0% {
    opacity: 0.50;
  }  
  50% {
    opacity: 1;
  }  
  100% {
    opacity: 0.50;
  }
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

.last-item{
  -webkit-mask-image: -webkit-gradient(linear, left top, left bottom, from(rgba(0,0,0,0.75)), to(rgba(0,0,0,0))) !important;
}

.label-items {
  display: flex;
  justify-content: space-between;
  margin-bottom: 0px;
  span {
    color: #666;
  }
}
.progress {
  height: 8px !important;
  margin-bottom: 15px;
}
.progress-bar-ad {
/* background: -webkit-linear-gradient(left, #f2d082 25%, #64f272 75%) !important; */
}
.progress-bar-in {
/* background: -webkit-linear-gradient(left, #f2d082 25%, #f29696 75%) !important; */
}
.progress-bar-be {
/* background: -webkit-linear-gradient(left, #f2d082 25%, #f2c8c8 75%) !important; */
}
</style>

<!-- ![Direction](../../assets/images/arrow-down.png){: .img-responsive .blinking .direction .down} -->


<div class="bootstrap-iso">  
  <!-- <div class="card mb-5" style="box-shadow:  0px 0px 15px 5px rgba(0, 0, 0, 0.075) !important; border-radius: 5px;"> -->
      <div class="card mb-3" style="box-shadow:  0px 0px 0px 0px rgba(0, 0, 0, 0.0) !important; border-radius: 0px; border: 0px; background-color:transparent !important;">
      <!-- <div class="text-center card-header">
          <h4><span style="font-size: 20px"><strong>Atit Gaonkar</strong></span></h4>
      </div> -->
      <div class="card-body">
          <div class="row">            
              <div class="col-xl-5 col-md-5 mb-0 text-center my-auto">
                  <!-- <img alt='Logo - Atit Gaonkar' src="/assets/images/logo.svg" width="100px"> -->
                  <img src="assets/images/atit-gaonkar.jpg" class="img-fluid z-depth-1 rounded-circle shadow atit-intro" alt="Atit Gaonkar" style="box-shadow: 0 5px 10px 0 rgba(0,0,0,0.16),0 8px 15px 0 rgba(0,0,0,0.12) !important;">
                  <div class='col-12 text-center mt-5'>
                  <a href="mailto:atit.sgaonkar@gmail.com" class="fas fa-envelope fs-6 mb-4 mb-md-0 mr-4" target="_blank" alt="Email"></a>
                  <a href="https://www.linkedin.com/in/atit-gaonkar/" class="fab fa-linkedin fs-6 mb-4 mb-md-0 mr-4 " target="_blank" style="" alt="LinkedIn"></a>
                  <a href="https://github.com/asgaonkar" class="fab fa-github fs-6 mb-4 mb-md-0 mr-4" target="_blank" alt="Github"></a>
                  <a href="https://www.instagram.com/atit.sgaonkar/" class="fab fa-instagram fs-6 mb-4 mb-md-0" target="_blank" alt="Instagram"></a>                  
                  </div>
                  <!-- <img src="assets/images/logo.png" class="img-fluid z-depth-1" width="10%" alt="Atit-Gaonkar"> -->
              </div>
              <div class="col-xl-7 col-md-7 mb-0">                  
                  <!-- <h5 class="card-title">Special title treatment</h5> -->
                  <!-- <p class="card-text">With supporting text below as a natural lead-in to additional content.</p> -->
                  <p class="card-text mt-2"><a href="work_experience">Software Engineer</a> at <a href="https://www.bloomreach.com/" target="_blank">Bloomreach</a> working towards enhancing Real time Intelligence platform to provide better user experience and customization. Responsible for building/automating backend systems and tools to support company-wide infrastructure to deliver high-level optimization solutions. Improved end-to-end replication speed by 90% (600 seconds to 60 seconds), built features to scale backend infrastructure, and built orchestration APIs to support development and operations. Used open-source software such as Prometheus, Docker, and Kubernetes to build a stable and robust monitoring system.</p>
                  <p class="card-text mt-2"><a href="education">Computer Science Graduate </a> from Arizona State University with focus on <a href="work_experience">Software Engineering</a> and <a href="certification">Cyber-Security</a>. Passionate about Blockchain, Binary Analysis, Web security, Algorithm Design and Data Visualization. Worked as an IoT-Blockchain Researcher at <a href="https://blockchain.asu.edu/" target='blank'>Blockchain Research Lab</a>, <a href="research">researching</a> on "Cybersecurity Considerations for Blockchain Systems". I have <a href="work_experience">work experience</a> in Blockchain, Data Engineering, System Security, Reverse Engineering Binaries and Web Security.</p>
                  <p class="card-text">My interest in <a href="research">Mathematics</a> lies in the field of Number Theory. Investigated on ways to identify unique patterns and sequences in the process of exponentiation. I keep myself productive working on personal <a href="projects">projects</a>. My hobbies include travelling, logo designing, photo manipulation and <a href="volunteering">volunteering</a></p>
                  <!-- <a href="resume" class="btn mb-2 mr-2 mt-0 resume" target="blank" style="color:white; background-color: gray !important; cursor: no-drop" title="View Resume">Resume (Online)</a> -->                  
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
        $(window).scrollTop(0);              
        $('.main-content-wrap').scrollTop(0);
        for (var i =0; i<$('.progress').length; i++)
        {
          $('.progress')[i].children[0].classList.add('bg-success');
        }
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
      $('.load-more').on('click', function() {
        if ($(this)[0].innerHTML[0]=='M'){
          for(var i=0;i<$('.load-more').length;i++){
          $('.load-more')[i].parentNode.parentNode.getElementsByClassName('last-item-handle')[0].classList.add("last-item");
          $('.load-more')[i].parentNode.parentNode.getElementsByClassName('hides')[0].style.display='none';
          $('.load-more')[i].innerHTML = 'More<i class="fas fa-angle-down fs-7 ml-2" style="vertical-align: middle;" aria-hidden="true"></i>';
          $('.load-more')[i].classList.remove('btn-green');
          $('.load-more')[i].classList.add('btn-blue');
        };
        }
        if ($(this)[0].innerHTML[0]=='M')
        {
          $(this)[0].parentNode.parentNode.getElementsByClassName('last-item-handle')[0].classList.remove("last-item");
          $(this)[0].parentNode.parentNode.getElementsByClassName('hides')[0].style.display='block';
          $(this)[0].innerHTML = 'Less<i class="fas fa-angle-up fs-7 ml-2" style="vertical-align: middle;" aria-hidden="true"></i>';
          $(this)[0].classList.add('btn-green');
          $(this)[0].classList.remove('btn-blue');
        }
        else
        {
          $(this)[0].parentNode.parentNode.getElementsByClassName('last-item-handle')[0].classList.add("last-item");
          $(this)[0].parentNode.parentNode.getElementsByClassName('hides')[0].style.display='none';
          $(this)[0].innerHTML = 'More<i class="fas fa-angle-down fs-7 ml-2" style="vertical-align: middle;" aria-hidden="true"></i>';
          $(this)[0].classList.remove('btn-green');
          $(this)[0].classList.add('btn-blue');
        }
      })      
    });
    function greenDotNotification()
    {
      document.getElementsByClassName('dotNotification')[0].style.color = 'green';
      document.getElementsByClassName('blinkingNotification')[0].style.color = 'green';
    }
    function redDotNotification()
    {
      document.getElementsByClassName('dotNotification')[0].style.color = 'red';
      document.getElementsByClassName('blinkingNotification')[0].style.color = 'red';
    }
    function redirectResume()
    {
      var link = document.createElement('a');
      link.href = 'Atit Gaonkar (Resume).pdf';
      link.setAttribute("target", "_blank");
      link.click();
    }
</script>
