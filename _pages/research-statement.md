---
layout: single
permalink: /research-statement/
author_profile: true
title: "Research Statement & Vision"
---

## Research Philosophy

My research philosophy centers on developing **safe, trustworthy, and mathematically grounded hybrid AI systems** for safety-critical applications. Through extensive experience applying both data-driven and physics-informed methods, I have gained firsthand understanding of where each approach fails individually—data-driven methods often lack interpretability and struggle with out-of-distribution scenarios, while physics-informed methods can be overly rigid and miss complex patterns in real-world data. This experience has shaped my vision to build **hybrid AI frameworks** that find the optimal mathematical blend of these approaches, creating systems that are both more reliable and easier to understand for safety-critical deployment.

I believe that the most transformative research emerges at disciplinary intersections—in my case, at the nexus of **Industrial & Systems Engineering**, **Computer Vision**, **Machine Learning**, and **Mathematical Optimization**. This interdisciplinary approach enables me to address complex real-world challenges with both theoretical rigor and practical relevance, particularly in domains where safety and trust are paramount.

I am deeply committed to **open science** and **reproducible research**. All my work emphasizes transparent methodologies, rigorous mathematical foundations, and the development of reproducible pipelines that the broader research community can build upon. I believe that research should not only advance scientific knowledge but also create tangible benefits for society, particularly in safety-critical domains where reliability, interpretability, and mathematical guarantees are essential.

As a first-generation graduate student and international scholar, I bring diverse perspectives to research challenges and am passionate about fostering **inclusive research environments** where creativity and innovation thrive through collaboration across backgrounds and disciplines.

## Evolution of My Research Vision

My research journey has been guided by a central question: *How can we develop intelligent systems that are not only accurate but also reliable, interpretable, and trustworthy in safety-critical applications?*

This vision emerged from my Master's work in **computational human performance modeling**, where I developed open-source tools for simulating human cognition and evaluating user interfaces. This experience revealed the power of computational methods to predict and understand complex behaviors while highlighting the critical importance of model transparency, validation, and mathematical rigor.

During my doctoral research, I evolved this foundation into a comprehensive research program exploring the **synergies and limitations of data-driven and physics-informed approaches**. My dissertation work on **calibration-free distance estimation**, **overtaking detection systems**, and **driver behavior classification** provided firsthand experience with both paradigms:

- **Data-driven methods** (Transformers, CNNs, Random Forest) demonstrated remarkable pattern recognition capabilities but often lacked interpretability and struggled with uncertainty quantification
- **Physics-informed methods** (geometric constraints, perspective geometry, PINNs) provided strong theoretical foundations and interpretability but were limited by rigid assumptions and incomplete physical models

This dual experience revealed a critical gap: neither approach alone provides the reliability, interpretability, and mathematical guarantees needed for safety-critical applications. This insight has shaped my research identity and **future vision**: developing **mathematically rigorous hybrid AI frameworks** that optimally blend data-driven learning with physics-informed constraints, creating systems that are both more reliable and easier to understand for safety-critical deployment.

## Current Research Contributions

My doctoral research has produced several methodological innovations with demonstrated impact:

### 1. Calibration-Free Distance Estimation Using Geometry-Informed Computer Vision
I developed a novel approach that leverages perspective geometry principles to estimate distances from monocular images without requiring camera calibration. This method achieved a **mean absolute error of 12.6 ± 2.9 cm** in cross-validation studies, with comprehensive uncertainty quantification and error analysis. The reproducible pipeline I created enables researchers to apply this method across diverse contexts, from transportation safety to robotics.

**Key Innovation**: Bridging classical geometric principles with modern computer vision to create practical, deployable solutions that don't require expensive calibration procedures.

### 2. Geometric Overtaking Detection with Early Warning
Combining YOLOv5 object detection with ByteTrack tracking and geometric validation, I created a system that detects vehicle overtaking events with **98.7% precision** and **98.1% recall**, providing **2.89 seconds of early warning** time. Validated on 319 real-world events across 41,500 frames, this work directly supports cyclist safety research and infrastructure planning.

**Key Innovation**: Integrating multiple computer vision techniques with geometric constraints to achieve both high accuracy and practical utility in challenging real-world conditions.

### 3. Machine Learning for Aggressive Driving Classification
I developed a comprehensive pipeline for identifying aggressive driving patterns using speed-adjusted longitudinal jerk features, achieving **93.8% classification accuracy** with Random Forest models across 556 driving trips. This work includes automated preprocessing, robust cross-validation protocols, and interpretable feature engineering.

**Key Innovation**: Creating interpretable, physics-grounded features that enable accurate behavioral classification while maintaining model transparency for safety applications.

### 4. Comparative Analysis of Driving Profiles and Fuel Economy
My analysis of acceleration and deceleration patterns across aggressive driving styles and EPA fuel economy test cycles (presented at **SAE WCX 2025**) provides actionable insights for sustainable transportation policies and driver assistance system design.

**Key Innovation**: Bridging behavioral research with sustainability engineering to inform both policy and system design.

## Future Research Directions

My research agenda builds on these foundations to develop **safe and trustworthy hybrid AI systems** with mathematical rigor for safety-critical applications. The core vision is to create frameworks that optimally blend data-driven and physics-informed methods, addressing the fundamental limitations I've observed in both approaches. This represents my **proposed future research program**:

### 1. Mathematical Foundations for Hybrid AI Safety (Core Research)
- **Rigorous uncertainty quantification** in hybrid models with provable bounds on prediction confidence
- **Mathematical frameworks** for optimal blending of data-driven and physics-informed components
- **Safety guarantees** through formal verification of hybrid AI systems
- **Interpretability metrics** that quantify and ensure model transparency for safety-critical decisions

