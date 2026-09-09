---
permalink: /
title: ""
seo_title: "Bashar Emon, PhD"
description: "Bashar Emon, PhD, is a researcher in biomechanics, mechanobiology, MEMS, tumor microenvironment mechanics, and microphysiological systems at the University of Illinois Urbana-Champaign."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  table a:hover {
    color: var(--in-page-menu-hover-color);
  }

  /* Mobile only: allow the content navigation table to wrap */
  @media screen and (max-width: 767px) {
    .content-nav {
      display: block;
      width: 100%;
    }

    .content-nav tbody {
      display: block;
      width: 100%;
    }

    .content-nav tr {
      display: flex;
      flex-wrap: wrap;
      width: 100%;
      gap: 6px 18px;
    }

    .content-nav td {
      display: block;
      width: auto;
      padding: 4px 0 !important;
      white-space: nowrap;
    }
  }
</style>

<table class="content-nav" style="width:100%; border:0; border-collapse:separate;text-align:left;font-size:1.3em;font-weight:bold;">
  <tr>
    <td style="border:0; border-style:none;"><a href="/about/">Home | Research</a></td>
    <td style="border:0; border-style:none;"><a href="/publications/">Publications</a></td>
    <td style="border:0; border-style:none;"><a href="/talks/">Talks</a></td>
    <td style="border:0; border-style:none;"><a href="/teaching/">Teaching</a></td>
    <td style="border:0; border-style:none;"><a href="/portfolio/">Awards</a></td>
    <td style="border:0; border-style:none;"><a href="/cv/">CV</a></td>
    <td style="border:0; border-style:none;"><a href="/contact/">Contact</a></td>
  </tr>
</table>

overview 
------
At the intersection of mechanics and medicine, my research draws inspiration from the physical forces that underpin the rules of life. Trained in both theoretical and experimental mechanics, I explore how forces, stiffness, and microstructure govern cell and tissue behavior in both health and disease. My work uncovers how mechanical forces control cellular signaling, how the tumor microenvironment (TME) evolves biomechanically, and how these insights can be leveraged to develop technologies for diagnostics, therapeutics, and personalized medicine. I use tools from mechanobiology, microfabrication, and machine learning to drive this scientific pursuit. 

<div style="display: flex; justify-content: space-around; gap: 20px; margin-bottom: 2rem; flex-wrap: wrap; text-align: center;">

  <div>
    <div><strong>Innovation</strong></div>
    <a href="#innovation">
      <img src="/images/CAF force timelapse.gif" alt="innovation"
           style="height: 150px; width: auto; object-fit: contain; border-radius: 12px;">
    </a>
  </div>

  <div>
    <div><strong>Mechanotransduction</strong></div>
    <a href="#mechanotransduction">
      <img src="/images/YAP animation_3.gif" alt="mechanotransduction"
           style="height: 150px; width: auto; object-fit: contain; border-radius: 12px;">
    </a>
  </div>

  <div>
    <div><strong>Neuromechanics</strong></div>
    <a href="#neuromechanics">
      <img src="/images/Neuron actin.gif" alt="neuromechanics"
           style="height: 150px; width: auto; object-fit: contain; border-radius: 12px;">
    </a>
  </div>

  <div>
    <div><strong>Translation</strong></div>
    <a href="#translation">
      <img src="/images/Translation_image.png" alt="translation"
           style="height: 150px; width: auto; object-fit: contain; border-radius: 12px;">
    </a>
  </div>

</div>



<div id="innovation" style="position: relative; top: -60px;"></div>
## <a name="innovation"></a>innovation

During my PhD, under the guidance of Professor Taher Saif, I developed a microfabricated force sensor that addresses a long-standing problem in cell/tissue mechanics: the inability to measure cellular forces in 3D microenvironments that evolve mechanically with time. Unlike traditional 2D traction force microscopy, this platform enables direct quantification of single- and multi-cellular forces in self-assembled 3D tissues with nanonewton resolution, alongside simultaneous readouts of matrix stiffening. These sensors have been employed to uncover dynamic mechanical interactions between cancer cells and stromal fibroblasts, revealing a feedback mechanism that promotes tumor invasion and remodeling of the extracellular matrix (ECM). Published in <a href="https://www.science.org/doi/10.1126/sciadv.abf2629" target="_blank">Science Advances</a> & 
<a href="https://www.nature.com/articles/s41596-024-01106-8" target="_blank">Nature Protocols</a>, this platform lays the foundation for biomechanical assays, drug screening, and ultimately mechanics-informed precision therapies. 

