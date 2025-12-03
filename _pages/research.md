---
layout: single
permalink: /research/
author_profile: true
title: "Research Projects"
---

<p>My research develops <strong>geometry-informed computer vision</strong> and <strong>machine learning methods</strong> for reliable measurement, perception, and decision support in safety-critical applications. I focus on creating interpretable, calibration-free solutions with rigorous validation and reproducible implementations.</p>

<div class="research-impact">
  <h3>Research Approach & Tools</h3>
  <p><strong>Programming & Frameworks</strong>: Python (expert) • PyTorch • TensorFlow • scikit-learn • OpenCV • NumPy • Pandas • Matplotlib • Julia • R • MATLAB</p>
  <p><strong>Computer Vision</strong>: YOLO (v5, v8) • RT-DETR • ByteTrack • Vision Transformers (ViTs) • Multi-object detection & tracking • Multi-modal data fusion • LiDAR processing</p>
  <p><strong>Machine Learning</strong>: Deep learning (CNNs, RNNs, Transformers) • Ensemble methods (Random Forest, XGBoost) • SVM • Bayesian methods • Physics-informed ML • Uncertainty quantification • Out-of-distribution detection</p>
  <p><strong>Research Practices</strong>: Experimental design • Statistical analysis • Cross-validation • Version control (Git/GitHub) • Reproducible pipelines • HPC (Slurm) • Docker • IRB protocols • Peer review • Technical documentation • LaTeX</p>
</div>

<div class="current-research">
  <h2>Current Research</h2>
  <div class="research-title">Geometry-Informed Computer Vision for Overtaking Distance Estimation from 2D Images</div>
  <div class="research-desc">Developing novel methods that leverage perspective geometry principles to estimate distances from monocular images without camera calibration requirements. Preliminary results achieved <strong>MAE 12.6 ± 2.9 cm</strong> in cross-validation with fully reproducible pipelines. This work enables practical deployment of distance measurement in resource-constrained settings and diverse environmental conditions.</div>
  <div class="project-contributions">
    <div class="contributions-title">Key Contributions:</div>
    <ul>
      <li>Novel calibration-free method combining geometric principles with transformer based computer vision</li>
      <li>Comprehensive benchmarking and ablation studies demonstrating robustness</li>
      <li>Open-source implementation with reproducible research pipeline</li>
    </ul>
  </div>
</div>