**Funding Potential**: NSF CISE Core Programs, DARPA Assured Autonomy, AFOSR Computational Mathematics

### 2. Hybrid AI for Transportation Safety and Autonomous Systems
- **Multi-modal perception** combining camera, LiDAR, and radar with physics-informed fusion
- **Real-time decision making** with uncertainty-aware hybrid models for autonomous vehicles
- **Calibration-free safety systems** that adapt to diverse environmental conditions
- **Human-AI collaboration** frameworks for semi-autonomous transportation systems

**Funding Potential**: NSF CMMI, DOT FHWA, NHTSA Safety Research, DARPA programs

### 3. Trustworthy AI for Critical Infrastructure
- **Smart manufacturing systems** with hybrid AI for quality control and predictive maintenance
- **Energy grid optimization** using physics-informed ML for renewable integration
- **Cybersecurity applications** with interpretable anomaly detection and threat assessment
- **Healthcare systems** with safe AI for medical diagnosis and treatment planning

**Funding Potential**: NSF CMMI Advanced Manufacturing, DOE Grid Modernization, NIST, NIH

### 4. Robust and Interpretable Computer Vision
- **Geometry-informed transformers** that combine attention mechanisms with physical constraints
- **Few-shot learning** for safety-critical applications with limited labeled data
- **Adversarial robustness** through physics-informed defense mechanisms
- **Cross-domain generalization** ensuring models work reliably across different contexts

**Funding Potential**: NSF CISE Computer Vision, DARPA AI programs, ONR Basic Research

### 5. Open-Source Tools and Reproducible Research
- **Hybrid AI frameworks** with standardized interfaces for data-driven and physics components
- **Benchmarking suites** for evaluating safety and trustworthiness in AI systems
- **Educational resources** for training the next generation in safe AI development
- **Community standards** for reproducible research in hybrid AI

**Funding Potential**: NSF CISE Education, Sloan Foundation, Industry partnerships

## Broader Impacts and Societal Relevance

My research directly addresses critical societal challenges through safe and trustworthy AI:

- **Safety-Critical Applications**: Hybrid AI frameworks ensure reliable performance in transportation, healthcare, and infrastructure systems where failures can have severe consequences
- **AI Trust and Transparency**: Mathematical guarantees and interpretability metrics build public confidence in AI systems and enable responsible deployment
- **Democratization of Safe AI**: Open-source tools and frameworks make advanced safety-critical AI accessible to smaller organizations and resource-constrained settings
- **Workforce Development**: Training the next generation in mathematically rigorous AI development prepares them for careers in safety-critical domains
- **Policy and Regulation**: Research provides evidence-based foundations for AI safety standards and regulatory frameworks
- **Economic Impact**: Reliable AI systems reduce costs associated with failures, recalls, and safety incidents across industries

## Research Training and Mentorship Vision

As a faculty member, I will build a diverse, collaborative research group focused on:

### Mentorship Approach
- **Mathematical rigor**: Students develop strong foundations in both data-driven and physics-informed methods
- **Safety-first mindset**: Training emphasizes reliability, interpretability, and mathematical guarantees from the start
- **Project-based learning**: Students work on publishable research with real-world safety-critical applications
- **Reproducible practices**: Training in version control, documentation, and open science for transparent research
- **Professional development**: Support for conference presentations, paper writing, and career planning
- **Individual growth plans**: Tailored mentorship recognizing each student's unique goals and strengths

### Fostering Inclusive Excellence
- **Recruiting diversity**: Active outreach to underrepresented groups through partnerships with organizations like WOC Code, NSBE, and SHPE
- **Creating belonging**: Establishing lab culture that values different perspectives and lived experiences
- **Supporting success**: Providing resources, advocacy, and mentorship particularly for first-generation and international students
- **Community building**: Connecting students with broader networks through conferences, workshops, and collaborations

### Interdisciplinary Collaboration
- **Cross-departmental partnerships**: Collaborating with computer science, mathematics, transportation, civil engineering, and human factors researchers
- **Industry connections**: Maintaining relationships with automotive, tech, healthcare, and manufacturing sectors for real-world safety-critical problem validation
- **National lab engagement**: Pursuing joint appointments and summer programs with DOE, NIST, and other national laboratories
- **International collaboration**: Building partnerships with leading researchers in AI safety and trustworthy systems globally

## Vision for External Funding and Partnerships

My research program is positioned to attract funding from multiple sources focused on AI safety and trustworthy systems:

- **Federal agencies**: NSF (CISE, CMMI, ENG), DARPA (Assured Autonomy, AI programs), DOE (Grid Modernization, VTO), DOT (FHWA, NHTSA), AFOSR, ONR
- **Industry partnerships**: Automotive (Ford, GM, Tesla), technology (Google, Microsoft, NVIDIA), healthcare (Medtronic, Johnson & Johnson), manufacturing sectors
- **Foundations**: Arnold Ventures (transportation safety), Alfred P. Sloan Foundation (technology and society), Schmidt Futures (AI safety)
- **National laboratories**: Collaborations with Argonne, Oak Ridge, NREL, NIST for applied research and facility access
- **International partnerships**: EU Horizon programs, UKRI, Canadian NSERC for global AI safety initiatives

I am committed to building a sustainable research program that combines fundamental methodological advances in hybrid AI with practical applications that benefit society, training the next generation of researchers to work at the intersection of mathematics, engineering, and safety-critical AI systems.

---

*This research vision reflects my commitment to advancing the field of safe and trustworthy AI while creating tangible societal benefits, fostering inclusive research environments, and training future leaders in mathematically rigorous computational engineering.*