<div style="
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 00px;
  padding: 00px;
  flex-wrap: wrap;
">

  <img src="/images/Sensor_force_SEM.png"
       alt="Force sensor"
       style="
         border-radius: 6px;
         opacity: 0.9;
         height: 350px;
         max-width: 120%;
         -webkit-mask-image: 
           linear-gradient(to bottom, transparent 0%, black 25%, black 85%, transparent 100%),
           linear-gradient(to right, transparent 0%, black 30%, black 90%, transparent 100%);
         -webkit-mask-composite: destination-in;
         mask-image: 
           linear-gradient(to bottom, transparent 0%, black 15%, black 85%, transparent 100%),
           linear-gradient(to right, transparent 0%, black 10%, black 90%, transparent 100%);
         mask-composite: intersect;
       ">

  <img src="/images/CAF force timelapse.gif"
       alt="CAF force timelapse"
       style="
         border-radius: 20px;
         opacity: 0.9;
         width: 670px;
         max-width: 100%;
         margin-left: 15px;
       ">
</div>


<div id="mechanotransduction" style="position: relative; top: -40px;"></div>
## <a name="mechanotransduction"></a>mechanotransduction

<!-- Image column floats right -->
<div style="float: right; margin-left: 20px; margin-top: 15px; display: flex; flex-direction: column; gap: 10px; align-items: flex-end;">

  <img src="/images/YAP animation_3.gif"
       alt="YAP activation"
       style="width: 320px; border-radius: 12px;" />

  <img src="/images/Actin_dapi_3D_final_crop.gif"
       alt="Actin 3D"
       style="width: 320px; border-radius: 12px;" />
</div>


My research has revealed that mechanical signaling, not just chemical cues, plays a critical role in cancer cell migration and metastasis <a href="https://www.nature.com/articles/s41598-025-89152-4" target="_blank">(Scientific Reports)</a>. I demonstrated that CAF (cancer-associated fibroblast) contractility drives alignment of ECM fibers and stiffening and of the TME, inducing nuclear deformation which activates Yes-Associated Protein (YAP), a mechanosensitive transcription co-activator <a href="https://doi.org/10.1016/j.actbio.2023.11.015" target="_blank">(Acta Biomaterialia)</a>. Activation of YAP upregulates genes linked to pro-metastatic behavior, including <a href="https://www.nature.com/articles/s41598-019-55687-6" target="_blank">Activin A</a>, a cytokine that further enhances invasion by the cancer cells. 

Other highlights of my work include:

* Determining illumination/fluorescence intensity thresholds for live-cell imaging to prevent phototoxic artifacts <a href="https://doi.org/10.1016/j.eml.2021.101249" target="_blank">(Extreme Mechanics Letters)</a>.
* Publishing a transcriptomic dataset of mechanosensitive CAFs, linking force-driven matrix stiffening to gene expression <a href="https://www.nature.com/articles/s41597-023-02233-9" target="_blank">(Scientific Data)</a>.
* Establishing traction as a cytotoxicity readout - I demonstrated that cell traction measurements can serve as an early, sensitive metric of cytotoxic response, often preceding morphological changes, thereby enabling force-based toxicity screening that complements viability and biochemical assays <a href="https://pubs.acs.org/doi/full/10.1021/acsnano.8b04513" target="_blank">(ACS Nano</a> & <a href="https://www.nature.com/articles/s41928-022-00791-1" target="_blank">Nature Electronics)</a>.

Collectively, these findings build a mechanistic framework for how forces shape cell behavior and tumor progression, opening new avenues for clinical translation. 



<div id="neuromechanics" style="position: relative; top: -60px;"></div>
## <a name="translation"></a>neuromechanics

