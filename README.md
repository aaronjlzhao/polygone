# Project Overview
This project leverages synthetic biology to address plastic pollution by engineering Escherichia coli to degrade polyethylene terephthalate (PET), a durable plastic causing environmental harm. Our genetic circuit breaks PET into ethylene glycol (EG) and terephthalic acid (TPA), then converts toxic EG into safe byproducts (malate and coenzyme A), offering a sustainable solution for waste management with applications in biomedical engineering and pharmaceutical packaging.
Problem Statement
PET's slow degradation (2,500-year half-life) contributes to 79% of the 6.3 billion tons of plastic waste in landfills or ecosystems (2015–2020). Microplastics pose risks to biodiversity and human health, including reproductive and hormonal issues. Current microbial solutions produce toxic EG, limiting their efficacy. Our system enhances PET degradation and eliminates EG toxicity.
Objectives

# Design a genetic circuit to detect PET byproducts and produce degradation enzymes.
Metabolize EG into non-toxic malate and CoA.
Achieve PET degradation 10^6 times faster than natural processes.
Validate circuit performance via modeling and in vitro tests.

# Technical Approach
Genetic Circuit
- Detection: Two AND gates detect PET byproducts (phthalates, alkanes), producing T7 RNA polymerase.
- PET Degradation: Enzymes PETase and MHETase break PET into EG and TPA.
- EG Metabolism: Enzymes (glycolaldehyde reductase, dehydrogenase, glycolate oxidase, malate synthase) convert EG to malate and CoA.

# Implementation
Assembly: Golden Gate assembly with BsaI-HFv2 and T4 DNA ligase for scarless DNA ligation.
Plasmids: Four plasmids (pSB1A3, pSB3K3, pSB4C5, pBBR1) ensure compatibility.
Testing: In vitro experiments in M9 medium with PET and activators measure CO2, pyruvate, and pH to confirm degradation.
Modeling: MATLAB Simbiology simulates enzyme kinetics and degradation rates.

# Results
Efficient PET breakdown into EG and TPA, surpassing natural degradation rates.
EG conversion to malate and CoA, with bottlenecks in downstream efficiency.
Simulations confirm circuit functionality, though EG degradation needs optimization.

# Relevance to Biomedical Engineering
Sustainable Packaging: Enables eco-friendly pharmaceutical packaging degradation.
Health Safety: Reduces microplastic-related health risks (e.g., hormonal imbalances).
Biotechnology: Showcases synthetic biology for sustainable bioprocessing.

# Future Directions
Optimize EG degradation via enzyme expression tuning.
Develop universal promoters for broader PET applicability.
Scale for industrial bioremediation and pharmaceutical waste management.

# Tools and Technologies
Molecular Biology: Golden Gate assembly, PCR, electroporation.
Bioinformatics: MATLAB Simbiology.
Biological Parts: iGEM BioBricks (e.g., BBa_K808000, BBa_K4290022).

