---
layout: default
title: Home
---

<link rel="stylesheet" href="/assets/css/style.css">

<nav class="site-nav">
  <a href="#bridge">Bridge</a>
  <a href="#projects">Projects</a>
  <a href="#skills">Skills</a>
  <a href="#contact">Contact</a>
</nav>

<header class="hero">

  <!-- Uncomment when profile picture is added -->

  <!--
  <img src="/assets/img/profile.jpg"
      alt="Profile picture"
      class="profile-pic">
  -->

  <h1>Jose Ramon Jeronimo Liñan</h1>
  <p class="tagline">
    Bridging biology and computation to turn biological data into decisions 
  </p>
  <p class="intro">
    As a bioprocess engineer, I bring the biological understanding behind the data — along with laboratory and industrial experience — to my computational biology work
  </p>
  <a class="btn btn-primary" href="#contact">Get in touch</a>

</header>

<main>

  <section id="bridge">
  <h2>Bridge</h2>
  <p>Bioprocess engineering taught me to read biological systems under pressure — optimizing fermentation runs, designing controlled experiments, and translating batch data into process decisions. That training built a skill most computational pipelines lack: the ability to look at a statistical output and ask what it means for the organism, not just the model. I build workflows with that lens built in, so the results translate into actions, not just plots.</p>
  <p><strong>What I bring:</strong></p>
  <ul>
  <li>Experimental design experience that catches data quality problems before they reach the pipeline</li>
  <li>The biological grounding to interpret computational outputs in context — not just report them</li>
  <li>Industrial and research exposure across fermentation, microbial systems, and omics</li>
  </ul>
  </section>


  <section id="projects">
  <h2>Projects</h2>

  <div class="cards-grid">

  <div class="project-card">
  <h3>gempipe</h3>
  <p>Manually discovering where a metabolic pathway is broken is painful. Gempipe provides the reactions that are causing the model to fail, shortening the discovery time from hours of manual search to minutes of automatic computing</p>
  <span class="pill" data-status="progress">In Progress</span>
  <div class="chips">
    <span class="chip">Python</span>
    <span class="chip">COBRApy</span>
  </div>
  <a class="overview-link" href="#" data-open-modal="gempipe-overview">Quick overview &#x2193;</a>
  <div class="card-footer">
    <a href="#">View repo &rarr;</a>
  </div>
  </div>

<!-- REST OF CARDS COMMENTED OUT
  Pattern for each new card:

  <div class="project-card">
  <h3>Project Name</h3>
  <p>One-sentence description</p>
  <span class="pill" data-status="live|progress|planned">Status</span>
  <div class="chips">
    <span class="chip">Tool</span>
  </div>
  <a class="overview-link" href="#project-name-overview">Quick overview &#x2193;</a>
  <div class="card-footer">
    <a href="https://github.com/...">View repo &rarr;</a>
  </div>
  </div>

  <div class="project-card">
  <h3>Single-Cell Transcriptomics Analysis</h3>
  <p>Single-cell RNA sequencing analysis using Scanpy, including QC, clustering and cell-type annotation.</p>
  <span class="pill" data-status="planned">Planned</span>
  <div class="chips">
    <span class="chip">Python</span>
    <span class="chip">Scanpy</span>
    <span class="chip">AnnData</span>
  </div>
  <a class="overview-link" href="#scanpy-overview">Quick overview &#x2193;</a>
  <div class="card-footer">
    <a href="#">View repo &rarr;</a>
  </div>
  </div>

  <div class="project-card">
  <h3>Machine Learning for Biological Data</h3>
  <p>Feature selection and predictive modelling applied to genomic datasets.</p>
  <span class="pill" data-status="progress">In Progress</span>
  <div class="chips">
    <span class="chip">Python</span>
    <span class="chip">scikit-learn</span>
    <span class="chip">Pandas</span>
  </div>
  <a class="overview-link" href="#ml-bio-overview">Quick overview &#x2193;</a>
  <div class="card-footer">
    <a href="#">View repo &rarr;</a>
  </div>
  </div>
-->

  </div>

  </section>

  <section id="skills">
  <h2>Skills</h2>

  <div class="skills-grid">

  <div class="skill-group">
  <h3>Python &middot; Data</h3>

  <span class="chip">pandas</span>
  <span class="chip">numpy</span>
  <span class="chip">scipy</span>
  <span class="chip">matplotlib</span>
  <span class="chip">seaborn</span>

  </div>

  <div class="skill-group">
  <h3>Python &middot; ML &amp; Bio</h3>

  <span class="chip">scikit-learn</span>
  <span class="chip">cobrapy</span>
  <span class="chip">scanpy</span>
  <span class="chip">streamlit</span>

  </div>

  <div class="skill-group">
  <h3>Bash Tools</h3>

  <span class="chip">gapseq</span>
  <span class="chip">samtools</span>
  <span class="chip">bowtie2</span>
  <span class="chip">fastqc</span>
  <span class="chip">fastp</span>

  </div>

  <div class="skill-group">
  <h3>Languages</h3>

  <ul>
  <li>Python</li>
  <li>SQL</li>
  <li>VBA</li>
  </ul>

  </div>

  </div>

  </section>

<section id="contact">
  <h2>Contact</h2>
  <p class="contact-invite">Open to roles in computational biology, bioinformatics, and research.</p>
  <a class="btn btn-primary" href="#" data-open-modal="contact-modal">Get in touch</a>
</section>

<!-- Contact modal -->
<div class="modal-overlay" id="contact-modal">
  <div class="modal-box">
    <a class="modal-close" href="#">&#x2715;</a>
    <h3>Get in touch</h3>
    <a class="btn btn-primary" href="mailto:biodatalab00@gmail.com">Email</a>
    <a class="btn" href="https://linkedin.com/in/yourprofile">LinkedIn</a>
    <a class="btn" href="https://github.com/yourusername">GitHub</a>
  </div>
</div>

<!-- Project summary modals — add one per card -->
<div class="modal-overlay" id="gempipe-overview">
  <div class="modal-box summary-box">
    <a class="modal-close" href="#">&#x2715;</a>
    <h3>gempipe</h3>
    <div class="summary-content">
      {% include_relative projects/gempipe_sum.md %}
    </div>
  </div>
</div>

</main>

<script>
document.querySelectorAll('[data-open-modal]').forEach(function(a){
  a.addEventListener('click', function(e){
    e.preventDefault();
    document.getElementById(a.dataset.openModal).classList.add('is-open');
  });
});
document.querySelectorAll('.modal-close').forEach(function(el){
  el.addEventListener('click', function(e){
    e.preventDefault();
    el.closest('.modal-overlay').classList.remove('is-open');
  });
});
document.querySelectorAll('.modal-overlay').forEach(function(overlay){
  overlay.addEventListener('click', function(e){
    if(e.target === overlay) overlay.classList.remove('is-open');
  });
});
</script>
