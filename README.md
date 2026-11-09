# CO3 – Advanced NLP and Transformer-Based Applications

This folder contains the CO3 practicals for the **Natural Language Processing (NLP)** course. The notebooks explore modern transformer models and applied NLP tasks, including classification, embeddings, text generation, entity recognition, translation, summarization and conversational systems.

## Practical List

| No. | Notebook | Topic |
|---:|---|---|
| 24 | `24_Fine_Tuning_BERT_Text_Classification.ipynb` | Fine-tuning BERT for text classification |
| 25 | `25_Sentence_Embeddings_BERT_GPT2.ipynb` | Sentence embeddings using BERT and GPT-2 |
| 26 | `26_Text_Generation_GPT2_Custom_Dataset.ipynb` | Text generation with GPT-2 and a custom dataset |
| 27 | `27_Named_Entity_Recognition_BERT.ipynb` | Named Entity Recognition using BERT |
| 28 | `28_Machine_Translation_MarianMT.ipynb` | Machine translation using MarianMT |
| 29 | `29_Text_Summarization_BART_.ipynb` | Text summarization using BART |
| 30 | `30_DialogGPT.ipynb` | Conversational text generation using DialoGPT |
| 31 | `31_Automatic_Doc_Classification.ipynb` | Automatic document classification |
| 32 | `32_FSM_Sequence_Modeling.ipynb` | FSM-based sequence modeling and document boundary detection |

## Requirements

These practicals commonly use Python, PyTorch and Hugging Face libraries. Install the common dependencies with:

```bash
pip install numpy pandas scikit-learn matplotlib
pip install torch transformers datasets accelerate sentencepiece
```

A notebook may require additional packages or a specific model/tokenizer. Follow the imports and setup instructions inside each notebook.

## How to Run

1. Open a notebook in **Google Colab** or **Jupyter Notebook**.
2. Select a runtime with sufficient RAM; a GPU runtime is recommended for model fine-tuning and generation.
3. Install the notebook's dependencies.
4. Load the required pretrained model/tokenizer and dataset. Some models are downloaded automatically on first use.
5. Run the notebook cells in order and inspect the generated outputs.

## Learning Outcomes

After completing these practicals, you should be able to:

- Fine-tune a pretrained BERT model for text classification.
- Generate and work with contextual sentence embeddings.
- Generate text using GPT-2.
- Perform transformer-based Named Entity Recognition.
- Translate text using MarianMT.
- Summarize documents using BART.
- Build a basic conversational system using DialoGPT.
- Classify documents automatically.
- Apply finite-state-machine concepts to sequence modeling and document boundary detection.

## Notes

- First-time model downloads require an internet connection and may take time.
- Large transformer models can require significant RAM/VRAM. Use a smaller model, reduced batch size, or a GPU runtime if necessary.
- Check each notebook for its expected dataset, language pair, model checkpoint and file paths.
- Model outputs are probabilistic; results may vary with model versions, random seeds and input data.