In a recent collaboration published in <a href="https://www.pnas.org/doi/10.1073/pnas.2311995120" target="_blank">PNAS</a>, we discovered that neuronal contractility is essential for synaptic firing. Using a 3D hippocampal neuron network cultured on a nanonewton-resolution force sensor, we found that neurons generate tension upon forming synapses—and this mechanical tension directly supports their ability to fire. Disrupting contractility caused a ~90% reduction in activity, which reversed upon restoring force, indicating that tension is not just a byproduct, but a requirement for synaptic transmission.
This work also revealed that contractility promotes vesicle clustering at presynaptic terminals, further supporting its role in synaptic readiness. These findings introduce a new mechanistic paradigm: neurons need physical tension to communicate, with implications for neurodevelopment, learning, and disorders where mechanical integrity is compromised.

<div style="display: flex; gap: 20px; margin-top: 20px; align-items: flex-start;">

  <!-- Left column: main image -->
  <div style="flex: 2; position: relative;">
    <img src="/images/Neuron actin.gif"
         alt="neuromechanics"
         style="width: 100%; border-radius: 12px;" />
    <div style="position: absolute; bottom: 10px; left: 10px; 
                background: rgba(0,0,0,0.6); color: #fff; 
                padding: 5px 10px; border-radius: 6px; font-size: 1rem;">
      Actin dynamics in neurons on the sensor
    </div>
  </div>

  <!-- Right column: stacked images -->
  <div style="flex: 1; display: flex; flex-direction: column; gap: 20px;">
    
    <div style="position: relative;">
      <img src="/images/Neuron firing.gif"
           alt="firing"
           style="width: 94%; border-radius: 12px;" />
      <div style="position: absolute; bottom: 10px; left: 10px; 
                  background: rgba(0,0,0,0.6); color: #fff; 
                  padding: 5px 10px; border-radius: 6px; font-size: 0.85rem;">
        Firing with tension
      </div>
    </div>

    <div style="position: relative;">
      <img src="/images/Neuron firing_no force.gif"
           alt="firing_no_force"
           style="width: 94%; border-radius: 12px;" />
      <div style="position: absolute; bottom: 10px; right: 30px; 
                  background: rgba(0,0,0,0.6); color: #fff; 
                  padding: 5px 10px; border-radius: 6px; font-size: 0.85rem;">
        Firing w/o tension
      </div>
    </div>

  </div>
</div>



<div id="translation" style="position: relative; top: -20px;"></div>
## <a name="translation"></a>mechanics for personalized medicine

Looking ahead, I envision an interdisciplinary research program that uses mechanics to understand disease, identify predictive biomechanical signatures, and develop technologies for personalized diagnosis and therapy. My future work will center on three interconnected directions:

### 1. Mechanobiology of Disease

I aim to uncover how physical forces, tissue mechanics, and extracellular matrix remodeling regulate disease progression. In cancer, I will investigate how cellular contractility, nuclear deformation, and matrix architecture influence invasion and metastasis. These studies will extend to complex disease models such as **glioblastoma-on-a-chip**, where engineered brain-like microenvironments can reveal how astrocyte contractility, ECM remodeling, and blood-brain-barrier mechanics regulate tumor dissemination.

### 2. Mechanics-Based Diagnostics and Therapeutics

A major goal of my research is to translate biomechanical measurements into clinically actionable tools. By integrating tumor histology, tissue mechanics, and machine learning, I will identify mechanical signatures, such as nuclear strain, tissue stiffness, cellular force, and fiber architecture, that predict disease progression and therapeutic response. I refer to these predictive mechanical signatures as **mechanomarkers**. In parallel, I will develop **force-targeted therapeutic strategies**, including approaches that suppress pathological cell contractility or decouple nuclear deformation from cytoskeletal force, to test whether disrupting the mechanical drivers of disease can limit invasion and metastasis.

### 3. Engineered Living Systems and Biomechanical Technologies

To enable these studies at scale, I will develop next-generation platforms for measuring and manipulating mechanics in living tissues. **High-throughput MEMS sensor arrays** will provide automated measurements of force, stiffness, remodeling, and other mechanomarkers in patient-derived tissues, creating opportunities for drug screening and personalized treatment selection. Over the longer term, I envision extending these technologies toward **implantable and biohybrid systems**, including sensors integrated with iPSC-derived muscle actuators and wearable or implantable devices capable of monitoring mechanical and physiological signals in vivo.

