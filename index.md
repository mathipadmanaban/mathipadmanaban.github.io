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


    <p>I am a researcher working on whether what an automated system reports can be relied on by the person who has to act on it. I hold a Ph.D. in Industrial and Systems Engineering and an M.S. in Human-Centered Design and Engineering, both from the University of Michigan-Dearborn, where I was advised by <a href="https://fenggroup.org" target="_blank">Dr. Fred Feng</a>.</p>

    <p>A system's own confidence is a poor guide to whether its output is right, because models are confidently wrong where they have not been before. My work checks outputs against something outside the model: the geometry of how an image was formed, a known standard, or the procedure used to certify the system. Longer term, I want reliability to be something an automated system can demonstrate to the people who depend on it, rather than something inferred from its own confidence.</p>

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
          <p>Speed-adjusted jerk thresholds jointly optimized with the classifier, because the same jerk magnitude means different things at 20 and 60 mph. 94% accuracy, AUC-ROC 0.971, across 556 trips and seven vehicle models. <em>Submitted, SAE WCX 2027.</em></p>
        </div>
      </div>

      <div class="work-row">
        <div class="work-thumb"><img src="/assets/images/work/overtaking-pipeline.png" alt="Detection, tracking and geometric validation stages"></div>
        <div class="work-body">
          <div class="t">A Geometry-Informed Computer Vision Method for Detecting and Examining Overtaking Vehicles From a Bicycle</div>
          <p class="pub-authors"><strong>G. Padmanaban</strong>, R. Moustafa, F. Feng</p>
          <p>Perspective-geometry validation on top of RT-DETR detection and ByteTrack tracking, discarding tracks that are not physically consistent with an overtaking manoeuvre. 98.1% recall with one false positive across 315 events. <em>Submitted, IEEE Transactions on Intelligent Transportation Systems. Poster, TRB Annual Meeting 2026.</em> <a href="https://par.nsf.gov/biblio/10679667" target="_blank">NSF PAR</a> &middot; <a href="https://github.com/fenggroup/vehicle-overtaking-tracker" target="_blank">Code</a></p>
        </div>
      </div>

      <div class="work-row no-thumb">
        <div class="work-body">
          <div class="t">Vision-Based Lateral Passing Distance Estimation from Bicycle-Mounted Cameras: A Projective Geometry Approach</div>
          <p class="pub-authors"><strong>G. Padmanaban</strong>, F. Feng</p>
          <p>Estimates how closely a vehicle passes a cyclist from bounding-box geometry, with no camera calibration. 0.126 m MAE; R&sup2; = 0.812 re-fit on the Waymo Open Dataset. <em>In preparation.</em> <a href="/research/">Details</a></p>
        </div>
      </div>

      <div class="work-row no-thumb">
        <div class="work-body">
          <div class="t">Quantifying Drivers-Overtaking-Bicyclists with Surrogate Safety Measures Derived from High-Resolution Digital Lidar</div>
          <p class="pub-authors">R. Moustafa, <strong>G. Padmanaban</strong>, F. Feng</p>
          <p> <em>Transportation Research Board Annual Meeting, 2026.</em> <a href="https://par.nsf.gov/biblio/10679666" target="_blank">NSF PAR</a></p>
        </div>
      </div>

      <div class="work-row no-thumb">
        <div class="work-body">
          <div class="t">Adaptable Machine Learning and Computer Vision Frameworks for Road Safety: Applications to Driver Behavior and Driver-Bicyclist Interaction Research</div>
          <p class="pub-authors"><strong>G. Padmanaban</strong></p>
          <p> <em>Ph.D. dissertation, University of Michigan-Dearborn, 2026. Advisor: Dr. Fred Feng.</em></p>
        </div>
      </div>

      <div class="work-row">
        <div class="work-thumb"><img src="/assets/images/work/epa-cycles.png" alt="On-road speed and acceleration profiles against EPA fuel economy cycles"></div>
        <div class="work-body">
          <div class="t">A Comparative Analysis of Acceleration and Deceleration Profiles for Aggressive Driving Styles and Fuel Economy Test Cycles</div>
          <p class="pub-authors"><strong>G. Padmanaban</strong>, F. Feng, E. Dai, A. Saini, G. Hu, Y. Zhao</p>
          <p>Whether the standardized cycles used to certify vehicle behaviour represent naturalistic driving. US06 approximates aggressive acceleration but overstates deceleration intensity, and the milder cycles overestimate it as well. <em>WCX SAE World Congress Experience, 2025. SAE Technical Paper 2025-01-8605.</em> <a href="https://doi.org/10.4271/2025-01-8605" target="_blank">DOI</a></p>
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


    <h2 id="news">News</h2>
    <div class="news-list">
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
