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
  <a class="btn btn-primary" href="#" data-open-modal="contact-modal">Get in touch</a>

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
  <div class="card-meta">
    <span class="pill" data-status="progress">In Progress</span>
    <div class="chips">
      <span class="chip">Python</span>
      <span class="chip">COBRApy</span>
    </div>
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
  <div class="card-meta">
    <span class="pill" data-status="live|progress|planned">Status</span>
    <div class="chips">
      <span class="chip">Tool</span>
    </div>
  </div>
  <a class="overview-link" href="#project-name-overview">Quick overview &#x2193;</a>
  <div class="card-footer">
    <a href="https://github.com/...">View repo &rarr;</a>
  </div>
  </div>

  <div class="project-card">
  <h3>Single-Cell Transcriptomics Analysis</h3>
  <p>Single-cell RNA sequencing analysis using Scanpy, including QC, clustering and cell-type annotation.</p>
  <div class="card-meta">
    <span class="pill" data-status="planned">Planned</span>
    <div class="chips">
      <span class="chip">Python</span>
      <span class="chip">Scanpy</span>
      <span class="chip">AnnData</span>
    </div>
  </div>
  <a class="overview-link" href="#scanpy-overview">Quick overview &#x2193;</a>
  <div class="card-footer">
    <a href="#">View repo &rarr;</a>
  </div>
  </div>

  <div class="project-card">
  <h3>Machine Learning for Biological Data</h3>
  <p>Feature selection and predictive modelling applied to genomic datasets.</p>
  <div class="card-meta">
    <span class="pill" data-status="progress">In Progress</span>
    <div class="chips">
      <span class="chip">Python</span>
      <span class="chip">scikit-learn</span>
      <span class="chip">Pandas</span>
    </div>
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
  <div class="contact-icons-row">

    <a class="contact-tile" href="mailto:biodatalab00@gmail.com">
      <span class="contact-icon">
        <svg viewBox="0 0 24 24" fill="currentColor"><path d="M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
      </span>
      <span class="contact-tile-label">Email</span>
    </a>

    <a class="contact-tile" href="https://linkedin.com/in/yourprofile" target="_blank" rel="noopener">
      <span class="contact-icon">
        <svg viewBox="0 0 24 24" fill="currentColor"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 0 1-2.063-2.065 2.064 2.064 0 1 1 2.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
      </span>
      <span class="contact-tile-label">LinkedIn</span>
    </a>

    <a class="contact-tile" href="https://github.com/yourusername" target="_blank" rel="noopener">
      <span class="contact-icon">
        <svg viewBox="0 0 24 24" fill="currentColor"><path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/></svg>
      </span>
      <span class="contact-tile-label">GitHub</span>
    </a>

    <a class="contact-tile" href="/assets/cv/CV.pdf" download>
      <span class="contact-icon">
        <svg viewBox="0 0 24 24" fill="currentColor"><path d="M19 9h-4V3H9v6H5l7 7 7-7zM5 18v2h14v-2H5z"/></svg>
      </span>
      <span class="contact-tile-label">Download CV</span>
    </a>

  </div>
</section>

<!-- Contact modal -->
<div class="modal-overlay" id="contact-modal">
  <div class="modal-box contact-box">
    <a class="modal-close" href="#">&#x2715;</a>
    <h3>Get in touch</h3>
    <p class="contact-modal-sub">Open to opportunities in computational biology and research</p>
    <div class="contact-rows">

      <a class="contact-row" href="mailto:biodatalab00@gmail.com">
        <span class="contact-icon">
          <svg viewBox="0 0 24 24" fill="currentColor" width="18" height="18"><path d="M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
        </span>
        <span class="contact-info">
          <span class="contact-label">Email</span>
          <span class="contact-handle">biodatalab00@gmail.com</span>
        </span>
        <span class="contact-arrow">&#x2192;</span>
      </a>

      <a class="contact-row" href="https://linkedin.com/in/yourprofile" target="_blank" rel="noopener">
        <span class="contact-icon">
          <svg viewBox="0 0 24 24" fill="currentColor" width="18" height="18"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 0 1-2.063-2.065 2.064 2.064 0 1 1 2.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
        </span>
        <span class="contact-info">
          <span class="contact-label">LinkedIn</span>
          <span class="contact-handle">linkedin.com/in/yourprofile</span>
        </span>
        <span class="contact-arrow">&#x2192;</span>
      </a>

      <a class="contact-row" href="https://github.com/yourusername" target="_blank" rel="noopener">
        <span class="contact-icon">
          <svg viewBox="0 0 24 24" fill="currentColor" width="18" height="18"><path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/></svg>
        </span>
        <span class="contact-info">
          <span class="contact-label">GitHub</span>
          <span class="contact-handle">github.com/yourusername</span>
        </span>
        <span class="contact-arrow">&#x2192;</span>
      </a>

      <a class="contact-row" href="/assets/cv/CV.pdf" download>
        <span class="contact-icon">
          <svg viewBox="0 0 24 24" fill="currentColor" width="18" height="18"><path d="M19 9h-4V3H9v6H5l7 7 7-7zM5 18v2h14v-2H5z"/></svg>
        </span>
        <span class="contact-info">
          <span class="contact-label">Curriculum Vitae</span>
          <span class="contact-handle">Download PDF</span>
        </span>
        <span class="contact-arrow">&#x2193;</span>
      </a>

    </div>
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
