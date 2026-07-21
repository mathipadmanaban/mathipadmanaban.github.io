---
layout: home
author_profile: true
---
<div class="hero-section">
    <div class="hero-content">
        <h1 class="hero-title">Gandhimathi (Mathi) Padmanaban</h1>
        <p class="hero-subtitle">Applied Computer Vision and Machine Learning &middot; Ph.D., Industrial and Systems Engineering, University of Michigan-Dearborn</p>
        <p class="hero-vision">I build geometry-grounded perception that stays reliable when the camera, platform, or site changes, and that signals when it should not be trusted.</p>
        <p class="hero-availability">Seeking postdoctoral and research positions, 2026&ndash;27. &nbsp;&middot;&nbsp; <a href="/assets/files/Mathi_CV.pdf" target="_blank">Download CV</a></p>
    </div>
</div>

<div class="page__content">
    <h2 id="about-me">About Me</h2>
    <p>I am an applied computer vision and machine learning researcher. I completed my Ph.D. in Industrial and Systems Engineering at the University of Michigan-Dearborn, advised by Dr. Fred Feng (dissertation defended June 2026). My work builds perception systems that human-AI systems can rely on, and that keep working when the sensor, platform, or recording site changes. Each feature starts from how a vehicle's projection in the image encodes its geometry, the way its bounding box grows as it approaches and its bearing shifts as it passes, and I derive that quantitatively from the pinhole camera model so the feature carries a physical quantity rather than raw appearance. Geometric-consistency checks reject detections that violate the projection model, and a confidence threshold lets the classification stage abstain rather than commit to a label it cannot support.</p>

    <p>I demonstrated this in road-safety measurement, estimating vehicle-bicyclist interactions from a single uncalibrated bicycle camera and showing that the same geometry-grounded formulation transfers to a different platform (the Waymo Open Dataset) when re-fit to a new supervision source. A second line of work models driver behavior from vehicle kinematics, the human side of any system that operates around people. I care about open, reproducible research, and I want to take the same approach, building the real structure of a problem into the model, into new domains where cheap sensors have to make reliable measurements. I am currently seeking postdoctoral and research positions.</p>

    <h2 id="research-focus">Research Focus</h2>
    <p>I work on perception that has to hold up outside the conditions it was built in. In my dissertation that meant grounding measurements in the geometry of how a camera forms an image, and having the classifier withhold a prediction when its confidence was low. Both were useful, in one domain, and both rested on choices I set by hand: the validation rules, the abstention threshold, and the sensor labels needed to re-fit the model on a new platform.</p>

    <p>What interests me now is making those choices less arbitrary. I want to know whether the physics of a scene can drive test-time adaptation to a new platform, in place of the sensor labels my own work relied on, and whether conformal prediction can put a real coverage guarantee behind an abstention threshold I currently set by hand. I am also interested in whether scene geometry can be used to check the spatial claims of large pretrained perception models, which are usually evaluated on clean imagery rather than in the conditions where they get deployed.</p>

    <h2 id="news">News</h2>
    <div class="news-list">
        <div class="news-item">
            <div class="news-date">Jun 2026</div>
            <div class="news-body">
                <div class="news-headline">Defended my Ph.D. dissertation, <em>Adaptable Machine Learning and Computer Vision Frameworks for Road Safety: Applications to Driver Behavior and Driver-Bicyclist Interaction Research</em>, at UM-Dearborn, advised by Dr. Fred Feng.</div>
            </div>
        </div>
        <div class="news-item">
            <div class="news-date">Jun 2026</div>
            <div class="news-body">
                <div class="news-headline">Released an open-source two-stage pipeline for injury-risk vehicle body-type classification (RT-DETR plus a fine-tuned ViT), which holds 89% accuracy on held-out sites without retraining and abstains rather than guess when confidence is low.</div>
                <div class="news-links">
                    <a href="https://doi.org/10.48550/arXiv.2606.05149" target="_blank"><i class="fas fa-file-alt"></i> arXiv:2606.05149</a>
                    <a href="https://github.com/fenggroup/vehicle-type-classifier" target="_blank"><i class="fab fa-github"></i> Code</a>
                </div>
            </div>
        </div>
        <div class="news-item">
            <div class="news-date">Jan 2026</div>
            <div class="news-body">
                <div class="news-headline">Presented at the Transportation Research Board (TRB) Annual Meeting, Washington, DC: geometry-informed overtaking detection from a single bicycle-mounted camera (poster), plus a co-authored talk.</div>
                <div class="news-links">
                    <a href="https://par.nsf.gov/biblio/10679667" target="_blank"><i class="fas fa-external-link-alt"></i> NSF PAR</a>
                </div>
            </div>
        </div>
        <div class="news-item">
            <div class="news-date">Oct 2025</div>
            <div class="news-body">
                <div class="news-headline">Received the Student Visionary Award at the International Forum on Research Excellence (IFoRE '25), Sigma Xi.</div>
            </div>
        </div>
        <div class="news-item">
            <div class="news-date">Apr 2025</div>
            <div class="news-body">
                <div class="news-headline">Presented at the WCX SAE World Congress Experience, Detroit: naturalistic acceleration and deceleration profiles benchmarked against EPA fuel-economy test cycles.</div>
                <div class="news-links">
                    <a href="https://www.sae.org/publications/technical-papers/content/2025-01-8605/" target="_blank"><i class="fas fa-external-link-alt"></i> SAE Technical Paper 2025-01-8605</a>
                </div>
            </div>
        </div>
    </div>

    <h2>Education</h2>
    <div class="education-list">
        <div class="education-item">
            <div class="degree">Ph.D. in Industrial and Systems Engineering</div>
            <div class="institution">University of Michigan-Dearborn (dissertation defended June 2026; degree Aug 2026)</div>
            <div class="year">Advisor: Dr. Fred Feng</div>
        </div>
        <div class="education-item">
            <div class="degree">M.S. in Human Centered Design and Engineering</div>
            <div class="institution">University of Michigan-Dearborn</div>
            <div class="year">2021</div>
        </div>
        <div class="education-item">
            <div class="degree">B.E. in Computer Science and Engineering</div>
            <div class="institution">Anna University, India</div>
            <div class="year">2013</div>
        </div>
    </div>

    <h2>Research Interests</h2>
    <div class="interests-list">
        <ul>
            <li class="interest-item"><strong>Methods</strong>: Geometry-informed computer vision • Physics-grounded measurement • Reliability-aware perception (out-of-distribution robustness, confidence-threshold abstention, conformal prediction) • Physics-driven test-time adaptation • Geometric checks on large pretrained perception models • Object detection and tracking • Behavioral modeling from kinematics</li>
            <li class="interest-item"><strong>Domains (current and exploring)</strong>: Infrastructure and platform-agnostic sensing • Trustworthy perception for human-AI systems • Remote sensing and environmental / climate machine learning • Vulnerable road user and transportation safety</li>
        </ul>
    </div>

    <h2>Selected Awards</h2>
    <div class="awards">
        <div class="award-item">
            <div class="award-title">Student Visionary Award</div>
            <div class="award-details">International Forum on Research Excellence (IFoRE '25), Sigma Xi</div>
            <div class="award-info">2025</div>
        </div>
        <div class="award-item">
            <div class="award-title">Upsilon Pi Epsilon (UPE) Scholarship</div>
            <div class="award-details">For academic performance and leadership in the computing community</div>
            <div class="award-info">2024</div>
        </div>
        <div class="award-item">
            <div class="award-title">Global Finalist, NASA Space Apps Challenge</div>
            <div class="award-details">DigitwiML: digital twin of C. elegans in space</div>
            <div class="award-info">2023</div>
        </div>
        <div class="award-item">
            <div class="award-title">Irma M. Wyman Scholar</div>
            <div class="award-details">Center for the Education of Women (CEW+), University of Michigan</div>
            <div class="award-info">$11,500 · 2020-2021</div>
        </div>
    </div>

    <p style="margin-top:1.5em;"><a href="/assets/files/Mathi_CV.pdf" target="_blank">See full CV</a> for the complete list of awards, publications, and service.</p>

</div>
