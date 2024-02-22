# Fast, High-Fidelity LLM Decoding with Regex Constraints

This repository includes resources meant to complement this [blog post](https://vivien000.github.io/blog/journal/llm-decoding-with-regex-constraints.html) entitled *Fast, High-Fidelity LLM Decoding with Regex Constraints*:
- A technical appendix formalizing and proving the algorithms introduced in the blog post;
- A Python notebook with implementations of DirectMerge and CartesianMerge, along with additional empirical results.

Please note that the code in the Python notebook was tested only with the tokenizer of Mistral-7B and takes into account some of its specificities, in particular the fact that a blank space is prepended to the strings to tokenize. The code should be adapted to work with other tokenizers.
