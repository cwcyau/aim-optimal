# AIM OPTIMAL

This is a repository for *Work Package 1: Cluster sequences and response to therapies in cMM* of NIHR-funded AIM OPTIMAL project led by University of Birmingham.

<figure>
  <p align="center">
    <img src="gfx/wp1a.png" alt="Trulli" style="width:70%">
  </p>
  <p align="center">
    
  </p>
</figure>
<figcaption align = "center" style="text-align:center"><b>Figure 1 - Schematic representation of WP1</b></figcaption>

## Objectives

**RQ1:** What are the trajectories of diseases within clusters, including sub-clinical and advanced phenotypes of the disease, measured as a continuum using biomarkers and physiological measurements of disease severity? (**Objective 1**)

**RQ2:** Does choice of prescribed medications reduce or increase risk of development of a subsequent disease or complication of an existing disease? (**Objective 2**)

**RQ3:** Can we develop risk prediction algorithms to allow us to identify: 1) the likely next disease; and 2) the best treatment option where there are multiple choices (e.g. best second line treatment, in diabetes or disease modifying anti-rheumatic drug in rheumatoid arthritis)? (**Objective 3**)

**RQ4:** Do acute clinical expressions (hyperglycaemia, delirium, TIA) and clinical data (increased granularity – features derived from images, electrophysiological findings, laboratory measurements) during hospital admissions and outpatient visits improve the predictive algorithms for future disease accumulation and therapeutic choice? (**Objective 4**)

## Methods

We will adopt a well-founded modelling approach that has recently become popularised for the characterisation of observational electronic medical record data15-20 . In such an approach, at any time point, each patient is associated with a “state” which denotes their history of (discrete) disease conditions, prescriptions, and biophysical measurements. These states will only be observed at a finite set of irregularly sampled time points and may be partially observed (e.g. disease conditions recorded but no biomarkers), or contain genuine missing entries (as supposed to measurements that were never taken). They are otherwise latent states which are unobserved. The state of each patient will be assumed to evolve over time according to an unknown law that we will learn from data. These temporal dynamics could be dependent on (near) static (gender, ethnicity) or time-varying (e.g. age, smoking status) covariates. The relative sparsity and irregular sampling of measurements in any individual means we must leverage large populations to infer the properties of these stochastic processes. Furthermore, critically for our work, there may exist different sub-groups (e.g. clusters, ethnic & deprivation groups) of patients that exhibit different time- evolution behaviours (Figure 1).



## Project Information

- [Team](team.md)
- [Work strands](strands.md)
- [Milestones](milestones.md)
