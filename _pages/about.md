---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- ---
layout: home            # keep the home layout
title: "Prathamesh Kulkarni"
permalink: /
--- -->

<!-- ===== HERO / NAME ===== -->
<!-- <div class="text-center my-4">
  <h1 style="font-size:3rem; font-weight:700;">Prathamesh Kulkarni</h1>
  <p style="font-size:1.25rem;">Computational Soft-Matter • PhD @ Rice University</p>
</div> -->

<!-- ===== ABOUT ===== -->
<div class="row align-items-center my-5">
  <div class="col-md-7">
    <h2>About&nbsp;Me</h2>
    <p>
    In my research, I build computational models to understand how biological soft matter such as crosslinked biopolymer networks behave and fail under mechanical deformation. In my doctoral work under Prof. Fred MacKintosh and Prof. Anatoly Kolomeisky, I have worked on understanding lattice-based and off-lattice fiber networks (e.g. collagen,
actin/vimentin) that explore mechanical phase transitions (criticality), phenomena like strain-stiffening, spring-like stretching/bending, stress relaxation, and crosstalk between components of composite networks. 
     </p>
     <p>
These models provide deeper insights into the response of biomaterials under mechanical stimuli and turning floppy spring-like networks (biomaterials) into tunable rigid networks (or composites) for the desired response as well as material failure using computaional tools in soft matter and statistical mechanics. 
I am deeply interested in applying computational tools using principles of physics and chemical engineering to solve real world problems and drive innovation in the field of soft materials, healthcare and engineering. Please feel free to reach out for discussions or collaborations.
</p>
    <p>
      <strong>Contact&nbsp;•</strong>
      <a href="mailto:prathamesh.kulkarni@rice.edu">Email</a> ·
      <a href="https://scholar.google.com/citations?hl=en&user=AB1YjFIAAAAJ">Google Scholar</a> ·
      <a href="www.linkedin.com/in/prathamesh-kulkarni-944a8b111">LinkedIn</a>
    </p>
  </div>

  <div class="col-md-5 text-center">
    <!-- <img src="/assets/images/lattice.png" class="img-fluid rounded" -->
         <!-- alt="Lattice simulation snapshot"> -->
  </div>
</div>



<!-- Duplicate ↑ block for more projects -->
<div>
<!-- ===== PUBLICATIONS ===== -->
<h2 id="publications" class="mt-5">Publications</h2>
<ul>
<li> Kulkarni, P., Kolomeisky, A. B., MacKintosh, F. C., Stress relaxation in spring networks via force-dependent stochastic
severing (In prep) </li>
<li> Kulkarni, P., Gupta, S., Kolomeisky, A. B., MacKintosh, F. C., Mechanics of composite networks with rope-like
filament (In preparation) </li>
</ul>
</div>


<!-- ===== PROJECTS ===== -->
<h2 id="projects" class="mt-5">Projects and Gallery</h2>

<p> Crosslinked fiber networks form a crucial part of biological systems contributing towards building tissues and are vital for processes like cell motility while being responsible for the structural
integrity. Their mechanical behavior is highly influenced by individual fiber properties and the network architecture, and so the average coordination number or connectivity (z) of the network architecture plays a critical role.Recent theories and experiments on fiber
network behavior have shown a strain-controlled rigidity transition. When subjected to finite incremental shear deformation, the networks transition from floppy to rigid
states at a critical strain threshold depending on the network connectivity and geometry. This transition exhibits rich critical phenomena and is second-order in nature. 
</p>

<!-- <div><img class="bg-white p-3 text-center my-3" src="/images/phasediagramschematic.png" class="img-fluid rounded" alt="phasediagramschematic" width="300"> -->
<!-- </div> -->
<div class="bg-white p-3 text-center my-3"> 
  <img src="/images/phasediagram_background2.png"
       class="img-fluid rounded"
       alt="phase‑diagram schematic"
       width="400">
</div>

<p>At the phase boundary, there is formation of load bearing force chains that span the system. Here are some movies that demonstrate their mechanical behavior:</p>

<div class="row my-4  text-center">
  <div class="col-md-4 text-center">

  <h3>Stress relaxation in spring networks via force-depedendent stochastic severing</h3>