<div class="projects">
  <h2>Dissertation Projects</h2>
  <div class="project-item">
    <div class="project-title">Geometry-Informed Computer Vision Based Overtaking Detection with Early Warning for Cyclist Safety</div>
    <div class="project-desc">Developed an integrated computer vision system combining YOLOv5 object detection, ByteTrack tracking, and geometric validation to detect and analyze vehicle overtaking events from a bicycle-mounted camera. The system achieved <strong>98.7% precision</strong> and <strong>98.1% recall</strong> while providing <strong>2.89 seconds of early warning</strong> time. Validated on <strong>319 real-world overtaking events</strong> across 41,500 frames captured in naturalistic cycling conditions.</div>
    <div class="project-contributions">
      <div class="contributions-title">Key Contributions:</div>
      <ul>
        <li>Multi-stage detection pipeline integrating deep learning with geometric constraints</li>
        <li>Robust event validation methodology for safety-critical applications</li>
        <li>Early warning system enabling proactive safety interventions</li>
        <li>Comprehensive real-world dataset and evaluation protocol</li>
        <li>Applications to infrastructure planning and cyclist safety policy</li>
      </ul>
    </div>
    <div class="project-links">
      <i class="fas fa-file-alt"></i> <em>Paper under review (2025)</em>
    </div>
  </div>

  <div class="project-item">
    <div class="project-title">Comparative Analysis: Aggressive Driving Profiles vs. Fuel Economy Test Cycles</div>
    <div class="project-desc">Conducted comprehensive comparative analysis of acceleration and deceleration patterns between real-world aggressive driving behaviors and EPA fuel economy test cycles. The study reveals significant discrepancies between standardized testing protocols and actual driving patterns, with implications for vehicle efficiency ratings, emissions testing, and sustainable transportation policy. <strong>Presented at SAE World Congress Experience (WCX) 2025.</strong></div>
    <div class="project-contributions">
      <div class="contributions-title">Key Contributions:</div>
      <ul>
        <li>Quantitative characterization of aggressive driving acceleration/deceleration patterns</li>
        <li>Gap analysis between real-world driving and EPA test cycle assumptions</li>
        <li>Evidence-based recommendations for policy and testing protocol improvements</li>
        <li>Implications for sustainable transportation and emissions reduction strategies</li>
      </ul>
    </div>
    <div class="project-links">
      <a href="https://www.sae.org/publications/technical-papers/content/2025-01-8605/" target="_blank"><i class="fas fa-external-link-alt"></i> SAE Technical Paper</a>
    </div>
  </div>

  <div class="project-item">
    <div class="project-title">Machine Learning for Aggressive Driving Prediction from Longitudinal Jerk</div>
    <div class="project-desc">Developed a comprehensive machine learning pipeline for identifying aggressive driving patterns using speed-adjusted longitudinal jerk features derived from vehicle kinematics. The system achieved <strong>93.8% classification accuracy</strong> using Random Forest models, validated across <strong>556 driving trips</strong> with rigorous cross-validation protocols. The interpretable feature engineering approach enables practical deployment in real-time driver assistance systems.</div>
    <div class="project-contributions">
      <div class="contributions-title">Key Contributions:</div>
      <ul>
        <li>Novel speed-adjusted jerk features capturing driving aggressiveness</li>
        <li>Automated preprocessing and feature extraction pipeline</li>
        <li>Comprehensive model comparison and hyperparameter optimization</li>
        <li>Robust cross-validation ensuring generalization</li>
      </ul>
    </div>
    <div class="project-links">
      <i class="fas fa-file-alt"></i> <em>Paper under review (2025)</em>
    </div>
  </div>

  <h2>Master's Thesis</h2>
  <div class="project-item">
    <div class="project-title">Computational Human Performance Modeling using Queuing Network in an Open-Source Platform</div>
    <div class="project-desc">Implemented an open-source version of the QN-MHP (Queuing Network-Model Human Processor) cognitive architecture using Python and SimPy for computational user interface testing. The model simulates human cognition as a queuing network of information processors, enabling cost-effective UI evaluation without extensive human subject testing. Model validation using visual-manual tasks demonstrated strong alignment with empirical data.</div>
    <div class="project-contributions">
      <div class="contributions-title">Key Contributions:</div>
      <ul>
        <li>Open-source implementation democratizing access to cognitive modeling tools</li>
        <li>Validation framework demonstrating model accuracy against empirical data</li>
        <li>Practical tool for designers to evaluate UI designs computationally</li>
        <li>Foundation for future human-automation interaction research</li>
      </ul>
    </div>
    <div class="project-links">
      <a href="http://dx.doi.org/10.7302/2328" target="_blank"><i class="fas fa-external-link-alt"></i> Master's Thesis</a>
    </div>
  </div>

  <h2>Research Software & Open Source Projects</h2>
  
  <div class="project-item">
    <div class="project-title">Geometry-Informed Overtaking Tracker</div>
    <div class="project-desc">Computer vision system for tracking vehicle overtaking bicyclists using YOLOv5, RT-DETR, ByteTrack, and geometric validation. Implemented in Python with comprehensive documentation and reproducible pipelines. Achieves 98.7% precision and 98.1% recall on real-world naturalistic cycling data.</div>
    <div class="project-contributions">
      <div class="contributions-title">Key Contributions:</div>
      <ul>
        <li>Multi-stage detection and tracking pipeline with geometric constraints</li>
        <li>Early warning system providing 2.89 seconds advance notice</li>
        <li>Comprehensive validation on 319 real-world events across 41,500 frames</li>
        <li>Open-source implementation for research community</li>
      </ul>
    </div>
  </div>
  
  <div class="project-item">
    <div class="project-title">DigitwiML: Digital Twin Modeling Platform for C. elegans in Space</div>
    <div class="project-desc">NASA SpaceApps Challenge Global Finalist project developing an open-source digital twin modeling platform for simulating C. elegans behavior in microgravity environments. Combines computational modeling, data visualization, and machine learning to support space biology research.</div>
    <div class="project-contributions">
      <div class="contributions-title">Key Contributions:</div>
      <ul>
        <li>Global Finalist recognition at NASA SpaceApps Challenge 2023</li>
        <li>Open-source platform accessible to space biology researchers</li>
        <li>Integration of biological modeling with machine learning</li>
        <li>Educational outreach through presentations and workshops</li>
      </ul>
    </div>
    <div class="project-links">
      <a href="https://github.com/" target="_blank"><i class="fas fa-external-link-alt"></i> GitHub Repository</a>
    </div>
  </div>
  
  <div class="project-item">
    <div class="project-title">Human Performance Modeling Tools</div>
    <div class="project-desc">Open-source queuing network simulation platform for computational human performance modeling using Python and SimPy. Implements the QN-MHP (Queuing Network-Model Human Processor) cognitive architecture, enabling cost-effective UI evaluation without extensive human subject testing.</div>
    <div class="project-contributions">
      <div class="contributions-title">Key Contributions:</div>
      <ul>
        <li>Open-source implementation of QN-MHP cognitive architecture</li>
        <li>Democratizes access to computational human performance modeling</li>
        <li>Validation against empirical data from visual-manual tasks</li>
        <li>Foundation for M.S. thesis research in human-centered design</li>
      </ul>
    </div>
  </div>
  
  <h2>Additional Research Projects</h2>
  <div class="project-item">
    <div class="project-title">Intelligent Lane Change Prediction for Autonomous Vehicles using Temporal Convolutional Networks</div>
    <div class="project-desc">Developed a deep learning system for predicting vehicle lane change behaviors using Temporal Convolutional Networks (TCN). Using real-world trajectory data from the NGSIM dataset, the model achieved <strong>98.66% prediction accuracy</strong> with rapid computational time, making it suitable for real-time deployment in autonomous vehicle decision-making systems.</div>
    <div class="project-contributions">
      <div class="contributions-title">Key Contributions:</div>
      <ul>
        <li>TCN architecture optimized for sequential trajectory analysis</li>
        <li>High-accuracy predictions enabling proactive autonomous vehicle responses</li>
        <li>Efficient computational performance for real-time applications</li>
        <li>Validation on large-scale real-world driving dataset</li>
      </ul>
    </div>
  </div>
  
  <div class="project-item">
    <div class="project-title">Mixed Methods Study: Data Privacy Perceptions in Messenger Applications</div>
    <div class="project-desc">Conducted comprehensive mixed-methods research exploring user perceptions of data privacy in messaging applications, comparing WhatsApp and Signal. The study analyzed the critical balance between privacy, trust, and usability, revealing users' strong preference for transparency and aggregate (vs. personal) data usage. Findings inform privacy-preserving design practices for communication technologies.</div>
    <div class="project-contributions">
      <div class="contributions-title">Key Contributions:</div>
      <ul>
        <li>Mixed-methods approach combining quantitative and qualitative insights</li>
        <li>Evidence-based understanding of privacy-usability trade-offs</li>
        <li>Design recommendations for privacy-preserving messaging systems</li>
        <li>Contributions to human-computer interaction and trust research</li>
      </ul>
    </div>
  </div>
  
  <div class="project-item">
    <div class="project-title">Autonomous Driving System for People with Autism Spectrum Disorder</div>
    <div class="project-desc">Designed specialized autonomous vehicle (ADS-DV) tailored for individuals with Autism Spectrum Disorder through human-centered design and extensive stakeholder engagement with caregivers. Developed customized interior design and companion mobile application addressing safety, monitoring, and individual preferences to enhance independent mobility. <strong>Published at ACM AutomotiveUI 2021.</strong></div>
    <div class="project-contributions">
      <div class="contributions-title">Key Contributions:</div>
      <ul>
        <li>Human-centered design approach for accessibility and inclusion</li>
        <li>Stakeholder engagement methodology with caregivers and families</li>
        <li>Customized AV interior and interface design for specific needs</li>
        <li>Broader impacts framework for accessible autonomous transportation</li>
      </ul>
    </div>
    <div class="project-links">
      <a href="https://doi.org/10.1145/3473682.3480282" target="_blank"><i class="fas fa-external-link-alt"></i> AutomotiveUI 2021 Paper</a>
    </div>
  </div>
</div>