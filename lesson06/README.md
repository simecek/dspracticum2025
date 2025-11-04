**Date**: Oct 20, 2025

* [Let's build GPT: from scratch, in code, spelled out](https://www.youtube.com/watch?v=kCc8FmEb1nY) (Karpathy's [original notebook](https://colab.research.google.com/drive/1JMLa53HDuA-i7ZBmqV7ZnA3c_fvtXnx-?usp=sharing) and [repo](https://github.com/karpathy/ng-video-lecture), our [modified notebook](Let_us_build_GPT.ipynb))

**Additional materials:**

* Original [GPT-2 paper](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) + [some exploration](https://www.kapilsharma.dev/posts/exploring-gpt2/)
* Karpathy's [Let's reproduce GPT-2 (124M)](https://www.youtube.com/watch?v=l8pRSuU81PU) lecture going a bit deeper
* Karpathy's [nanochat](https://github.com/karpathy/nanochat)
* [Everything About Transformers](https://www.krupadave.com/articles/everything-about-transformers)

**Assignment 06** (due **Nov 3, 8:30 AM**)

Train a GPT-2 model on the text you scraped in **Assignment 05**.  
You may (but don’t have to) use [Let_us_build_GPT.ipynb](Let_us_build_GPT.ipynb).

* Generate some text — how does it look?  
* Try to improve your GPT-2 model:  
  - **Add tokenization** using the `tiktoken` package (see hint in [HW06_hint.ipynb](HW06_hint.ipynb)).  
  - Experiment with other parameters and observe how they affect the generated text. It is a bit alchemy. 
  - Try prompting your model with something more interesting than just `\n`.  

Submit your training notebook and a sample of the generated text.  
Does it at least resemble the structure of the original?



