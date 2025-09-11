# ML-Tabular-Project
Predictions on lean body mass based on certain genes

# Problem Formulation


*To what extent can genetic variation (SNPs, polygenic scores) predict skeletal muscle phenotypes such as lean body mass, muscle fiber cross-sectional area, and strength, and how do these predictions differ by sex and enhancement status (natural vs. enhanced athletes)?*

**Why I chose the topic:**

* Muscle gain is central to health, sports performance, and aging (sarcopenia).
* Genetic predisposition explains *part* of why some people gain muscle more easily (“are high responders”).
* Understanding genetics–muscle links has social implications: fair play in sports (doping), personalised training, and preventative health for aging populations.
* A model that predicts predisposition could help design tailored fitness or medical interventions.

---

#  Proposition

I propose to:

* Build an ML model that predicts muscle-related phenotypes (e.g., handgrip strength, muscle CSA, lean mass) from genetic variants (SNPs / PRS) plus basic covariates (sex, age, body fat %).
* Evaluate feature importance: which SNPs / PRS contribute most to predictions.
* Explore subgroup analysis: *male vs female*, *natural vs enhanced (if dataset allows)*.
* Deliverable: a reproducible pipeline + report, possibly publishable as a pilot in exercise genomics (if suitable).