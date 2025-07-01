# TFM-Evaluating-Transformer-Reasoning-Applied-to-Chess-and-Improving-It-Using-Search-Heuristics

In 2024, Google introduced three Large-Scale Transformer-based models (LST), with 9, 136, and 270 million parameters, designed to evaluate chess moves. The largest model, with 270 million parameters, was trained on billions of positions and achieved performance comparable to that of a grandmaster.

This breakthrough suggests that Transformers are not only effective in tasks related to memorization, such as natural language processing, but can also tackle problems that require reasoning and complex pattern recognition. To explore this capability, this Master’s Thesis proposes a detailed analysis of the model.

First, the performance of the LST will be evaluated using a set of chess puzzles grouped by difficulty and type of challenge, allowing the study of its behavior across different levels of complexity. Next, a depth-search scheme will be implemented in which the model itself will act as a heuristic. The results will be compared to those obtained by the base model to analyze whether integrating a search strategy can outperform the improvements achieved solely by increasing the number of model parameters.

You can find the used models in this repo: [Searchless Chess](https://github.com/google-deepmind/searchless_chess).

Thanks to my tutor [Francisco Herrera Triguero](https://scholar.google.com/citations?user=HULIk-QAAAAJ&hl=en) and my workmate [Ignacio Aguilera Martos](https://scholar.google.es/citations?user=6qqRY7oAAAAJ&hl=es) for support me in this project.
