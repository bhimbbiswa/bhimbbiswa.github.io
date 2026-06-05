diff --git a/_pages/about.md b/_pages/about.md
index c2f0baa..7b6e3d6 100644
--- a/_pages/about.md
+++ b/_pages/about.md
@@ -8,10 +8,13 @@ redirect_from:
   - /about.html
 ---
 <style> body {text-align: justify} </style>
-Hi! I'm a postdoctoral research associate at the <a href="https://pedicordlab.com" target="_blank" rel="noopener noreferrer" style="color:#3B528B;">Pedicord Lab</a>, University of Cambridge, UK. My research focuses on the gut-brain axis and its potential impacts on health and disease. I completed my PhD in 2024 from the <a href="https://sites.google.com/view/mgrl-koide-lab/home" target="_blank" rel="noopener noreferrer" style="color:#3B528B;">Koide Lab</a>, National Institute of Genetics, Japan, where I investigated how the gut microbiome can influence animal domestication using mice as a model.
 
-Throughout my research journey, I have developed expertise in both wet lab and dry lab techniques, with a particular emphasis on metagenomic analysis. In the wet lab, I specialise in molecular biology and microbiology, with extensive experience in various **mouse behaviour analyses** and phenotyping. My dry lab expertise includes advanced **metagenome analysis, genome assembly, phylogenomics, and analysis of behavioural data**, enabling me to extract and interpret complex biological insights from large-scale datasets. Additionally, I have successfully generated **bacterial** and **viral** metagenome-assembled genomes (**MAGs**) and developed specialised datasets to support microbiome and domestication research.
+I am a Postdoctoral Research Associate at the <a href="https://pedicordlab.com" target="_blank" rel="noopener noreferrer">Pedicord Lab</a>, University of Cambridge, working at the intersection of computational metagenomics and gut-brain biology. My research programme centres on developing and deploying **population-scale shotgun metagenomics pipelines** — including reference database construction and rigorous benchmarking — to profile under-characterised components of the gut microbiome and link them to neurological and behavioural phenotypes.
 
-Feel free to contact me for any inquiries or potential collaborations. You can reach me at <a href="mailto:bbb27@cam.ac.uk" style="color:#3B528B;">bbb27[at]cam.ac.uk</a><br>
-*Key words:*<br>
-metagenomics; microbiome; genomics; behavioural genetics; tameness; gut-brain axis; *Limosilactobacillus reuteri*
+I completed my PhD in 2024 at the <a href="https://sites.google.com/view/mgrl-koide-lab/home" target="_blank" rel="noopener noreferrer">Koide Lab</a>, National Institute of Genetics, Japan, where I identified a gut bacterium with causal effects on animal domestication behaviour in mice. This work resulted in a patent (<a href="https://patents.google.com/patent/WO2024242147" target="_blank" rel="noopener noreferrer">PCT/JP2024/018885</a>) and a licensing agreement with Morinaga Milk Industry.
+
+My expertise spans both wet lab (molecular biology, microbiology, mouse behaviour phenotyping) and large-scale dry lab analysis (**metagenome assembly, genome binning, phylogenomics, HPC-scale pipeline development**). I have generated bacterial, viral, and eukaryotic metagenome-assembled genomes (MAGs) and built specialised reference datasets to support microbiome research.
+
+Feel free to reach out for inquiries or collaborations: <a href="mailto:bbb27@cam.ac.uk">bbb27[at]cam.ac.uk</a>
+
+*Keywords:* metagenomics; eukaryotic metagenomics; gut microbiome; pipeline development; reference database construction; MAGs; phylogenomics; gut-brain axis; behavioural genetics; tameness; *Limosilactobacillus reuteri*
diff --git a/_sass/_masthead.scss b/_sass/_masthead.scss
index b7ddcea..edac743 100644
--- a/_sass/_masthead.scss
+++ b/_sass/_masthead.scss
@@ -5,6 +5,13 @@
 .masthead {
   position: relative;
   border-bottom: 1px solid $border-color;
+
+  &::after {
+    content: '';
+    display: block;
+    height: 3px;
+    background: linear-gradient(90deg, #1D9E75 0%, #534AB7 100%);
+  }
   -webkit-animation: intro 0.3s both;
           animation: intro 0.3s both;
   -webkit-animation-delay: 0.15s;
diff --git a/_sass/_variables.scss b/_sass/_variables.scss
index c584e78..c39916a 100644
--- a/_sass/_variables.scss
+++ b/_sass/_variables.scss
@@ -60,11 +60,11 @@ $code-background-color-dark : $light-gray;
 $text-color                 : $dark-gray;
 $border-color               : $lighter-gray;
 
-$primary-color              : #7a8288;
+$primary-color              : #1D9E75;
 $success-color              : #62c462;
 $warning-color              : #f89406;
 $danger-color               : #ee5f5b;
-$info-color                 : #52adc8;
+$info-color                 : #0F6E56;
 
 /* brands */
 $behance-color              : #1769FF;
@@ -90,11 +90,11 @@ $xing-color                 : #006567;
 
 
 /* links */
-$link-color                 : $info-color;
-$link-color-hover           : mix(#000, $link-color, 25%);
-$link-color-visited         : mix(#fff, $link-color, 25%);
-$masthead-link-color        : $primary-color;
-$masthead-link-color-hover  : mix(#000, $primary-color, 25%);
+$link-color                 : #1D9E75;
+$link-color-hover           : #0F6E56;
+$link-color-visited         : #5DCAA5;
+$masthead-link-color        : #1D9E75;
+$masthead-link-color-hover  : #0F6E56;
 
 
 /*
