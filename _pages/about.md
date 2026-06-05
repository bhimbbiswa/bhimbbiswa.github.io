---
permalink: /
title: "Welcome!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
body {text-align: justify}
.research-cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 12px;
  margin: 1.5em 0 2em 0;
}
.rcard {
  border: 1px solid #9FE1CB;
  border-left: 4px solid #1D9E75;
  border-radius: 6px;
  padding: 0.9em 1em;
  background: #f7fdfb;
}
.rcard-title {
  font-size: 0.85em;
  font-weight: 700;
  color: #0F6E56;
  margin-bottom: 0.4em;
  text-transform: uppercase;
  letter-spacing: 0.04em;
}
.rcard p {
  font-size: 0.85em;
  color: #333;
  margin: 0;
  line-height: 1.5;
  text-align: left;
}
</style>

I am a Postdoctoral Research Associate at the <a href="https://pedicordlab.com" target="_blank" rel="noopener noreferrer">Pedicord Lab</a>, University of Cambridge, working at the intersection of computational metagenomics and gut-brain biology. My research programme centres on developing and deploying **population-scale shotgun metagenomics pipelines** — including reference database construction and rigorous benchmarking — to profile under-characterised components of the gut microbiome and link them to neurological and behavioural phenotypes.

I completed my PhD in 2024 at the <a href="https://sites.google.com/view/mgrl-koide-lab/home" target="_blank" rel="noopener noreferrer">Koide Lab</a>, National Institute of Genetics, Japan, where I identified a gut bacterium with causal effects on animal domestication behaviour in mice. This work resulted in a patent (<a href="https://worldwide.espacenet.com/patent/search/family/093589448/publication/WO2024242147A1?q=pn%3DWO2024242147A1" target="_blank" rel="noopener noreferrer">PCT/JP2024/018885</a>) and a licensing agreement with Morinaga Milk Industry.

My expertise spans both wet lab (molecular biology, microbiology, mouse behaviour phenotyping) and large-scale dry lab analysis (**metagenome assembly, genome binning, phylogenomics, HPC-scale pipeline development**). I have generated bacterial, viral, and eukaryotic metagenome-assembled genomes (MAGs) and built specialised reference datasets to support microbiome research.

<div class="research-cards">
  <div class="rcard">
    <div class="rcard-title">Eukaryotic Metagenomics</div>
    <p>Developing reference databases and benchmarked pipelines for profiling fungal and other eukaryotic components of the gut microbiome from shotgun sequencing data.</p>
  </div>
  <div class="rcard">
    <div class="rcard-title">HPC-Scale Pipeline Development</div>
    <p>Building reproducible, scalable Snakemake workflows for population-scale metagenomic analysis across tens of thousands of samples on HPC infrastructure.</p>
  </div>
  <div class="rcard">
    <div class="rcard-title">Gut–Brain Axis</div>
    <p>Investigating how gut microbial communities — bacterial and beyond — influence neurological and behavioural phenotypes in human cohorts and mouse models.</p>
  </div>
  <div class="rcard">
    <div class="rcard-title">Metagenome-Assembled Genomes</div>
    <p>Constructing and curating MAG catalogues from diverse host populations to expand reference databases for microbial ecology research.</p>
  </div>
</div>

Feel free to reach out for inquiries or collaborations: <a href="mailto:bbb27@cam.ac.uk">bbb27[at]cam.ac.uk</a>

*Keywords:* metagenomics; eukaryotic metagenomics; gut microbiome; pipeline development; reference database construction; MAGs; phylogenomics; gut-brain axis; behavioural genetics; tameness; *Limosilactobacillus reuteri*
