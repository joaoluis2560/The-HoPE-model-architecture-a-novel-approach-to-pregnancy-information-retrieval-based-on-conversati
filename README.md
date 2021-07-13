# The HoPE model architecture: a novel approach to pregnancy information retrieval based on conversational agents
Conversational agents are used to communicating with humans in a friendlymanner.  To  achieve  the  highest  level  of  performance,  agents  need  to  respond  as-sertively and fastly. Transformers architectures are shown to produce excellent per-formances on recent tasks, however, for tasks involving conversational agents theymay have a lower speed performance. The main goal of this study is to evaluate andpropose a HoPE (Healthcare and Obstetric in PrEgnancy) model that is tailored topregnancy data. We carried out a dataset extraction and construction process based oncollections of health documents related to Breastfeeding, Childcare, Pregnant Care,Nutrition, Risks, Vaccines, Exams, and Physical Exercises. We evaluated two pre-trained models in the Portuguese language for the conversational agent architectureproposal and chose the one with the best performance to compose the HoPE architec-ture. The BERTimbau model, which has been trained on data augmentation strategies,proves to be able to retrieve information quickly and most accurately than others.Forthe fine-tuning process, we achieved a Spearman correlation of 92.74 on BERTimbauaugmented with a few pairs (1200 pairs). The HoPE model architecture, achievedan F1-Score of 0.87, outperforming other combinations tested in this study, such asBERTimbau TF-IDF and BERTimbau BM25. We will evaluate this approach for clin-ical studies in future studies.
