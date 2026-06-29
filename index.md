---
layout: default
title: Home
---

<link rel="stylesheet" href="/assets/css/style.css">

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
  <a href="#contact">Get in touch</a>

</header>

<nav class="site-nav">
  <a href="#bridge">Bridge</a>
  <a href="#projects">Projects</a>
  <a href="#skills">Skills</a>
  <a href="#contact">Contact</a>
</nav>

<main>

  <section id="bridge">
  <h2>Bridge</h2>
  <p>Bioprocess engineering taught me to read biological systems under pressure — optimizing fermentation runs, designing controlled experiments, and translating batch data into process decisions. That training built a skill most computational pipelines lack: the ability to look at a statistical output and ask what it means for the organism, not just the model. I build workflows with that lens built in, so the results translate into actions, not just plots.</p>
  <p><strong>What I bring:</strong></p>
  <ul>
  <li>Experimental design experience that catches data quality problems before they reach the pipeline</li>
  <li>The biological grounding to interpret computational outputs in context — not just report them</li>
  <li>Industrial and research exposure across  fermentation, microbial systems, and omics</li>
  </ul>
  </section>


  <section id="projects">
  <h2>Projects</h2>

  <div class="project-card">
  <h3>gempipe</h3>
  <p>Manually discovering where a metabolic pathway is broken is painful. Gempipe provides the reactions that are causing the model to fail, shortening the discovery time from hours of manual search to minutes of automatic computing</p>
  <span class="pill" data-status="progress">In Progress</span>
  <div class="chips">
    <span class="chip">Python</span>
    <span class="chip">COBRApy</span>
  </div>
  <a href="#">View repo &rarr;</a>
  </div>

<!-- REST OF CARDS COMMENTED OUT

  <div class="project-card">
  <h3>Single-Cell Transcriptomics Analysis</h3>
  <p>
  Single-cell RNA sequencing analysis using Scanpy, including QC,
  clustering and cell-type annotation.
  </p>
  <p><strong>Status:</strong> Repository under preparation</p>
  <p><strong>Technologies:</strong> Python • Scanpy • AnnData</p>
  </div>

  <div class="project-card">
  <h3>Machine Learning for Biological Data</h3>
  <p>
  Feature selection and predictive modelling applied to genomic datasets.
  </p>
  <p><strong>Status:</strong> Active Development</p>
  <p><strong>Technologies:</strong> Python • scikit-learn • Pandas</p>
  </div>
-->
  </section>

  <section id="skills">
  <h2>Skills</h2>

  <div class="skills-grid">

  <div class="skill-group">
  <h3>Python Tools</h3>

  <span class="chip">pandas</span>
  <span class="chip">numpy</span>
  <span class="chip">matplotlib</span>
  <span class="chip">seaborn</span>
  <span class="chip">cobrapy</span>
  <span class="chip">scanpy</span>
  <span class="chip">scikit-learn</span>
  <span class="chip">scipy</span>
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

  <a class="btn btn-primary" href="mailto:your.email@gmail.com">Get in touch</a>
  <a class="btn" href="https://linkedin.com/in/yourprofile">LinkedIn</a>
  <a class="btn" href="https://github.com/yourusername">GitHub</a>

</section>

</main>

<footer></footer>
