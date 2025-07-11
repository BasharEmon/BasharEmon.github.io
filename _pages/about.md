---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  table a:hover {
    color: var(--in-page-menu-hover-color);
  }
</style>

<table style="width:100%; border:0; border-collapse:separate;text-align:left;font-size:1.3em;font-weight:bold;">
  <tr>
    <td style="border:0; border-style:none;"><a href="/about/">Home/Research</a></td>
    <td style="border:0; border-style:none;"><a href="/publications/">Publications</a></td>
    <td style="border:0; border-style:none;"><a href="/talks/">Talks</a></td>
    <td style="border:0; border-style:none;"><a href="/teaching/">Teaching</a></td>
    <td style="border:0; border-style:none;"><a href="/portfolio/">Awards</a></td>
    <td style="border:0; border-style:none;"><a href="/cv/">CV</a></td>
    <td style="border:0; border-style:none;"><a href="/contact/">Contact</a></td>
  </tr>
</table>

Overview 
------
At the intersection of mechanics and medicine, my research draws inspiration from the physical forces that underpin the rules of life. Trained in both theoretical and experimental mechanics, I explore how forces, stiffness, and microstructure govern cell and tissue behavior in both health and disease. My work uncovers how physical forces control cellular signaling, how the tumor microenvironment (TME) evolves biomechanically, and how these insights can be leveraged to develop technologies for diagnostics, therapeutics, and personalized medicine. I use tools from mechanobiology, microfabrication, and machine learning to drive this scientific pursuit. 

<div style="display: flex; justify-content: space-around; gap: 20px; margin-bottom: 2rem;">

  <a href="#innovation">
    <img src="/images/CAF force timelapse.gif" alt="innovation" style="height: 150px; width: auto; object-fit: contain; border-radius: 12px;">     <!-- Sensor_force_SEM_crop.png -->
  </a>

  <a href="#mechanotransduction">
    <img src="/images/YAP animation_3.gif" alt="mechanotransduction" style="height: 150px; width: auto; object-fit: contain; border-radius: 12px;">
  </a>

  <a href="#neuromechanics">
    <img src="/images/YAP animation_3.gif" alt="neuromechanics" style="height: 150px; width: auto; object-fit: contain; border-radius: 12px;">
  </a>

  <a href="#translation">
    <img src="/images/Actin_dapi_3D_final.gif" alt="translation" style="height: 150px; width: auto; object-fit: contain; border-radius: 12px;">
  </a>

</div>


<div id="innovation" style="position: relative; top: -60px;"></div>
## <a name="innovation"></a>innovation

