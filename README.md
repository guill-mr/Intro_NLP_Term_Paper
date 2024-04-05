# Intro_NLP_Term_Paper
Repository for the term paper on Introduction to NLP.

Group Members:
- Bennett, Andrew
- Handt Fueyo, Miguel
- Mirabent Rubinat, Guillem

For this paper, we studied the predictive capacity of a model trained on speeches from Spanish politicians. We trained the model strictly on speeches from politicians who pertain to the 2 main Spanish political parties (PSOE and PP) and then we used this model to predict the party of politicians from other Spanish parties. 

The results we got were quite interesting for other nation-level parties. Specifically for Podemos and VOX, the model was able to identify which was which only based on how similar they were to the speeches it was trained on.
At least at a correlational level, we can extract that right-wing parties and left-wing parties in Spain do use some semantic resources which are different from the other side on the political spectrum but which present some relevant similarities among parties closer on the spectrum. This only holds for parties which have the whole country of Spain as their political scope because the model fails to differentiate significatively when regional parties come into play.

This paper data comes from the project ParlaMint:
Erjavec, Tomaž; et al., 2023, Multilingual comparable corpora of parliamentary debates ParlaMint 4.0, http://hdl.handle.net/11356/1859.

From which we used only the Spanish Corpus.
