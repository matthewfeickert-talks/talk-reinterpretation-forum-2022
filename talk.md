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

.center.large.bold[Start publishing (full) statistical models]

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

.kol-1-2[
- .bold[2000]: Likelihood publishing recommended at [1st Workshop on Confidence Limits, CERN](http://inspirehep.net/record/534129)
]
.kol-1-2[
<br><br>
<br><br>
.width-100[[![likelihood_publishing_agreement](figures/likelihood_publishing_agreement.png)](https://cds.cern.ch/record/411537)]

.center[DOI: [10.5170/CERN-2000-005](https://inspirehep.net/literature/534129)]
]

---
<!-- Slide 2 -->
# Historical Overview

.kol-1-2[
- .bold[2000]: Likelihood publishing recommended at [1st Workshop on Confidence Limits, CERN](http://inspirehep.net/record/534129)
- .bold[2012]: Public likelihood functions requested in [Les Houches Recommendations](https://inspirehep.net/literature/1093520)
]
.kol-1-2[
.width-100[[![les-houches-recommendations](figures/les-houches-recommendations.png)](https://inspirehep.net/literature/1093520)]
.center[DOI: [10.1140/epjc/s10052-012-1976-3](https://inspirehep.net/literature/1093520)]
]

---
<!-- Slide 3 -->
# Historical Overview

.kol-1-2[
- .bold[2000]: Likelihood publishing recommended at [1st Workshop on Confidence Limits, CERN](http://inspirehep.net/record/534129)
- .bold[2012]: Public likelihood functions requested in [Les Houches Recommendations](https://inspirehep.net/literature/1093520)
- .bold[2013]: ATLAS publishes likelihood scan RooFit Workspaces to HEPData
]
.kol-1-2[
.width-100[[![hepdata_workspaces](figures/hepdata_workspaces.png)](https://www.hepdata.net/record/106539)]

.center[[https://www.hepdata.net/record/106539](https://www.hepdata.net/record/106539)]
]

---
<!-- Slide N -->
# Historical Overview

.kol-1-2[
- .bold[2000]: Likelihood publishing recommended at [1st Workshop on Confidence Limits, CERN](http://inspirehep.net/record/534129)
- .bold[2012]: Public likelihood functions requested in [Les Houches Recommendations](https://inspirehep.net/literature/1093520)
- .bold[2013]: ATLAS publishes likelihood scan RooFit Workspaces to HEPData
- .bold[2017]: CMS PUB note on simplified likelihood for reinterpretation
]
.kol-1-2[
<br><br>
.width-100[[![CMS-note-2017-001](figures/CMS-note-2017-001.png)](https://cds.cern.ch/record/2242860/)]

.center[[CMS-NOTE-2017-001](https://cds.cern.ch/record/2242860/)]
]

---
<!-- Slide N -->
# Historical Overview

.kol-1-2[
- .bold[2000]: Likelihood publishing recommended at [1st Workshop on Confidence Limits, CERN](http://inspirehep.net/record/534129)
- .bold[2012]: Public likelihood functions requested in [Les Houches Recommendations](https://inspirehep.net/literature/1093520)
- .bold[2013]: ATLAS publishes likelihood scan RooFit Workspaces to HEPData
- .bold[2017]: CMS PUB note on simplified likelihood for reinterpretation
- .bold[2019]: First full statistical models published to HEPData for ATLAS SUSY analysis
]
.kol-1-2[
<br><br>
.width-100[[![HEPData_likelihoods](figures/HEPData_likelihoods.png)](https://www.hepdata.net/record/ins1748602)]

.center[DOI: [10.17182/hepdata.89408](https://doi.org/10.17182/hepdata.89408.v3/r2)]
]

---
<!-- Slide N -->
# Historical Overview

.kol-1-2[
- .bold[2000]: Likelihood publishing recommended at [1st Workshop on Confidence Limits, CERN](http://inspirehep.net/record/534129)
- .bold[2012]: Public likelihood functions requested in [Les Houches Recommendations](https://inspirehep.net/literature/1093520)
- .bold[2013]: ATLAS publishes likelihood scan RooFit Workspaces to HEPData
- .bold[2017]: CMS PUB note on simplified likelihood for reinterpretation
- .bold[2019]: First full statistical models published to HEPData for ATLAS SUSY analysis
- .bold[2019]: ATLAS PUB Note on publishing full statistical models using pyhf's JSON schema for HistFactory
]
.kol-1-2[
<br><br>
.width-100[[![PUB_note_cover](figures/PUB_note_cover.png)](https://inspirehep.net/literature/1795223)]

.center[[ATL-PHYS-PUB-2019-029](https://inspirehep.net/literature/1795223)]
]

---
<!-- Slide N -->
# Historical Overview

.kol-1-2[
- .bold[2000]: Likelihood publishing recommended at [1st Workshop on Confidence Limits, CERN](http://inspirehep.net/record/534129)
- .bold[2012]: Public likelihood functions requested in [Les Houches Recommendations](https://inspirehep.net/literature/1093520)
- .bold[2013]: ATLAS publishes likelihood scan RooFit Workspaces to HEPData
- .bold[2017]: CMS PUB note on simplified likelihood for reinterpretation
- .bold[2019]: First full statistical models published to HEPData for ATLAS SUSY analysis
- .bold[2019]: ATLAS PUB Note on publishing full statistical models using pyhf's JSON schema for HistFactory
- .bold[2020]: Reinterpretation forum advocates for full statistical models in [Status and Recommendations after Run 2 paper](https://inspirehep.net/literature/1785921)
]
.kol-1-2[
<br><br>
.width-100[[![reinterpretation-forum-recommendations](figures/reinterpretation-forum-recommendations.png)](https://inspirehep.net/literature/1785921)]

.center[DOI: [10.21468/SciPostPhys.9.2.022](https://inspirehep.net/literature/1785921)]
]

---
<!-- Slide N -->
# Historical Overview

.kol-1-2.small[
- .bold[2000]: Likelihood publishing recommended at [1st Workshop on Confidence Limits, CERN](http://inspirehep.net/record/534129)
- .bold[2012]: Public likelihood functions requested in [Les Houches Recommendations](https://inspirehep.net/literature/1093520)
- .bold[2013]: ATLAS publishes likelihood scan RooFit Workspaces to HEPData
- .bold[2017]: CMS PUB note on simplified likelihood for reinterpretation
- .bold[2019]: First full statistical models published to HEPData for ATLAS SUSY analysis
- .bold[2019]: ATLAS PUB Note on publishing full statistical models using pyhf's JSON schema for HistFactory
- .bold[2020]: Reinterpretation forum advocates for full statistical models in [Status and Recommendations after Run 2 paper](https://inspirehep.net/literature/1785921)
- .bold[2020]: SModelS publishes comparison of simplified models to full statistical models
]
.kol-1-2[
<br><br>
.width-100[[![sabine_workshop_slide](figures/sabine_workshop_slide.png)](https://inspirehep.net/literature/1814793)]

[Feedback on use of public Likelihoods](https://indico.cern.ch/event/957797/contributions/4026032/), Sabine Kraml
(ATLAS Exotics + SUSY Reinterpretations Workshop)

.center[DOI: [10.1016/j.cpc.2021.107909](https://inspirehep.net/literature/1814793)]
]

---
<!-- Slide N -->
# Historical Overview

.kol-1-2.small[
- .bold[2000]: Likelihood publishing recommended at [1st Workshop on Confidence Limits, CERN](http://inspirehep.net/record/534129)
- .bold[2012]: Public likelihood functions requested in [Les Houches Recommendations](https://inspirehep.net/literature/1093520)
- .bold[2013]: ATLAS publishes likelihood scan RooFit Workspaces to HEPData
- .bold[2017]: CMS PUB note on simplified likelihood for reinterpretation
- .bold[2019]: First full statistical models published to HEPData for ATLAS SUSY analysis
- .bold[2019]: ATLAS PUB Note on publishing full statistical models using pyhf's JSON schema for HistFactory
- .bold[2020]: Reinterpretation forum advocates for full statistical models in [Status and Recommendations after Run 2 paper](https://inspirehep.net/literature/1785921)
- .bold[2020]: SModelS publishes comparison of simplified models to full statistical models
- .bold[2021]: Publishing statistical models recommendations paper
]
.kol-1-2[
<br><br>
.width-100[[![publishing-statistical-models-paper](figures/publishing-statistical-models-paper.png)](https://inspirehep.net/literature/1919763)]

.center[DOI: [10.21468/SciPostPhys.12.1.037](https://inspirehep.net/literature/1919763)]
]

---
<!-- Slide N -->
# Historical Overview

.kol-1-2.small[
- .bold[2000]: Likelihood publishing recommended at [1st Workshop on Confidence Limits, CERN](http://inspirehep.net/record/534129)
- .bold[2012]: Public likelihood functions requested in [Les Houches Recommendations](https://inspirehep.net/literature/1093520)
- .bold[2013]: ATLAS publishes likelihood scan RooFit Workspaces to HEPData
- .bold[2017]: CMS PUB note on simplified likelihood for reinterpretation
- .bold[2019]: First full statistical models published to HEPData for ATLAS SUSY analysis
- .bold[2019]: ATLAS PUB Note on publishing full statistical models using pyhf's JSON schema for HistFactory
- .bold[2020]: Reinterpretation forum advocates for full statistical models in [Status and Recommendations after Run 2 paper](https://inspirehep.net/literature/1785921)
- .bold[2020]: SModelS publishes comparison of simplified models to full statistical models
- .bold[2021]: Publishing statistical models recommendations paper
- .bold[2022]: Snowmass 2022 white paper and COMPF07 recommendations
]
.kol-1-2[
.width-100[[![snowmass-white-paper-cover](figures/snowmass-white-paper-cover.png)](https://inspirehep.net/literature/2054747)]
.center[arXiv: [2203.10057](https://inspirehep.net/literature/2054747)]

.width-100[[![snowmass-compf7-recommendations](figures/snowmass-compf7-recommendations.png)](https://inspirehep.net/literature/2153139)]
.center[arXiv: [2209.08054](https://inspirehep.net/literature/2153139)]
]

---
# Future work and today's focus

.kol-1-2.large[
- Lots of exciting work in the publishing models landscape!
- Getting as many published and useable full statistical models as possible
   - Ongoing work in CMS looking towards publishing and use of full statistical models
- Making models published in different formats interoperable
   - Comparing and translating between HistFactory and CMS Combine serializations
- Creating new model formalisms that allow for greater adoption
   - HEP Statistics Serialization and JSON schemas
]
.kol-1-2[
<br><br>
.center.width-100[[![today-agenda](figures/today-agenda.png)](https://indico.cern.ch/event/1197680/sessions/466366/#20221213)]
]

---
class: end-slide, center

.huge[Backup]

---

class: end-slide, center
count: false

The end.
