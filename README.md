# Build-Your-Own-LLM

## Purpose
Most of the LLM foundation models, even if they are called Open, are behind closed doors controlled by the Big Tech. The research community is doing an amazing job to democratize LLMs, with the limited resources at their disposal. This repo is intended to capture the guidance and resources that allow you to build and fine-tune LLMs based on open source.

Please create a pull request if you have something helpful to share.

### Open Source LLMs
+ [List of Open Sourced Fine-Tuned LLMs](https://medium.com/geekculture/list-of-open-sourced-fine-tuned-large-language-models-llm-8d95a2e0dc76)

#### Foundation (Base) LLMs
+ [LLaMa from Facebook](https://github.com/facebookresearch/llama) Restricted use, but this model has been [leaked](https://www.deeplearning.ai/the-batch/how-metas-llama-nlp-model-leaked/) and can be found on torrents.

#### Instruction Tuned LLMs 
+ [Alpaca from Stanford University](https://crfm.stanford.edu/2023/03/13/alpaca.html) (Restricted use, as it is based on Facebook's LLaMa)
+ [Koala from UC Berkeley](https://bair.berkeley.edu/blog/2023/04/03/koala/) (Restricted use, as it is based on Facebook's LLaMa)
+ [HuggingFace](https://huggingface.co/OpenAssistant/oasst-sft-6-llama-30b-xor) (Restricted use, as it is based on Facebook's LLaMa)
+ [OPT-IML](https://huggingface.co/facebook/opt-iml-max-30b)

### Easy to read Concepts of LLMs
+ [Visualization of Transformer](https://jalammar.github.io/illustrated-transformer/)

### Development Frameworks
+ [Hugging Face](https://huggingface.co/) Provides easy Python libraries to design, train and infer with LLMs

### Frameworks to interact with and use LLMs
+ [LangChain - Building applications with LLMs through composability](https://github.com/hwchase17/langchain)
+ [LlamaIndex - Connect your LLM's with external data](https://github.com/jerryjliu/llama_index)

### Run LLM on your Laptop (low resource devices)
+ [Run the LLaMA model using 4-bit integer quantization on a MacBook](https://github.com/ggerganov/llama.cpp)

### Frontends to interact with LLMs
+ [Web UI for LLMs](https://github.com/oobabooga/text-generation-webui)
+ [An LLM playground you can run on your laptop.](https://github.com/nat/openplayground)

### Datasets to train your LLM (if you have the infra)
+ [Common Crawl](https://commoncrawl.org/)
