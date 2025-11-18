---
title: Research
nav:
  order: 1
  tooltip: Learn about our research
---

# {% include icon.html icon="fa-solid fa-flask-vial" %}Research

At Neurone Lab we study computation across biological and artificial systems, aiming to understand how structure, dynamics, and information flow give rise to intelligent behaviour. We also use computational and data-driven methods to analyse biological processes and images, helping biologists interpret complex data and uncover mechanistic insights that are difficult to access through experimental techniques alone. Our work brings together machine learning, computational biology, advanced microscopy, and neuroscience to explore shared principles of learning and representation. 

Our research spans integrating ideas from natural systems into artificial intelligence systems and the analysis of complex biological datasets. We work with multi-scale data, including single-cell omics from cancer studies, large collections of label-free cellular images, and high-resolution microscopy modalities such as ptychography. This integrated perspective allows us to link structure, function, and computation while developing algorithms, analysis pipelines, and benchmarks that support both biological discovery and technological innovation. Our interdisciplinary approach connects fundamental research with real-world applications across biology and medicine.


{% capture text %}

To  bridge molecular mechanisms of cis regulation to developmental phenotypic consequences, we combine _in vivo_ embryology with _in vitro_ cellular models that recapitulate the same cell fate decisions. Our favourite model system is the developing spinal cord, where a small combination of signals directs the specification of neural progenitors and therefore which neurons they will make. 

{% endcapture %}

{%
  include feature.html
  image="images/Research_all-02.png"
  text=text
%}

{% capture text %}

We use a variety of novel genomics and computational methods, developing new approaches when needed to answer the questions. Our current projects include state-of-the art proteomics and microscopy approaches to address the mechanistic principles of how cis-regulatory elements control cell fate choice between neural progenitors.

{%
  include button.html
  link="publications"
  text="Read more"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Research_all-01.png"
  link="publications"
  flip=true
  style="bare"
  text=text
%}



{% include tags.html tags="publication, resource, website" %}


{% include section.html %}

## Resources

{% include list.html component="card" data="projects" filters="group: featured" style="small" %}

{% include section.html %}

<!---
## More

{% include list.html component="card" data="projects" filters="group: " style="small" %}
-->