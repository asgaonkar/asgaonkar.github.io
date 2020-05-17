---
layout: default
title: Home
nav_order: 1
description: "Atit Gaonkar - Computer Science (Cyber-Security) Graduate student at Arizona State University. A passionate Coder, Web developer and gamer."
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
.progress-bar {
background: -webkit-linear-gradient(left, #f2d082 25%, #f28282 75%) !important; /* Chrome10-25,Safari5.1-6 */
}

</style>

![Direction](../../assets/images/arrow-down.png){: .img-responsive .blinking .direction .down}


<div class="bootstrap-iso">
  <div class="card mb-5" style="box-shadow:  0px 0px 15px 5px rgba(0, 0, 0, 0.075) !important; border-radius: 5px;">
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
                  <p class="card-text">I keep myself productive working on personal <a href="education">projects</a>. My hobbies include travelling, logo designing, photo manipulation and <a href="volunteering">volunteering</a></p>
                  <a href="#" class="btn btn-blue mb-2 mr-2 mt-0 resume" target="blank" style="color:white; background-color: gray" title="View Resume">Resume (Online)</a>
                  <a href="#" class="btn btn-blue mb-2 mr-2 mt-0 resume" target="blank" style="color:white; background-color: gray" title="Download Resume">Resume (PDF)</a>
              </div>
          </div>
      </div>
  </div>
  <div class="card mb-5" style="box-shadow:  0px 0px 15px 5px rgba(0, 0, 0, 0.075) !important; border-radius: 5px;">
      <div class="card-body">
        <div class='row text-center mb-4'>
          <h4 class="no_toc mb-2 text-center" id="skillset" style='width:100%;'><span style="font-size: 20px"><strong>SKILL SET</strong></span></h4>
        </div>        
        <div class='row ml-1 mr-1'>
          <div class='card col-lg-12 col-md-12 sol-sm-12 mb-3 ml-1' style='padding: 0px'>            
            <!-- Card -->            
              <div class="card-header">
                <div class='row' style='width:100%; margin: 0px'>
                  <p><h4 class='mb-0'><i class="fas fa-laptop-code fs-7 ml-2" style='vertical-align: middle; color: #10ac7d'></i><strong style='vertical-align: middle; vertical-align: middle;' class='ml-2'>Web Developement</strong></h4></p>
                </div>
              </div>
              <!-- Card content -->
              <div class="card-body">      
                <div class='advanced'>    
                  <div class="label-items">
                    <span>Advance Skills</span>
                    <span>90%</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 90%;">
                    </div>
                  </div>
                  <div class='advanced-skills ml-4'>                  
                    <!-- Title -->
                    <h4 class="card-title mb-0">Languages</h4>
                    <!-- Text -->                
                    <p class="card-text mb-4"><a style="color: #007bff">HTML</a>, CSS, JS, PHP, SQL, Python</p>
                    <!-- Title -->
                    <h4 class="card-title mb-0">Framework</h4>
                    <!-- Text -->
                    <p class="card-text mb-4">Flask, Jekyll, Bootstrap</p>
                  </div>                    
                </div>
                <div class='intermediate mt-2 last-item-handle last-item'>    
                  <div class="label-items">
                    <span>Intermediate Skills</span>
                    <span>70%</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 70%;">
                    </div>
                  </div>
                  <div class='intermediate-skills ml-4'>                                      
                    <!-- Title -->
                    <h4 class="card-title mb-0">CMS</h4>
                    <!-- Text -->
                    <p class="card-text mb-4">Drupal</p>
                  </div>                    
                </div>
                <div class='beginner mt-2 hides' style='display: none'>    
                  <div class="label-items">
                    <span>Beginner Skills</span>
                    <span>30%</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 30%;">
                    </div>
                  </div>
                  <div class='beginner-skills ml-4'>                                      
                    <!-- Title -->
                    <h4 class="card-title mb-0">Frameworks</h4>
                    <!-- Text -->
                    <p class="card-text mb-4">Django, Angular, React</p>
                  </div>                    
                </div>
              </div>
              <div class='card-footer mb-0 text-center'>
              <a href="javascript:void(0);" class="btn btn-blue mb-0 mt-0 load-more" style="color:white; background-color: gray" title="Show More">Show More<i class="fas fa-angle-down fs-7 ml-2" style='vertical-align: middle;'></i></a>
            </div>            
            <!-- Card -->            
          </div>          
          <div class='card col-lg-12 col-md-12 sol-sm-12 mb-3 ml-1' style='padding: 0px'>            
            <!-- Card -->            
              <div class="card-header">
                <div class='row' style='width:100%; margin: 0px'>
                  <p><h4 class='mb-0'><i class="fas fa-fingerprint fs-7 ml-2" style='vertical-align: middle; color: #10ac7d'></i><strong style='vertical-align: middle; vertical-align: middle;' class='ml-2'>Cyber Security</strong></h4></p>
                </div>
              </div>
              <!-- Card content -->
              <div class="card-body">      
                <div class='advanced'>
                  <div class="label-items">
                    <span>Advanced Skills</span>
                    <span>90%</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 90%;">
                    </div>
                  </div>
                  <div class='advanced-skills ml-4'>                                      
                    <!-- Title -->
                    <h4 class="card-title mb-0">Binary Analysis</h4>
                    <!-- Text -->
                    <p class="card-text mb-4">Buffer Overflow, Shellcodes, Format Strings</p>
                    <!-- Title -->
                    <h4 class="card-title mb-0">Web Exploitation</h4>
                    <!-- Text -->
                    <p class="card-text mb-4">XSS and SQL Injection</p>
                  </div>                    
                </div>
                <div class='intermediate mt-2 last-item-handle last-item'>    
                  <div class="label-items">
                    <span>Intermediate Skills</span>
                    <span>70%</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 70%;">
                    </div>
                  </div>
                  <div class='intermediate-skills ml-4'>                                      
                    <!-- Title -->
                    <h4 class="card-title mb-0">Binary Analysis</h4>
                    <!-- Text -->
                    <p class="card-text mb-4">Heap Exploitation, Reverse Engineering</p>
                    <!-- Title -->
                    <h4 class="card-title mb-0">Forensics</h4>
                    <!-- Text -->
                    <p class="card-text mb-4">Phishing Kit Analysis, Network Traffic Analysis</p>
                  </div>                    
                </div>
                <div class='beginner mt-2 hides' style='display: none'>    
                  <div class="label-items">
                    <span>Beginner Skills</span>
                    <span>30%</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 30%;">
                    </div>
                  </div>
                  <div class='beginner-skills ml-4'>                                      
                    <!-- Title -->
                    <h4 class="card-title mb-0">Web Exploitation</h4>
                    <!-- Text -->
                    <p class="card-text mb-4">CSRF</p>
                  </div>                    
                </div>
              </div>
              <div class='card-footer mb-0 text-center'>
              <a href="javascript:void(0);" class="btn btn-blue mb-0 mt-0 load-more" style="color:white; background-color: gray" title="Show More">Show More<i class="fas fa-angle-down fs-7 ml-2" style='vertical-align: middle;'></i></a>
            </div>            
            <!-- Card -->            
          </div>
          <div class='card col-lg-12 col-md-12 sol-sm-12 mb-3 ml-1' style='padding: 0px'>            
            <!-- Card -->            
              <div class="card-header">
                <div class='row' style='width:100%; margin: 0px'>
                  <p><h4 class='mb-0'><i class="fas fa-chart-line fs-7 ml-2" style='vertical-align: middle; color: #10ac7d'></i><strong style='vertical-align: middle; vertical-align: middle;' class='ml-2'>Data Visualization</strong></h4></p>
                </div>
              </div>
              <!-- Card content -->
              <div class="card-body">      
                <div class='advanced'>
                  <div class="label-items">
                    <span>Advanced Skills</span>
                    <span>90%</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 90%;">
                    </div>
                  </div>
                  <div class='advanced-skills ml-4'>                                      
                    <!-- Title -->
                    <h4 class="card-title mb-0">Visualization Techniques</h4>
                    <!-- Text -->
                    <p class="card-text mb-4">Interactive Visualization</p>
                    <!-- Title -->
                    <h4 class="card-title mb-0">Designing</h4>
                    <!-- Text -->
                    <p class="card-text mb-4">Adobe Suite (Illustrator, Photoshop)</p>
                  </div>                    
                </div>
                <div class='intermediate mt-2 last-item-handle last-item'>    
                  <div class="label-items">
                    <span>Intermediate Skills</span>
                    <span>70%</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 70%;">
                    </div>
                  </div>
                  <div class='intermediate-skills ml-4'>                                      
                    <!-- Title -->
                    <h4 class="card-title mb-0">Languages and Library</h4>
                    <!-- Text -->
                    <p class="card-text mb-4">D3.js, R</p>
                    <!-- Title -->
                    <h4 class="card-title mb-0">Softwares</h4>
                    <!-- Text -->
                    <p class="card-text mb-4">Tableau, PowerBI, TIBCO Spotfire</p>
                  </div>                    
                </div>
                <div class='beginner mt-2 hides' style='display: none'>    
                  <div class="label-items">
                    <span>Beginner Skills</span>
                    <span>30%</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 30%;">
                    </div>
                  </div>
                  <div class='beginner-skills ml-4'>                                      
                    <!-- Title -->
                    <h4 class="card-title mb-0">Techniques</h4>
                    <!-- Text -->
                    <p class="card-text mb-4">Network Visualization</p>
                  </div>                    
                </div>
              </div>
              <div class='card-footer mb-0 text-center'>
              <a href="javascript:void(0);" class="btn btn-blue mb-0 mt-0 load-more" style="color:white; background-color: gray" title="Show More">Show More<i class="fas fa-angle-down fs-7 ml-2" style='vertical-align: middle;'></i></a>
            </div>            
            <!-- Card -->            
          </div>
          <div class='card col-lg-12 col-md-12 sol-sm-12 mb-3 ml-1' style='padding: 0px'>            
            <!-- Card -->            
              <div class="card-header">
                <div class='row' style='width:100%; margin: 0px'>
                  <p><h4 class='mb-0'><i class="fas fa-code fs-7 ml-2" style='vertical-align: middle; color: #10ac7d'></i><strong style='vertical-align: middle; vertical-align: middle;' class='ml-2'>Computer Programming</strong></h4></p>
                </div>
              </div>
              <!-- Card content -->
              <div class="card-body">      
                <div class='advanced'>
                  <div class="label-items">
                    <span>Advanced Skills</span>
                    <span>90%</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 90%;">
                    </div>
                  </div>
                  <div class='advanced-skills ml-4'>                                      
                    <!-- Title -->
                    <h4 class="card-title mb-0">Languages</h4>
                    <!-- Text -->
                    <p class="card-text mb-4">Python</p>                                 
                  </div>                    
                </div>
                <div class='intermediate mt-2 last-item-handle last-item'>    
                  <div class="label-items">
                    <span>Intermediate Skills</span>
                    <span>70%</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 70%;">
                    </div>
                  </div>
                  <div class='intermediate-skills ml-4'>                                      
                    <!-- Title -->
                    <h4 class="card-title mb-0">Languages</h4>
                    <!-- Text -->
                    <p class="card-text mb-4">C++, JS, C</p>                    
                  </div>                    
                </div>
                <div class='beginner mt-2 hides' style='display: none'>    
                  <div class="label-items">
                    <span>Beginner Skills</span>
                    <span>30%</span>
                  </div>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 30%;">
                    </div>
                  </div>
                  <div class='beginner-skills ml-4'>                                      
                    <!-- Title -->
                    <h4 class="card-title mb-0">Languages</h4>
                    <!-- Text -->
                    <p class="card-text mb-4">Go, Prolog</p>
                  </div>                    
                </div>
              </div>
              <div class='card-footer mb-0 text-center'>
              <a href="javascript:void(0);" class="btn btn-blue mb-0 mt-0 load-more" style="color:white; background-color: gray" title="Show More">Show More<i class="fas fa-angle-down fs-7 ml-2" style='vertical-align: middle;'></i></a>
            </div>            
            <!-- Card -->            
          </div>
        </div>
      </div>
      <!-- <div class="card-footer text-center">
      </div> -->
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
        if ($(this)[0].innerHTML[5]=='M'){
          for(var i=0;i<$('.load-more').length;i++){
          $('.load-more')[i].parentNode.parentNode.getElementsByClassName('last-item-handle')[0].classList.add("last-item");
          $('.load-more')[i].parentNode.parentNode.getElementsByClassName('hides')[0].style.display='none';
          $('.load-more')[i].innerHTML = 'Show More<i class="fas fa-angle-down fs-7 ml-2" style="vertical-align: middle;" aria-hidden="true"></i>';
          $('.load-more')[i].classList.remove('btn-green');
          $('.load-more')[i].classList.add('btn-blue');
        };
        }
        if ($(this)[0].innerHTML[5]=='M')
        {
          $(this)[0].parentNode.parentNode.getElementsByClassName('last-item-handle')[0].classList.remove("last-item");
          $(this)[0].parentNode.parentNode.getElementsByClassName('hides')[0].style.display='block';
          $(this)[0].innerHTML = 'Show Less<i class="fas fa-angle-up fs-7 ml-2" style="vertical-align: middle;" aria-hidden="true"></i>';
          $(this)[0].classList.add('btn-green');
          $(this)[0].classList.remove('btn-blue');
        }
        else
        {
          $(this)[0].parentNode.parentNode.getElementsByClassName('last-item-handle')[0].classList.add("last-item");
          $(this)[0].parentNode.parentNode.getElementsByClassName('hides')[0].style.display='none';
          $(this)[0].innerHTML = 'Show More<i class="fas fa-angle-down fs-7 ml-2" style="vertical-align: middle;" aria-hidden="true"></i>';
          $(this)[0].classList.remove('btn-green');
          $(this)[0].classList.add('btn-blue');
        }
      })
    });
</script>
