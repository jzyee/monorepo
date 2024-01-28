# monorepo
for all the small personal projects

```
monorepo
├── llava
|  ├── llava_.ipynb
|  └── requirements.txt
├── mistral
|  ├── mistral.ipynb
|  └── requirements.txt
├── README.md
└── r_python
   ├── test.ipynb
   └── test_4_1_0.ipynb


```

tree was made using treee command using tree-cli[1]


# references

[1] tree-cli: https://github.com/MrRaindrop/tree-cli



# Model Landscape

| Model Name    | Hugging Face Link or Similar                                                 | Made By (Company) | Authors | Number of Parameters   | Use Case                                              | Novelty/Special Feature                                         | Done |
|---------------|------------------------------------------------------------------------------|-------------------|---------|------------------------|-------------------------------------------------------|-----------------------------------------------------------------|------|
| Mistral       | [Mistral](https://huggingface.co/Mistral)                                    | Mistral AI        | N/A     | 7 Billion              | General LLM tasks                                     | Sliding Window Attention for extended context comprehension      |  ✓      |
| Mixtral       | [Mixtral](https://huggingface.co/Mixtral)                                    | N/A               | N/A     | 85 Billion             | General LLM tasks                                     | Mixture of Experts (MOE) model for efficient scaling            |      |
| LLaMA         | [LLaMA](https://huggingface.co/LLaMA)                                        | N/A               | N/A     | 7B, 13B, 33B, 65B      | General LLM tasks, research                           | Multiple sizes for diverse research and application needs        |  ✓      |
| OpenFlamingo  | [OpenFlamingo](https://huggingface.co/OpenFlamingo)                          | N/A               | N/A     | N/A                    | Multimodal tasks                                      | Focuses on multimodal understanding combining text and images    |  ✓      |
| OpenCLIP      | [OpenCLIP](https://huggingface.co/OpenCLIP)                                  | N/A               | N/A     | Various                | Multimodal tasks                                      | Advanced image-text matching capabilities                       |   ✓      |
| GPT-3         | [GPT-3](https://huggingface.co/OpenAI/gpt-3)                                 | OpenAI            | N/A     | 175 Billion            | General-purpose LLM, text generation, NLP tasks       | One of the largest and most powerful LLMs                        |      |
| BERT          | [BERT](https://huggingface.co/bert-base-uncased)                             | Google            | N/A     | 110 Million (Base)     | NLP tasks, text classification, question answering    | Introduced transformer-based architecture, revolutionized NLP    |      |
| T5            | [T5](https://huggingface.co/t5-small)                                        | Google            | N/A     | Varies                 | General-purpose LLM, text-to-text tasks               | Text-to-text approach, versatile for various NLP tasks           |      |
| RoBERTa       | [RoBERTa](https://huggingface.co/roberta-base)                               | Facebook AI       | N/A     | 125 Million (Base)     | NLP tasks, text classification, sentiment analysis    | Improved BERT with more training data and hyperparameter tuning  |      |
| XLNet         | [XLNet](https://huggingface.co/xlnet-base-cased)                             | Google/CMU        | N/A     | 110 Million (Base)     | NLP tasks, text generation, text classification       | Combines strengths of BERT and GPT                               |      |
| ELECTRA       | [ELECTRA](https://huggingface.co/google/electra-base-discriminator)           | Google            | N/A     | 110 Million (Base)     | NLP tasks, efficient pre-training for transformers    | Efficiently pre-trained, smaller but competitive                 |      |
| CLIP          | [CLIP](https://huggingface.co/openai/clip-vit-base-patch32)                  | OpenAI            | N/A     | Varies                 | Image and text understanding, zero-shot learning      | Connects images and text                                         |      |
| DALL-E        | [DALL-E](https://huggingface.co/flax-community/dalle-mini)                   | OpenAI            | N/A     | 12 Billion             | Image generation from textual descriptions            | Novel approach to generating images from text descriptions       |      |
| ViT           | [ViT](https://huggingface.co/google/vit-base-patch16-224)                    | Google            | N/A     | 86 Million             | Image classification, computer vision tasks           | Transformer model directly applied to sequences of image patches |      |
| DeBERTa       | [DeBERTa](https://huggingface.co/microsoft/deberta-base)                     | Microsoft         | N/A     | 138 Million (Base)     | NLP tasks, better MLM and NLU performance             | Enhanced BERT and RoBERTa with disentangled attention mechanism  |      |
