# Adapting-language-models-to-new-topics
This project investigates how well state-of-the-art language models like GPT-3.5 and PaLM-2 can adapt to new topics outside of their training data. Specifically, it looks at few-shot learning approaches for sentiment analysis on financial news (seen domain) and poetry (unseen domain).

Problem Statement
Language models struggle when applied to niche topics and domains they haven't encountered before. This project evaluates this limitation by testing how well GPT-3.5 and PaLM-2 perform on seen data they were primed on versus unseen data from a different domain.

Methodology
Sentiment analysis classification on financial news articles (seen domain) and poetry excerpts (unseen domain)
GPT-3.5 and PaLM-2 models tested via few-shot learning
Models primed with financial news examples, then tested on poetry without any domain adaptation
50 test cases conducted per experiment configuration
Results
Accuracy 40-60% on seen financial news domain
Accuracy drops to 6-16% on unseen poetry domain
PaLM-2 outperforms GPT-3.5 on both seen and unseen datasets
Models tend to predict "no result" more frequently for unfamiliar poetry data
PaLM-2 better leverages context learning from few examples
Conclusions
Few-shot learning alone insufficient for adapting to radically different topics
More advanced adaptation techniques likely necessary
Architectural improvements enable better generalization
Significant scope to enhance model versatility through advanced techniques
Important implications for real-world language model deployment
Reference
See the [project report PDF](Adapting language models to new topics.pdf) for full background and details.
