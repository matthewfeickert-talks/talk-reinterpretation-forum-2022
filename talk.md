class: middle, center, title-slide
count: false

# Overview of Publishing Statistical Models

.huge.blue[Matthew Feickert]<br>
.large[(University of Wisconsin-Madison)]
<br>
[matthew.feickert@cern.ch](mailto:matthew.feickert@cern.ch)


[Reinterpretation Forum Workshop 2022](https://indico.cern.ch/event/1197680/contributions/5160805/)
<br>
December 13th, 2022

---
# Starting with the important information

.center.large.bold[Start publishing full statistical models now]

.kol-1-2.large[

.center.width-100[[![recommendation-tall](figures/recommendation-tall.png)](https://inspirehep.net/literature/1919763)]
<!-- .center.width-100[[![full-model-recommendation](figures/full-model-recommendation.png)](https://inspirehep.net/literature/1919763)] -->

.center.large[[Publishing statistical models: Getting the most out of particle physics experiments](https://inspirehep.net/literature/1919763)]
]
.kol-1-2[

.center.width-100[[![snowmass-recommendations](figures/snowmass-recommendations.png)](https://inspirehep.net/literature/2054747)]

.center[[Data and Analysis Preservation, Recasting, and Reinterpretation](https://inspirehep.net/literature/2054747) (Snowmass 2022 whitepaper)]
.center[[Reinterpretation and Long-Term Preservation of Data and Code](https://inspirehep.net/literature/2153139) (Snowmass 2022 recommendations)]
]

---
# Why is the full statistical model important?

.kol-1-2.large[
- High information-density summary of analysis
- Almost everything we do in the analysis ultimately affects the likelihood function from the statistical model and is encapsulated in it
   - Trigger
   - Detector
   - Systematic Uncertainties
   - Event Selection
- Unique representation of the analysis to preserve
]
.kol-1-2.large[
.gray[When considering down-stream functionality, the .bold[full statistical model] together with the corresponding data are the .bold[gold standard] as they .bold[enable combinations, reinterpretations, and the generation of synthetic or pseudo data] ("toy Monte Carlo") that are typically needed for frequentist procedures (see e.g. Section 4.2.2), or for validating statistical procedures.]

.center.large[[Publishing statistical models: Getting the most out of particle physics experiments](https://inspirehep.net/literature/1919763)]
]

---
<!-- Slide 1 -->
# Historical Overview

.kol-1-2.large[
- .bold[2000]: Likelihood publishing recommended at [1st Workshop on Confidence Limits, CERN](http://inspirehep.net/record/534129)
]
.kol-1-2[
<br><br>
<br><br>
.width-100[[![likelihood_publishing_agreement](figures/likelihood_publishing_agreement.png)](https://cds.cern.ch/record/411537)]
]

---
<!-- Slide 2 -->
# Historical Overview

.kol-1-2.large[
- .bold[2000]: Likelihood publishing recommended at [1st Workshop on Confidence Limits, CERN](http://inspirehep.net/record/534129)
- .bold[201X]: Next thing, probably CMS publishing
]
.kol-1-2[
<br><br>
<br><br>
.width-100[[![likelihood_publishing_agreement](figures/likelihood_publishing_agreement.png)](https://cds.cern.ch/record/411537)]
]

---
# Summary
.kol-2-3.huge[
- Build community practices on top of .bold[established standards]
   <!-- - There are professional communities at work building tools, so we should join them, not rebuild a wheel -->
- If citation of your software is important to you, .bold[make it easy] for a user to find your citation information
- Modern standards like `CITATION.cff` allow for .bold[single source of citation information] that can be exported as needed
- Long term archives + [FAIR practices](https://indico.cern.ch/event/1211229/contributions/5120857/)
   - Zenodo provides automatically release information each release
]
.kol-1-3[
.center.width-80[[![CFF-logo](figures/CFF-logo.png)](https://citation-file-format.github.io/)]

.center.width-100[[![zenodo-logo](figures/zenodo-logo.svg)](https://zenodo.org/)]
]

---
class: end-slide, center

.huge[Backup]

---
# Does any of this actually work?

As mentioned, these opinions have been formed from developing pyhf, and the citation count for the [JOSS paper](https://doi.org/10.21105/joss.02823) has increased each year.

.center.width-100[[![pyhf-inspire-citations-count](figures/pyhf-inspire-citations-count.png)](https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=refersto%3Arecid%3A1845084&ui-citation-summary=true)]

---

class: end-slide, center
count: false

The end.
