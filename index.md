---
layout: page
---

<style>
.profile { color: #2f2f2f; font-size: 16px; line-height: 1.65; }
.profile a { color: #2f5d8a; text-decoration: none; }
.profile a:hover { text-decoration: underline; }

.profile p, .profile p + p { text-indent: 0; margin-top: 0; }

.profile-header { display: flex; align-items: flex-start; gap: 32px; }
.profile-intro { flex: 1 1 auto; min-width: 0; }
.profile-header h1 { margin: 0 0 12px; font-size: 2.2rem; line-height: 1.15; }
.profile-header p { margin: 0 0 12px; }
.profile-links a + a { margin-left: 16px; }

.profile-photo { flex: 0 0 250px; margin-top: 4px; }
.profile-photo img { display: block; width: 100%; height: auto; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,.12); }
.profile-photo-caption { margin-top: 6px; color: #777; font-size: 0.8rem; line-height: 1.4; text-align: center; }

.open-to { margin-top: 24px; padding: 12px 16px; border-left: 4px solid #2f5d8a; background: #f2f6fa; border-radius: 4px; }

.profile section { margin-top: 34px; }
.profile h2 { margin: 0 0 14px; padding-bottom: 7px; border-bottom: 1px solid #e5e5e5; font-size: 1.45rem; }

.highlights { margin: 0; padding-left: 20px; }
.highlights li { margin-bottom: 8px; }

.stack-row { display: flex; gap: 16px; margin-bottom: 10px; }
.stack-label { flex: 0 0 150px; font-weight: 600; color: #444; }
.chip { display: inline-block; margin: 0 6px 6px 0; padding: 1px 10px; border: 1px solid #d6dde5; border-radius: 99px; background: #f7f9fb; font-size: 0.88rem; }

.publication { margin-bottom: 18px; }
.publication-title { font-weight: 600; }
.publication-meta { color: #555; }
.publication.featured { padding: 16px 18px; border: 1px solid #e5e5e5; border-left: 4px solid #d9480f; border-radius: 6px; background: #fbf8f4; }
.publication.featured .publication-title { font-size: 1.08rem; }
.badge { display: inline-block; margin-right: 8px; padding: 1px 8px; border-radius: 99px; color: #fff; font-size: 0.8rem; font-weight: 600; vertical-align: 2px; }
.badge-new { background: #d9480f; }
.badge-review { background: #6c757d; }
.publication-links a + a { margin-left: 14px; }

.timeline { margin: 0; padding: 0; list-style: none; }
.timeline li { margin-bottom: 8px; }
.timeline-date { display: inline-block; min-width: 150px; color: #666; font-weight: 600; }

.news { margin: 0; padding: 0; list-style: none; }
.news li { margin-bottom: 8px; }
.news-date { display: inline-block; min-width: 88px; color: #666; font-weight: 600; }

@media (max-width: 700px) {
  .profile-header { display: block; }
  .profile-photo { max-width: 320px; margin: 16px auto 0; }
  .stack-row { display: block; }
  .stack-label { margin-bottom: 4px; }
  .timeline-date, .news-date { display: block; }
}
</style>

<div class="profile">

<div class="profile-header">
  <div class="profile-intro">
    <h1>Hanyang Zhong (钟翰扬)</h1>
    <p>
      PhD candidate in Electronic Engineering (Robotics) at the
      <a href="https://www.york.ac.uk/">University of York</a>, UK (expected Jan 2027).
      I build complete real-robot systems for <strong>dexterous, contact-rich manipulation</strong>:
      dexterous hands and fingertip force sensors, embedded control, multimodal data collection,
      and imitation-learning policies deployed on physical robots. I also build
      <strong>agentic robots</strong> that use LLM/MLLM reasoning to drive learned skills.
    </p>
    <p class="profile-links">
      <a href="mailto:hanyangzhong552@gmail.com">Email</a>
      <a href="https://scholar.google.com/citations?user=6cbhsRMAAAAJ">Google Scholar</a>
      <a href="https://github.com/HanyangZhong">GitHub</a>
      <a href="https://huggingface.co/hanyang1">Hugging Face</a>
    </p>
  </div>
  <div class="profile-photo">
    <img src="images/icra2026_booth.jpg" alt="Hanyang Zhong presenting the MLLM-Fabric poster at ICRA 2026" />
    <div class="profile-photo-caption">Presenting our <a href="https://ieeexplore.ieee.org/abstract/document/11217170">MLLM-Fabric</a> poster at ICRA 2026, Vienna</div>
  </div>
</div>

<div class="open-to">
  <strong>Open to roles from early 2027:</strong> Robotics / Embodied AI Research Scientist,
  Robot Learning Engineer, or Postdoc, in dexterous manipulation, robot learning and embodied AI.
</div>

<section>
  <h2>Highlights</h2>
  <ul class="highlights">
    <li><strong>Co-first author of <a href="https://dexremo.github.io/">DexRemo</a>, accepted to IEEE T-RO (2026).</strong>
      Designed the hardware and fingertip force sensors for a low-cost, 12-DoF three-finger hand.
      Adding fingertip force raised imitation-learning success from <strong>24% to 83%</strong>,
      and the hand reached a <strong>62.5 N</strong> pull-out strength, the highest among the hands we compared.</li>
    <li><strong>5 peer-reviewed papers</strong> in T-RO, RA-L, ICME (Oral), ICMEW and CogSci; first or co-first author on 4.</li>
    <li><strong>Built a full robot stack alone:</strong> the bimanual teleoperation platform, force sensors, PCB and firmware,
      the data pipeline, and policy deployment. Independent first author of a bimanual imitation-learning paper under review at ICRA 2027.</li>
    <li><strong>Reviewer</strong> for ICRA, RSS, CoRL and IROS. Presented a poster at ICRA 2026 in Vienna.</li>
    <li><strong>Open-source releases:</strong> the <a href="https://huggingface.co/datasets/EuniceF/MLLM-Fabric">MLLM-Fabric dataset</a>,
      the <a href="https://github.com/HanyangZhong/BRU-datasets">BRU dataset</a> and <a href="https://github.com/HanyangZhong/FENet">FENet code</a>.</li>
    <li><strong>Industry experience:</strong> 2 years as an Embedded Systems Engineer and 3 years as a Graduate Teaching Assistant for MSc Intelligent Robotics.</li>
  </ul>
</section>

<section>
  <h2>Tech Stack</h2>
  <div class="stack-row">
    <div class="stack-label">Robot Learning</div>
    <div><span class="chip">Imitation Learning</span><span class="chip">ACT-style Policies</span><span class="chip">Teleoperation Data Collection</span><span class="chip">Multimodal Policies (Vision / Force / Tactile)</span><span class="chip">Real-Robot Deployment</span></div>
  </div>
  <div class="stack-row">
    <div class="stack-label">Embodied AI</div>
    <div><span class="chip">LLM / MLLM Task Planning</span><span class="chip">Agentic Skill Orchestration</span><span class="chip">VLA Systems</span><span class="chip">MLLM Fine-tuning</span></div>
  </div>
  <div class="stack-row">
    <div class="stack-label">Software</div>
    <div><span class="chip">Python</span><span class="chip">C++</span><span class="chip">PyTorch</span><span class="chip">ROS</span><span class="chip">OpenCV</span><span class="chip">Linux</span><span class="chip">Git</span><span class="chip">Multi-sensor Sync &amp; Logging</span></div>
  </div>
  <div class="stack-row">
    <div class="stack-label">Hardware</div>
    <div><span class="chip">Fingertip Force / F-T Sensing</span><span class="chip">Sensor Calibration</span><span class="chip">PCB Design</span><span class="chip">Embedded Firmware</span><span class="chip">Motor Control</span></div>
  </div>
  <div class="stack-row">
    <div class="stack-label">Mechanical</div>
    <div><span class="chip">SolidWorks</span><span class="chip">Inventor</span><span class="chip">Dexterous Hand Prototyping</span><span class="chip">3D Printing</span><span class="chip">CNC</span><span class="chip">Sheet Metal</span></div>
  </div>
</section>

<section>
  <h2>Selected Publications</h2>

  <div class="publication featured">
    <div class="publication-title"><span class="badge badge-new">New</span>DexRemo: A Force-Sensing Hand Platform and Task Suite for Contact-Rich Removal Manipulation</div>
    <div>Liman Wang<sup>&dagger;</sup>, <strong>Hanyang Zhong</strong><sup>&dagger;</sup>, Zhaole Sun, Wenting Cao, Babar Jamil, Andy Tyrrell, Shan Luo, Jihong Zhu
      <span class="publication-meta">(<sup>&dagger;</sup>equal contribution)</span></div>
    <div class="publication-meta"><em>IEEE Transactions on Robotics (T-RO), 2026, accepted</em></div>
    <div class="publication-links">
      <a href="https://dexremo.github.io/">Project Page</a>
      <a href="https://arxiv.org/abs/2611.15981">Paper</a>
      <a href="https://youtu.be/4ot1Yy7es_o">Video</a>
    </div>
  </div>

  <div class="publication">
    <div class="publication-title"><span class="badge badge-review">Under Review</span>Hidden Force-Regime Coverage for Contact-Rich Bimanual Imitation Learning</div>
    <div><strong>Hanyang Zhong</strong>, et al.</div>
    <div class="publication-meta"><em>IEEE International Conference on Robotics and Automation (ICRA), 2027, under review</em></div>
  </div>

  <div class="publication">
    <div class="publication-title">MLLM-Fabric: Multimodal Large Language Model-Driven Robotic Framework for Fabric Sorting and Selection</div>
    <div>Liman Wang, <strong>Hanyang Zhong</strong>, Tianyuan Wang, Shan Luo, Jihong Zhu</div>
    <div class="publication-meta"><em>IEEE Robotics and Automation Letters (RA-L), 2025; presented at ICRA 2026</em></div>
    <div class="publication-links">
      <a href="https://ieeexplore.ieee.org/abstract/document/11217170">Paper</a>
      <a href="https://github.com/limanwang/MLLM-Fabric">Code</a>
      <a href="https://huggingface.co/datasets/EuniceF/MLLM-Fabric">Dataset</a>
    </div>
  </div>

  <div class="publication">
    <div class="publication-title">Balancing Rigor and Utility: Mitigating Cognitive Biases in Large Language Models for Multiple-Choice Questions</div>
    <div><strong>Hanyang Zhong</strong><sup>&dagger;</sup>, Liman Wang<sup>&dagger;</sup>, Wenting Cao, Zeyuan Sun</div>
    <div class="publication-meta"><em>Annual Meeting of the Cognitive Science Society (CogSci), 2025</em></div>
    <div class="publication-links">
      <a href="https://escholarship.org/uc/item/2vr690cx">Paper</a>
      <a href="https://hanyangzhong.github.io/BRU-website/">Project Page</a>
      <a href="https://github.com/HanyangZhong/BRU-datasets">Dataset</a>
    </div>
  </div>

  <div class="publication">
    <div class="publication-title">FENet: Focusing Enhanced Network for Lane Detection</div>
    <div>Liman Wang<sup>&dagger;</sup>, <strong>Hanyang Zhong</strong><sup>&dagger;</sup></div>
    <div class="publication-meta"><em>IEEE International Conference on Multimedia and Expo (ICME), 2024, <strong>Oral</strong></em></div>
    <div class="publication-links">
      <a href="https://ieeexplore.ieee.org/document/10687857">Paper</a>
      <a href="https://github.com/HanyangZhong/FENet">Code</a>
    </div>
  </div>

  <div class="publication">
    <div class="publication-title">LLM-SAP: Large Language Models Situational Awareness-Based Planning</div>
    <div>Liman Wang<sup>&dagger;</sup>, <strong>Hanyang Zhong</strong><sup>&dagger;</sup></div>
    <div class="publication-meta"><em>IEEE ICME Workshops (ICMEW), 2024</em></div>
    <div class="publication-links">
      <a href="https://ieeexplore.ieee.org/document/10645429">Paper</a>
      <a href="https://arxiv.org/abs/2312.16127">arXiv</a>
    </div>
  </div>

  <div class="publication-meta"><sup>&dagger;</sup> equal contribution</div>
</section>

<section>
  <h2>Education &amp; Experience</h2>
  <ul class="timeline">
    <li><span class="timeline-date">2022 – Jan 2027</span><strong>PhD, Electronic Engineering (Robotics)</strong>, University of York, UK</li>
    <li><span class="timeline-date">2022 – 2025</span><strong>Graduate Teaching Assistant</strong>, MSc Intelligent Robotics, University of York</li>
    <li><span class="timeline-date">2021 – 2022</span><strong>MSc, Intelligent Robotics</strong>, University of York, UK</li>
    <li><span class="timeline-date">2019 – 2021</span><strong>Embedded Systems Engineer</strong>, Zhigong Control Technology, Guangzhou, China</li>
    <li><span class="timeline-date">2015 – 2019</span><strong>BEng, Electronic Information Engineering</strong>, Jiangxi University of Water Resources and Electric Power</li>
  </ul>
</section>

<section>
  <h2>Reviewing</h2>
  <p>ICRA 2026, 2027 · RSS 2027 · CoRL 2026 · IROS 2026 · Complex &amp; Intelligent Systems · ICME 2024</p>
</section>

<section>
  <h2>News</h2>
  <ul class="news">
    <li><span class="news-date">Nov 2026</span><a href="https://dexremo.github.io/">DexRemo</a> accepted to <strong>IEEE T-RO</strong>.</li>
    <li><span class="news-date">Nov 2026</span>Reviewer for <strong>ICRA 2027</strong> and <strong>RSS 2027</strong>.</li>
    <li><span class="news-date">Jun 2026</span>Presented MLLM-Fabric at <strong>ICRA 2026</strong>, Vienna.</li>
    <li><span class="news-date">Oct 2025</span>MLLM-Fabric accepted to <strong>IEEE RA-L</strong>.</li>
    <li><span class="news-date">Jul 2025</span>Balancing Rigor and Utility accepted to <strong>CogSci 2025</strong>.</li>
    <li><span class="news-date">Mar 2024</span>FENet accepted to <strong>ICME 2024</strong> as an oral paper.</li>
  </ul>
</section>

</div>
