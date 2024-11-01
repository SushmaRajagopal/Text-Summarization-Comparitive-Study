
# Text-Summarization-Comparitive-Study


Text summarization, an interesting problem in natu
ral language processing, requires the ability to extract significant
 information from a text and create concise and informative
 summaries. Recent improvements in the discipline, particularly
 the usage of Transformer-based models, have resulted in state
of-the-art text summarization performance, across a wide range
 of benchmarks. We evaluate the efficacy of 4 important text
 summarising algorithms using the CNN/Daily Mail dataset: GPT
2, BART, T5-Small and Pegasus. GPT-2, a large language model
 built on a Transformer architecture, is one of the models under
 consideration. It is assumed that the first 3 lines of the articles in
 the dataset as the baseline model or human-written summaries.
 Training all 4 models with the dataset and telling them to
 summarize, whose outputs are stored in a dictionary called
 summaries. Then given a new input text from the article column
 of the dataset all models summarize the given text and for
 those output summaries, ROUGE and BLEU scores are found to
 compare which is best. Visualization is done in various forms like
 Heat maps and Bar graphs. ROUGE scores provide quantitative
 measures of the quality of generated summaries.
