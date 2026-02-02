# Government Rhetoric in Greek Parliamentary Speeches (2010–2020)
### course project: Advanced Social Data Science II | SODAS, University of Copenhagen, Spring 2025 

This project analyzes rhetorical style in Greek parliamentary proceedings (2010–2020), focusing on:\
  (1) emotional tone in government vs opposition speech\
  (2) linguistic complexity across speaker roles\
  (3) semantic change in political discourse over time\
The work adapts computational social science methods to Modern Greek, using custom preprocessing and embedding-based approaches.

### Notebooks & Files

`00_preprocessing.ipynb`  Data handling, cleaning, and preprocessing pipeline.\
`01_lexiconbasedsentimentanalysis.ipynb`  RQ1 — Emotional rhetoric differences during political crises.\
`02_smogindexanalysis.ipynb`  RQ2 — Linguistic complexity of government officials vs other MPs.\
`03_semanticdriftanalysis_visualizations.ipynb`  RQ3 — Semantic and rhetorical drift over the decade.\
`04_results-visualizations.ipynb`  Final plots and summary visualizations.

`asds2-project-requirements.txt` — Python dependencies\
`out_lexicon_6sent.csv` — Sentiment lexicon output (6 emotion categories) by Drista(2018)\
`embeddings/` — Word embedding models used for semantic drift analysis\

### Methods
- Lexicon-based sentiment scoring (Greek-adapted)
- Readability and SMOG complexity metrics
- Word embeddings + semantic drift techniques
- Greek-BERT (`nlpaueb/bert-base-greek-uncased-v1`)

### References
Hjorth (2024), The Rhetorical Cost of Governing\
Loukas et al. (2024), GR-NLP Toolkit for Modern Greek\
Rodriguez & Spirling (2022), Word Embeddings in Political Science\
Widmann (2021), Emotional Appeals in Populist Rhetoric\
Dritsa (2018), Speech Quality and Sentiment Analysis on the Hellenic Parliament Proceeding
