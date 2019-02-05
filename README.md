# narrowbroad
This repository provides data and code needed to reproduce all analyses reported in Scholz, Baek, O'Donnell, Falk (2019). Decision-making about broad- and narrowcasting: A neuroscientific perspective. Media Psychology. DOI: 10.1080/15213269.2019.1572522.

NOTE: We report that neural activity in the contrasts of interest is not significantly associated with the size of participants' ego Facebook network. We are currently not including network size in the datasets provided here while we review our policy on participant privacy protection and data sharing. 

Data files:

- Percent signal change in ROIs during reading screen periods of the Article task in three contrasts: Narrowcasting > Control (NARROWvsCONTENT_read), Broadcasting > Control (BROAD>CONTENT_read), Narrowcasting > Broadcasting (NARROWvsBROAD_read):
  - Self-related processing ROI: nsynth_self.csv
  - Social processing ROI: nsynth_ment.csv
  - Self excluding social ROI: nsynth_selfnotment.csv
  - Social excluding self ROI: nsynth_mentnotself.csv
  
- Identical ROI exctractions from the neural model which controls for reaction time:
  - Self-related processing ROI: nsynth_self_rt.csv
  - Social processing ROI: nsynth_ment_rt.csv
  - Self excluding social ROI: nsynth_selfnotment_rt.csv
  - Social excluding self ROI: nsynth_mentnotself_rt.csv
  
- Article (art_id) word count (for teaser_wc = abstract and total_wc = abstract + headline) and presentation times (pres_time) within the Article task in s: articles.csv
- Participant (pID) gender and age: demographics_wo_egodegree.csv
- Reaction times Article task: rt.csv

Analysis:
- R-Code for Analysis: analysis.Rmd
- R-Markdown output: analysis_out.html