Together, these directions establish a unified framework in which fundamental mechanobiology informs new diagnostic markers and therapeutic strategies, while advanced sensing technologies provide the tools needed to translate mechanical insight toward personalized medicine.

<div style="display: flex; gap: 20px; margin-top: 20px; align-items: flex-start;">

  <div style="flex: 2; position: relative; display: flex; justify-content: center;">
    <img src="/images/Translation_thumb_v2.gif"
         alt="Translation"
         style="width: 95%; border-radius: 12px; 
         -webkit-mask-image: 
           linear-gradient(to bottom, transparent 0%, black 4%, black 96%, transparent 100%),
           linear-gradient(to right, transparent 0%, black 4%, black 96%, transparent 100%);
         -webkit-mask-composite: destination-in;
         mask-image: 
           linear-gradient(to bottom, transparent 0%, black 4%, black 96%, transparent 100%),
           linear-gradient(to right, transparent 0%, black 4%, black 96%, transparent 100%); 
         mask-composite: intersect;" />
    <div style="position: absolute; bottom: 10px; left: 05%; 
                color: #ccc; 
                padding: 5px 10px; border-radius: 6px; font-size: .8rem;">
      mechanics-informed medicine
    </div>
  </div>
</div>


### Selected Publications

<div style="font-size:0.9em;" markdown="1">
  
**Biomechanical 3D tumor models on a micro-milled high-throughput force sensor array**  
Emon, B. et al., **Biofabrication**, 18, 025015 (2026). https://doi.org/10.1088/1758-5090/ae5347

**A multifunctional sensor for cell traction force, matrix remodeling and biomechanical assays in self-assembled 3D tissues in vitro**  
Emon, B et al., **Nature Protocols**, 20, 2005–2033 (2025) . https://doi.org/10.1038/s41596-024-01106-8

**Nuclear deformation regulates YAP dynamics in cancer associated fibroblasts**  
Emon, B. et al., **Acta Biomaterialia**, 173, 93–108 (2024). https://doi.org/10.1016/j.actbio.2023.11.015

**A novel method for sensor-based quantification of single/multi-cellular traction dynamics and remodeling in 3D matrices**  
Emon, B. et al., **Science Advances**, 7(15), eabf2629 (2021). https://doi.org/10.1126/sciadv.abf2629

**Dose-independent threshold illumination for non-invasive time-lapse fluorescence imaging of live cells**  
Emon, B. et al., **Extreme Mechanics Letters**, 46, 101249 (2021). https://doi.org/10.1016/j.eml.2021.101249

</div>


<!-- Looking ahead, I envision a research program that leverages biomechanical insight to drive transformative advances in medicine. Key goals include:
* **Mechanomarkers for Prognostics**  
  Using machine learning on tumor histology and mechanical profiles, I aim to identify mechanical signatures (nuclear strain, stiffness, fiber architecture) that predict metastatic potential - a class of diagnostic tools I term “mechanomarkers”.

* **Force-Targeted Therapies**  
  Through contractility-inhibiting devices and CRISPR-based tools to decouple nuclear deformation from cytoskeletal force, I plan to test new ways to interrupt the physical drivers of metastasis.

* **Glioblastoma-on-a-Chip**  
  Modeling the brain's biomechanical environment will allow exploration of how astrocyte contractility and ECM remodeling influence glioblastoma spread across the blood-brain barrier.

* **High-Throughput MEMS Sensors**  
  A sensor array system will enable automated measurements of biomechanical indicators (mechanomarkers!) for drug screening in patient-derived tissues. These platforms can feed into real-time clinical decision tools and customized treatment planning.
  
* **Biohybrid Systems and Wearables**  
  My long-term vision includes implantable MEMS devices and biohybrid sensors using iPSC-derived muscle actuators, capable of monitoring real-time force and physiological cues in vivo, bringing mechanical insight directly into the clinic.  -->



<!-- Sensor to measure cell force in 3D matrices. 
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



Ways to add figures here.... 
======
1. <img src="/images/sensor_force_1.png" alt="Force sensor" style="border-radius: 25px; opacity: 1; max-width: 100%;"> 
2. [Profile photo](/images/profile.png) -->
