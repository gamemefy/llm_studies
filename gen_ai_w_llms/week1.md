# Introduction to LLMs and the generative AI project lifecycle

## Generative AI & LLMs
* we call LLM models such as GPT a base model. apparently it is one of the biggest but it doesn't seem the biggest
* we interact differently with LLM models compared to other machine learning models. they take natural language in a prompt window and the result is also in natural language
  
## LLM use cases and tasks
* areas of usage: text analysis, translation, coding, entity extraction(e.g. getting names of people), etc.

## Text generation before transformers
* transformers beat RNNs since it got introduced in 2017, allowing complex languages to be understandable to the machines with other benefits such as:
  * scale efficiently
  * put meanings of the words into consideration
  * make use of parallel processing, utilizing big data

## Transformers architecture
* self-attention: learn the relationships between tokens in input sequences(singular/plural?)
* multi-headed self-attention: self-attention but within different aspects of input sequences(singular/plural?)
* first inputs are turned into vectors at embedding part
* outputs will be selected through softmax. outputs are possibilities of easily thousands of different words. usually the highest possible word is chosen but there are other ways to select the output.
* 
