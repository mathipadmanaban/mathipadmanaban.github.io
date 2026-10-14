---
layout: home
author_profile: true
---
<div class="hero-section">
    <div class="hero-content">
        <h1 class="hero-title">Gandhimathi (Mathi) Padmanaban</h1>
        <p class="hero-subtitle">Ph.D., Industrial and Systems Engineering, University of Michigan-Dearborn</p>
        <p class="hero-availability">On the 2026&ndash;27 Academic Job Market &nbsp;&middot;&nbsp; <a href="/assets/files/mathi_cv.pdf" target="_blank">CV</a> &nbsp;&middot;&nbsp; <a href="mailto:gmathi@umich.edu">gmathi@umich.edu</a></p>
    </div>
</div>

<div class="page__content">

<style>
.work-list { margin: 1.2em 0; }
.work-row { display: flex; gap: 1.1em; align-items: flex-start; margin-bottom: 1.6em; }
.work-thumb { flex: 0 0 190px; }
.work-row.no-thumb .work-body { padding-left: 0; }
.work-thumb img { width: 100%; height: auto; border: 1px solid #e6e6e6; border-radius: 3px; background: #fff; }
.work-body { flex: 1 1 auto; }
.work-body .t { font-weight: 600; }
.work-body .pub-authors { font-size: 0.85em; color: #666; margin: 0.15em 0 0.4em 0; }
@media (max-width: 620px) {
  .work-row { display: block; }
  .work-thumb { max-width: 320px; margin-bottom: 0.6em; }
}
</style>


    <p>I build and evaluate adaptable AI systems that are driven and constrained by physical measurements from multimodal data in safety-critical settings involving human interaction. My research sits at the intersection of computer vision, machine learning, and human-centered automation, applied to transportation safety.</p>

    <p>I completed my Ph.D. in Industrial and Systems Engineering at the University of Michigan-Dearborn in August 2026, advised by <a href="https://fenggroup.org" target="_blank">Dr. Fred Feng</a>. My dissertation built tools for driver behavior and driver-bicyclist interaction research. One estimates how closely a vehicle passes a cyclist from a single bicycle-mounted camera using projective geometry, and another detects overtaking vehicles and keeps only the tracks whose movement matches a vehicle passing from behind. I also built a classifier that sorts passing vehicles by injury risk to cyclists and outputs "unknown" when its confidence is low, and a model that identifies aggressive driving from vehicle kinematics and pedal operations. In the lab's LiDAR study of drivers overtaking cyclists, I worked on synchronizing the LiDAR and camera data. Before the Ph.D., I completed an M.S. in Human Centered Design and Engineering on human performance modeling, after five years in the software industry building human-machine interfaces.</p>

    <p>My long-term research agenda is to make these systems auditable, so that the people who share roads and other spaces with them are not the ones who discover when they are wrong.</p>

    <h2 id="publications">Publications</h2>
    <div class="work-list">

      <div class="work-row">
        <div class="work-thumb"><img src="/assets/images/work/multi-view-id.jpg" alt="Vehicle classification results across four frames, including unknown labels"></div>
        <div class="work-body">
          <div class="t">A Multi-View Vehicle Image Dataset and Two-Stage Pipeline for Fine-Grained Vehicle-Type Recognition at Ground Level</div>
          <p class="pub-authors"><strong>G. Padmanaban</strong>, F. Feng</p>
          <p>Detection followed by a fine-tuned ViT over six classes defined by injury risk to cyclists. 89% accuracy at held-out sites with no retraining, and an "unknown" output under low confidence rather than a committed label. <em>In preparation, CVPR 2027.</em> <a href="https://doi.org/10.48550/arXiv.2606.05149" target="_blank">Earlier preprint</a> &middot; <a href="https://github.com/fenggroup/vehicle-type-classifier" target="_blank">Code</a></p>
        </div>
      </div>

      <div class="work-row">
        <div class="work-thumb"><img src="/assets/images/work/agg-driving-pipeline.png" alt="Machine learning pipeline from raw kinematics to model selection"></div>
        <div class="work-body">
          <div class="t">A Machine Learning Framework to Identify Aggressive Driving Based on Vehicle Kinematics and Driver Pedal Operations</div>
          <p class="pub-authors"><strong>G. Padmanaban</strong>, F. Feng, E. Dai, A. Saini, G. Hu, Y. Zhao</p>
          <p>Speed-adjusted jerk thresholds jointly optimized with the classifier, because the same jerk magnitude means different things at 20 and 60 mph. 94% accuracy, AUC-ROC 0.971, across 556 trips and seven vehicle models. <em>Abstract accepted, SAE WCX 2027.</em></p>
        </div>
      </div>

      <div class="work-row">
        <div class="work-thumb"><img src="/assets/images/work/overtaking-pipeline.png" alt="Detection, tracking and geometric validation stages"></div>
        <div class="work-body">
          <div class="t">A Geometry-Informed Computer Vision Method for Detecting and Examining Overtaking Vehicles From a Bicycle</div>
          <p class="pub-authors"><strong>G. Padmanaban</strong>, R. Moustafa, F. Feng</p>
          <p>RT-DETR detection and multi-object tracking, followed by three checks from camera geometry that keep only the tracks whose movement matches a vehicle passing from behind. 98.1% recall across 315 annotated events, with a mean of 2.37 s warning before the vehicle passes. <em>Submitted, IEEE Transactions on Intelligent Transportation Systems. Poster, TRB Annual Meeting 2026.</em> <a href="https://par.nsf.gov/biblio/10679667" target="_blank">NSF PAR</a> &middot; <a href="https://github.com/fenggroup/vehicle-overtaking-tracker" target="_blank">Code</a></p>
        </div>
      </div>

      <div class="work-row no-thumb">
        <div class="work-body">
          <div class="t">Vision-Based Lateral Passing Distance Estimation from Bicycle-Mounted Cameras: A Projective Geometry Approach</div>
          <p class="pub-authors"><strong>G. Padmanaban</strong>, F. Feng</p>
          <p>Estimates how closely a vehicle passes a cyclist from bounding-box geometry derived from the pinhole camera model. 0.126 m mean absolute error, and R&sup2; = 0.812 when re-fitted on the Waymo Open Dataset. <em>Poster accepted, International Cycling Safety Conference 2026. Journal manuscript in preparation.</em> <a href="/research/">Details</a></p>
        </div>
      </div>

      <div class="work-row no-thumb">
        <div class="work-body">
          <div class="t">Quantifying Drivers-Overtaking-Bicyclists with Surrogate Safety Measures Derived from High-Resolution Digital Lidar</div>
          <p class="pub-authors">R. Moustafa, <strong>G. Padmanaban</strong>, F. Feng</p>
          <p>Surrogate safety measures for drivers overtaking cyclists, from high-resolution LiDAR. <em>Transportation Research Board Annual Meeting, 2026.</em> <a href="https://par.nsf.gov/biblio/10679666" target="_blank">NSF PAR</a></p>
        </div>
      </div>

      <div class="work-row no-thumb">
        <div class="work-body">
          <div class="t">Adaptable Machine Learning and Computer Vision Frameworks for Road Safety: Applications to Driver Behavior and Driver-Bicyclist Interaction Research</div>
          <p class="pub-authors"><strong>G. Padmanaban</strong></p>
          <p> <em>Ph.D. dissertation, University of Michigan-Dearborn, 2026. Advisor: Dr. Fred Feng.</em> <a href="https://doi.org/10.7302/dspace/30874" target="_blank">Deep Blue</a></p>
        </div>
      </div>

      <div class="work-row">
        <div class="work-thumb"><img src="/assets/images/work/epa-cycles.png" alt="On-road speed and acceleration profiles against EPA fuel economy cycles"></div>
        <div class="work-body">
          <div class="t">A Comparative Analysis of Acceleration and Deceleration Profiles for Aggressive Driving Styles and Fuel Economy Test Cycles</div>
          <p class="pub-authors"><strong>G. Padmanaban</strong>, F. Feng, E. Dai, A. Saini, G. Hu, Y. Zhao</p>
          <p>Whether the standardized cycles used to certify vehicles represent on-road driving. US06 approximates aggressive acceleration but overstates deceleration intensity, and the milder cycles overestimate it as well. <em>WCX SAE World Congress Experience, 2025. SAE Technical Paper 2025-01-8605.</em> <a href="https://doi.org/10.4271/2025-01-8605" target="_blank">DOI</a></p>
        </div>
      </div>

      <div class="work-row no-thumb">
        <div class="work-body">
          <div class="t">An Autonomous Driving System: Dedicated Vehicle for People with ASD and their Caregivers</div>
          <p class="pub-authors"><strong>G. Padmanaban</strong>, N. P. Jachim, H. Shandi, L. Avetisyan, G. Smith, H. Hammoud, F. Zhou</p>
          <p> <em>AutomotiveUI '21 Adjunct, ACM, 2021, pp. 142-147.</em> <a href="https://doi.org/10.1145/3473682.3480282" target="_blank">DOI</a></p>
        </div>
      </div>

      <div class="work-row no-thumb">
        <div class="work-body">
          <div class="t">Computational Human Performance Modeling using Queuing Network in an Open-Source Platform</div>
          <p class="pub-authors"><strong>G. Padmanaban</strong></p>
          <p> <em>M.S. thesis, University of Michigan-Dearborn, 2021.</em> <a href="https://deepblue.lib.umich.edu/handle/2027.42/169161/" target="_blank">Deep Blue</a></p>
        </div>
      </div>

    </div>


    <h2 id="software">Research Software</h2>
    <div class="work-list">
      <div class="work-row no-thumb"><div class="work-body"><div class="t">Geometry-informed overtaking tracker</div><p>Automated measurement of vehicle-bicyclist interactions with a physical plausibility check on detector output. Python. <a href="https://github.com/fenggroup/vehicle-overtaking-tracker" target="_blank">GitHub</a></p></div></div>
      <div class="work-row no-thumb"><div class="work-body"><div class="t">Vehicle type classifier</div><p>Injury-risk vehicle classification that abstains under low confidence. Python. <a href="https://github.com/fenggroup/vehicle-type-classifier" target="_blank">GitHub</a></p></div></div>
      <div class="work-row no-thumb"><div class="work-body"><div class="t">DigitwiML</div><p>Machine learning platform for digital twin modeling of biological dynamics in space environments; Global Finalist, NASA Space Apps Challenge 2023. Python. <a href="https://github.com/gmbabu6/DigitwiML" target="_blank">GitHub</a></p></div></div>
    </div>

    <h2 id="news">News</h2>
    <div class="news-list">
        <div class="news-item">
            <div class="news-date">Oct 2026</div>
            <div class="news-body"><div class="news-headline">Abstract accepted at SAE WCX 2027 for the aggressive-driving detection framework.</div></div>
        </div>
        <div class="news-item">
            <div class="news-date">Oct 2026</div>
            <div class="news-body"><div class="news-headline">Passing-distance poster accepted at the International Cycling Safety Conference (ICSC 2026), Knoxville, November 2026.</div></div>
        </div>
        <div class="news-item">
            <div class="news-date">Aug 2026</div>
            <div class="news-body"><div class="news-headline">Completed my Ph.D. at the University of Michigan-Dearborn.</div></div>
        </div>
        <div class="news-item">
            <div class="news-date">Jun 2026</div>
            <div class="news-body">
                <div class="news-headline">Released an open-source pipeline for injury-risk vehicle classification with confidence-based abstention.</div>
                <div class="news-links">
                    <a href="https://doi.org/10.48550/arXiv.2606.05149" target="_blank"><i class="fas fa-file-alt"></i> arXiv:2606.05149</a>
                    <a href="https://github.com/fenggroup/vehicle-type-classifier" target="_blank"><i class="fab fa-github"></i> Code</a>
                </div>
            </div>
        </div>
        <div class="news-item">
            <div class="news-date">Jan 2026</div>
            <div class="news-body">
                <div class="news-headline">Presented at the Transportation Research Board Annual Meeting, Washington, DC.</div>
                <div class="news-links"><a href="https://par.nsf.gov/biblio/10679667" target="_blank"><i class="fas fa-external-link-alt"></i> NSF PAR</a></div>
            </div>
        </div>
        <div class="news-item">
            <div class="news-date">Oct 2025</div>
            <div class="news-body"><div class="news-headline">Student Visionary Award, International Forum on Research Excellence (IFoRE '25), Sigma Xi.</div></div>
        </div>
    </div>

</div>
