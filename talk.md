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

.middle-logo[]

---
# Historical Overview

.kol-1-2.large[
- 2010
]
.kol-1-2[
<br><br>
.center.width-100[[![dan-katz-intro](figures/dan-katz-intro.png)](https://indico.cern.ch/event/1211229/contributions/5120849/)]
.center[[Daniel Katz's talk](https://indico.cern.ch/event/1211229/contributions/5120849/)]
]

---
# Why is the likelihood important?

.kol-1-2.width-90[
<br>
- High information-density summary of analysis
- Almost everything we do in the analysis ultimately affects the likelihood and is encapsulated in it
   - Trigger
   - Detector
   - Systematic Uncertainties
   - Event Selection
- Unique representation of the analysis to preserve
]
.kol-1-2.width-100[
<br><br>
[![likelihood_connections](figures/likelihood_connections.png)](https://indico.cern.ch/event/839382/contributions/3521168/)
]

---
# Likelihood serialization...

.center[...making good on [19 year old agreement to publish likelihoods](https://indico.cern.ch/event/746178/contributions/3396797/)]

.center.width-90[
[![likelihood_publishing_agreement](figures/likelihood_publishing_agreement.png)](https://cds.cern.ch/record/411537)
]

.center[([1st Workshop on Confidence Limits, CERN, 2000](http://inspirehep.net/record/534129))]

.bold[This hadn't been done in HEP until now]
- In an "open world" of statistics this is a difficult problem to solve
- What to preserve and how? All of ROOT?
- Idea: Focus on a single more tractable binned model first

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
