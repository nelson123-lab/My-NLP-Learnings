- Salesforce Research has introduced a series of Large Language Models (LLMs) called XGen-7B, which are trained on sequences up to 8K tokens long. This is a 
  significant advancement as most open-source LLMs are trained on sequences with a maximum of 2K tokens. The XGen-7B models include XGen-7B-4K-Base, XGen-7B-8K-Base, 
  and XGen-7B-8k-Inst, which have been fine-tuned on public-domain instructional data.

- These models were trained using Salesforce’s proprietary library JaxFormer, optimized for TPU-v4 hardware. The training process involved a staged approach, 
  starting with 800B tokens with a sequence length of 2k tokens, then 400B tokens with 4k length, and finally, 300B tokens with 8k length.

- The XGen-7b models were evaluated on three primary tasks: long-form dialogue generation, text summarization, and question-answering. Across all tasks, the XGen-7B 
  models outperformed other instruction-tuned and baseline models, demonstrating their superior performance in understanding and generating coherent responses in 
  extensive text contexts.

- However, like many AI models, the XGen-7b models are not exempt from biases and can potentially generate toxic responses. Salesforce Research has open-sourced its 
  code to allow the community to further explore and improve upon their work.