I developed a microfabricated 3D tissue sensor that addresses a long-standing problem in cell mechanics: the inability to measure cellular forces in 3D microenvironments. Unlike traditional 2D traction force microscopy, this platform enables direct quantification of single- and multicellular forces in self-assembled 3D tissues with nanonewton resolution, alongside simultaneous readouts of matrix stiffening. These sensors have been used to uncover dynamic mechanical interactions between cancer cells and stromal fibroblasts, revealing a feedback loop that promotes tumor invasion and remodeling of the extracellular matrix (ECM). Published in [Science Advances](https://www.science.org/doi/10.1126/sciadv.abf2629) & [Nature Protocols](https://www.nature.com/articles/s41596-024-01106-8), this platform lays the foundation for biomechanical assays, drug screening, and ultimately mechanics-informed precision therapies.

<div style="text-align: center; padding: 20px;">
  <img src="/images/Sensor_force_SEM.png"
       alt="Force sensor"
       style="
         border-radius: 6px;
         opacity: 0.9;
         max-width: 120%;
         height: 350px;
         -webkit-mask-image: 
           linear-gradient(to bottom, transparent 0%, black 25%, black 85%, transparent 100%),
           linear-gradient(to right, transparent 0%, black 30%, black 90%, transparent 100%);
         -webkit-mask-composite: destination-in;
         mask-image: 
           linear-gradient(to bottom, transparent 0%, black 15%, black 85%, transparent 100%),
           linear-gradient(to right, transparent 0%, black 10%, black 90%, transparent 100%);
         mask-composite: intersect;
       ">
</div>

 
<div id="mechanotransduction" style="position: relative; top: -60px;"></div>
## <a name="mechanotransduction"></a>mechanotransduction

My research has revealed that mechanical signaling, not just chemical cues, plays a dominant role in cancer cell migration and metastasis. I showed that CAF (cancer-associated fibroblast) contractility drives stiffening of the ECM and induces nuclear deformation in cancer cells, which activates YAP, a mechanosensitive transcription co-activator. This activation upregulates genes linked to pro-metastatic behavior, including Activin A, a cytokine that further enhances invasion. Additional work published in Scientific Data and Extreme Mechanics Letters includes:
* Defining thresholds for phototoxicity in live-cell imaging
* Transcriptomic changes in mechanosensitive CAFs
* Mapping fiber alignment under mechanical strain
These findings help build a framework for understanding how physical forces regulate gene expression, migration, and tumor progression.

<img src="/images/YAP animation_3.gif" alt="translation">


<div id="neuromechanics" style="position: relative; top: -60px;"></div>
## <a name="translation"></a>neuromechanics

In our recent PNAS study, we discovered that neuronal contractility is essential for synaptic firing. Using a 3D hippocampal neuron network cultured on a nanonewton-resolution force sensor, we found that neurons generate tension upon forming synapses—and this mechanical tension directly supports their ability to fire. Disrupting contractility caused a ~90% reduction in activity, which reversed upon restoring force, indicating that tension is not just a byproduct, but a requirement for synaptic transmission.
This work also revealed that contractility promotes vesicle clustering at presynaptic terminals, further supporting its role in synaptic readiness. These findings introduce a new mechanistic paradigm: neurons need physical tension to communicate, with implications for neurodevelopment, learning, and disorders where mechanical integrity is compromised.

<img src="/images/Actin_dapi_3D_final.gif" alt="mechanotransduction" style="height: 450px;">


<div id="translation" style="position: relative; top: -60px;"></div>
## <a name="translation"></a>mechanics for personalized medicine

Looking ahead, I envision a research program that transforms biomechanics from a basic science tool into a clinical decision-making platform. Key goals include:
* Mechanomarkers for Prognostics <br>
Using machine learning on tumor histology and mechanical profiles, I aim to identify mechanical signatures (nuclear strain, stiffness, fiber architecture) that predict metastatic potential — a class of diagnostic tools I term “mechanomarkers”
* Force-Targeted Therapies <br>
By developing contractility-inhibiting devices and using CRISPR-based tools to decouple nuclear deformation from cytoskeletal force, I will test new ways to interrupt the physical drivers of metastasis.
* Glioblastoma-on-a-Chip <br>
I will model the brain's biomechanical environment, exploring how astrocyte contractility and ECM remodeling influence glioblastoma spread across the blood-brain barrier
* High-Throughput MEMS Sensors <br>
I aim to design a sensor array system compatible with 96-well formats to enable automated force measurements for drug screening in patient-derived tissues. These platforms will feed into real-time clinical decision tools and customized treatment planning
* Biohybrid Systems and Wearables <br>
My long-term vision includes implantable MEMS devices and biohybrid sensors using iPSC-derived muscle actuators, capable of monitoring real-time force and physiological cues in vivo, bringing mechanical insight directly into the clinic.

<img src="/images/Actin_dapi_3D_final.gif" alt="mechanotransduction" style="height: 450px;">


Sensor to measure cell force in 3D matrices. 
------
Description of the sensor and image below in italic. 
<div style="text-align: center; padding: 20px;">
  <img src="/images/Sensor_force_SEM.png"
       alt="Force sensor"
       style="
         border-radius: 6px;
         opacity: 0.9;
         max-width: 120%;
         height: 350px;
         -webkit-mask-image: 
           linear-gradient(to bottom, transparent 0%, black 25%, black 85%, transparent 100%),
           linear-gradient(to right, transparent 0%, black 30%, black 90%, transparent 100%);
         -webkit-mask-composite: destination-in;
         mask-image: 
           linear-gradient(to bottom, transparent 0%, black 15%, black 85%, transparent 100%),
           linear-gradient(to right, transparent 0%, black 10%, black 90%, transparent 100%);
         mask-composite: intersect;
       ">
</div>



In addition, this sensor platform can simultaneously monitor/measure the evolution of matrix mechanical properties, and test drug efficacy in cancer treatment. This method marks a significant advancement in the field as this platform solved a long-standing problem of directly measuring force dynamics in an active matrix, which mimics in vivo mechanical microenvironment. 

My long-term goal is to apply cell and tissue mechanics to develop therapeutic strategies and design innovative medical devices that can transform patient care. I am eager to establish interdisciplinary collaborations and expand my research by exploring the role of cell contractility, local stress and matrix mechanical properties in fundamental cell functions. I aim to uncover significant clinical insights and develop translational technologies that apply engineering mechanics to medical applications. 

During my PhD, under the supervision of Professor Taher Saif, I developed a novel experimental platform that allows, for the first time, measuring single cell forces in 3D matrices and forming in vitro tumors with primary cancer cells and stromal cells that assist the cancer cells (published in [Science Advances](https://www.science.org/doi/10.1126/sciadv.abf2629) & [Nature Protocols](https://www.nature.com/articles/s41596-024-01106-8)). Cell forces could only be measured for cells on a 2D soft elastic substrate from the substrate deformation. However, cells in organs are in a 3D environment. Cell forces in 3D matrices could not be measured due to non-linearity and/or local remodeling of the matrix. I overcame this limitation by inventing a sensor platform that takes advantage of force balance to measure cell-generated forces. 



<!-- Ways to add figures here.... 
======
1. <img src="/images/sensor_force_1.png" alt="Force sensor" style="border-radius: 25px; opacity: 1; max-width: 100%;"> 
2. [Profile photo](/images/profile.png) -->