<!-- <p> Highly crosslinked network at shear strain under stochastic filament loss </p> -->
<p> Highly crosslinked network at shear strain under stochastic filament loss for Tension-enhanced (positive)  and Tension-suppressed (negative) mechano-chemical feedback:</p>
<p> <span style="color: red;">Red:</span>  High tension <span style="color:blue;">Blue:</span>  low tension/compression </p>
<!-- poster="/files/DoubleNetwork_zoomed.png" -->
<!-- Project 1 -->
<!-- ===== side‑by‑side video pair ===== -->
<!--
<div class="row my-4">

  
  <div class="col-12 col-md-6 text-center">
    <figure class="figure">
      <video src="/assets/videos/output_-50_new_u2.mp4"
             class="img-fluid"
             controls loop muted preload="metadata" width="300"></video>
      <figcaption class="figure-caption">
        Negative feedback: force chains persist → rigidity
      </figcaption>
    </figure>
  </div>

  
  <div class="col-12 col-md-6 text-center">
    <figure class="figure">
      <video src="/assets/videos/output_50_new_u2.mp4"
             class="img-fluid"
             controls loop muted preload="metadata" width="300"></video>
      <figcaption class="figure-caption">
        Positive feedback: chains lost → no rigidity
      </figcaption>
    </figure>
  </div>

</div>
-->

    <figure class="figure">
    <video src="/assets/videos/output_-50_new_u2.mp4"
           width="400" controls loop muted preload="metadata"></video>
       <figcaption class="figure-caption">
         <!-- Negative feedback: Load bearing force chains are present even at lower connectivities => rigidity  -->
        <!-- Z=4.0&nbsp;&nbsp;·&nbsp;&nbsp;γ = 0.2 -->
       </figcaption>       
       <p>Negative feedback: Load bearing force chains are present even at lower connectivities => rigidity </p>
          </figure>
          
  </div>

  <!-- <div> -->
  <div class="col-md-4 text-center">
    <figure class="figure">
    <video src="/assets/videos/output_50_new_u2.mp4"
           width="400" controls loop muted preload="metadata"></video>
       <figcaption class="figure-caption">
        <!-- Positive feedback: Load bearing force chains are absent even at higher connectivities => no rigidity  -->
        <!-- Z=4.0&nbsp;&nbsp;·&nbsp;&nbsp;γ = 0.2 -->
       </figcaption>       
       <p>Positive feedback: Load‑bearing force chains are absent even at higher connectivities ⇒ no rigidity</p>
          </figure> 
  </div>
</div>
<!-- </div> -->

  
<div class="row-my-4 text-center">
  
  <div class="col-md-4 text-center">
<h3>Mechanics of composite networks with rope-like filaments</h3>
<img src="/files/DoubleNetwork_zoomed.png" class="img-fluid rounded" alt="Double Network snapshot" width="400">
  </div>
  <div class="col-md-4">
        <video src="/assets/videos/output_video_sample1000.mp4"
           width="400" controls loop muted preload="metadata"></video>
    <!-- <img src="/files/DoubleNetwork_zoomed.png" class="img-fluid rounded" alt="Double Network snapshot" width="300"> -->
         <figcaption class="figure-caption">
        Network achieves rigidity at lower strains than expected as the ropes "activate"!
        <!-- Z=4.0&nbsp;&nbsp;·&nbsp;&nbsp;γ = 0.2 -->
       </figcaption>       
       <p>Network achieves rigidity at lower strains than expected as the ropes "activate"!</p>
  </div>


  <div class="col-md-4  text-center" >
    <h3>Robophysics bootcamp</h3>

     <video src="/assets/videos/bootcamp_video.mp4"
           width="400" controls loop muted preload="metadata"></video>

  </div>
      <p>
    Arduino-programmed 5-linker robot using Dynamixel servo motors. Such robots can be used as model system to test principles of locomotion as well as understand biomechanics and locomotion of organisms like snakes, centipedes, etc. 
    </p>
</div>
<!-- </div> -->

<!--  START: side‑by‑side video comparison  -->
<!-- <div class="row">
  <div class="col-md-4"> <video src="/assets/videos/output_-50_new_u2.mp4"
           width="300" controls loop muted preload="metadata"></video></div>
  <div class="col-md-4"> <video src="/assets/videos/output_50_new_u2.mp4"
           width="300" controls loop muted preload="metadata"></video></div>
</div> -->