---
layout: single
permalink: /research/
author_profile: true
title: "Research"
---

<p>I want reliability to be something an automated system can demonstrate to the people who depend on it, rather than something inferred from its own confidence. That means building external checks that hold where models fail, and evaluations that measure what people are actually relying on the system for.</p>

<p>The work below is where I have built and tested that so far. Physical settings are the proving ground, because ground truth still exists in them: the geometry of how a camera formed an image, or a standard a system is supposed to meet, can adjudicate a claim independently of the model that made it. The projects run from measurement systems that report a number a person acts on, through checks that discard outputs the situation rules out and a classifier that declines rather than guess, to a result that asks the same question of a certification test instead of a model.</p>

<div class="projects">
  <h2>Doctoral Research</h2>

  <div class="project-item">
    <div class="project-title">Vision-Based Lateral Passing Distance Estimation from Bicycle-Mounted Cameras: A Projective Geometry Approach</div>
    <div class="project-desc">A framework that estimates how closely a vehicle passes a cyclist from 2D bounding-box geometry alone, with no camera calibration. Three features derived from the pinhole camera model absorb the unknown calibration constants when fit to a cheap ultrasonic proximity sensor as the training signal.</div>
    <div class="project-contributions">
      <div class="contributions-title">Key results</div>
      <ul>
        <li>0.126 m mean absolute error (MAPE 8.2%) on 92 naturalistic passing events, leave-one-group-out cross-validation.</li>
        <li>External validation on the Waymo Open Dataset (re-fit with LiDAR supervision, different platform and range): R&sup2; = 0.812, MAPE 6.6%, across 11,248 detections. The physics-grounded feature design transferred; the model was retrained, not applied zero-shot.</li>
      </ul>
    </div>
    <div class="project-links">
      <em>In preparation</em>
    </div>
  </div>

  <div class="project-item">
    <div class="project-title">A Geometry-Informed Computer Vision Method for Detecting and Examining Overtaking Vehicles From a Bicycle</div>
    <div class="project-desc">An automated pipeline that detects vehicle overtaking events from a single rear-facing bicycle-mounted camera, with no multi-sensor rig and no calibration. A three-stage geometric validation module (bearing-angle trend, apparent-size growth, spatial confirmation) enforces perspective-geometry rules on top of RT-DETR detection and ByteTrack tracking, rejecting detections that are physically implausible for an overtaking maneuver.</div>
    <div class="project-contributions">
      <div class="contributions-title">Key results</div>
      <ul>
        <li>98.1% recall with a single false positive across 315 annotated events.</li>
        <li>Mean advance warning of 2.37 s before passage; 83.2% of events exceed a 1.5 s reaction-time threshold.</li>
      </ul>
    </div>
    <div class="project-links">
      <em>Submitted, IEEE Transactions on Intelligent Transportation Systems; TRB Annual Meeting 2026 (poster)</em> · <a href="https://par.nsf.gov/biblio/10679667" target="_blank"><i class="fas fa-external-link-alt"></i> NSF PAR</a> · <a href="https://github.com/fenggroup/vehicle-overtaking-tracker" target="_blank"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>

  <div class="project-item">
    <div class="project-title">A Multi-View Vehicle Image Dataset and Two-Stage Pipeline for Fine-Grained Vehicle-Type Recognition at Ground Level</div>
    <div class="project-desc">A two-stage pipeline (RT-DETR detection plus a fine-tuned ViT-Base/16) that classifies passing vehicles into six categories defined by injury risk to cyclists (passenger car, SUV, pickup, minivan, large van, commercial truck), rather than make and model. I assembled and labeled the custom dataset and designed the taxonomy. The classifier abstains and outputs "unknown" when confidence is low, rather than silently misclassifying.</div>
    <div class="project-contributions">
      <div class="contributions-title">Key results</div>
      <ul>
        <li>94% accuracy in-distribution (3,805 events; per-class F1 0.91-0.97).</li>
        <li>89% accuracy on separate held-out sites with no retraining, with abstention correctly rising under distribution shift.</li>
      </ul>
    </div>
    <div class="project-links">
      <em>In preparation, CVPR 2027</em> · <a href="https://doi.org/10.48550/arXiv.2606.05149" target="_blank"><i class="fas fa-external-link-alt"></i> Earlier preprint</a> · <a href="https://github.com/fenggroup/vehicle-type-classifier" target="_blank"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>



  <div class="project-item">
    <div class="project-title">A Machine Learning Framework to Identify Aggressive Driving Based on Vehicle Kinematics and Driver Pedal Operations</div>
    <div class="project-desc">A machine learning framework that classifies aggressive versus non-aggressive driving from longitudinal jerk and driver pedal operations. The core idea is a speed-adjusted jerk threshold, four speed segments aligned with FHWA roadway functional classes, jointly optimized with the classifier over a large grid search, because the same jerk magnitude means different things at 20 mph and 60 mph.</div>
    <div class="project-contributions">
      <div class="contributions-title">Key results</div>
      <ul>
        <li>94% accuracy, AUC-ROC 0.971 (Random Forest), across 556 trips and 7 vehicle models.</li>
        <li>Speed-adjusted thresholds consistently beat fixed thresholds across all classifiers and feature sets.</li>
      </ul>
    </div>
    <div class="project-links">
      <em>Submitted, SAE WCX 2027</em>
    </div>
  </div>

  <div class="project-item">
    <div class="project-title">A Comparative Analysis of Acceleration and Deceleration Profiles for Aggressive Driving Styles and Fuel Economy Test Cycles</div>
    <div class="project-desc">The same reliability question, asked of a test procedure instead of a model: does the standardized cycle used to certify vehicle behaviour represent the behaviour it certifies? A speed-segmented characterization of real-world aggressive and non-aggressive driving, benchmarked against four EPA fuel-economy test cycles. The US06 cycle approximates aggressive acceleration but substantially overstates aggressive deceleration intensity; all milder cycles also overestimate deceleration relative to naturalistic driving, with implications for powertrain calibration and fuel-economy labeling.</div>
    <div class="project-links">
      <a href="https://www.sae.org/publications/technical-papers/content/2025-01-8605/" target="_blank"><i class="fas fa-external-link-alt"></i> SAE Technical Paper 2025-01-8605</a>
      <em>WCX SAE World Congress Experience, 2025</em>
    </div>
  </div>

  <h2>Earlier Work</h2>

  <div class="project-item">
    <div class="project-title">Computational Human Performance Modeling using Queuing Network in an Open-Source Platform</div>
    <div class="project-desc">An open-source implementation of the QN-MHP (Queuing Network-Model Human Processor) cognitive architecture in Python and SimPy, modeling human multitask performance as a queuing network of information processors so that interface designs can be evaluated computationally. Validated against empirical visual-manual task data.</div>
    <div class="project-links">
      <a href="http://dx.doi.org/10.7302/2328" target="_blank"><i class="fas fa-external-link-alt"></i> Thesis</a>
    </div>
  </div>

  <div class="project-item">
    <div class="project-title">An Autonomous Driving System: Dedicated Vehicle for People with ASD and their Caregivers</div>
    <div class="project-desc">A human-centered design study for an autonomous vehicle tailored to individuals with Autism Spectrum Disorder and their caregivers, developed through stakeholder engagement, with a customized interior concept and companion application addressing safety and monitoring.</div>
    <div class="project-links">
      <a href="https://doi.org/10.1145/3473682.3480282" target="_blank"><i class="fas fa-external-link-alt"></i> AutomotiveUI 2021</a>
    </div>
  </div>
</div>
