# Historical Texts Summarizer/Modernizer

**By: Landon Bragg & Ben Kim**

## Project Overview

The *Historical Texts Summarizer/Modernizer* project uses neural networks to transform and summarize historical English texts into modern English. The aim is to make these texts more readable and accessible to contemporary audiences, especially students and scholars who encounter challenges understanding archaic language.

This project leverages deep learning techniques, such as encoder-decoder models with attention mechanisms, to condense lengthy texts into concise, unbiased summaries that retain essential points and meaning.


### Goal

The model is designed to translate complex, older English into simpler, modern English summaries. This solution is tailored to meet the needs of users who find traditional English challenging, such as students in courses like *Great Texts* at Baylor University.

### Target Audience

The target audience includes:
- Students and scholars of historical literature
- Individuals studying old English who need language simplification
- Educators who wish to use summaries as a teaching tool to explore language evolution

## Project Data

The model is trained on a custom dataset consisting of:
- **train_data**: Passages in older English
- **eval_data**: Professional modern English summaries of each passage

Each row in the dataset provides a sample of language transformation from complex historical English to simplified, modernized English, allowing the model to capture specific linguistic nuances while maintaining readability.


## Usage Instructions

### Model Training

1. Run the notebook’s training cells to prepare the model. You will be prompted to enter an API key for access to resources like Weights & Biases (WandB).
2. If you don’t have an API key, create an account and follow the instructions provided in the notebook.

### Summarization and Modernization

To use the summarizer:
1. Run the summarization cell.
2. Enter the text you want modernized, or use one of the built-in test examples.
3. The model will generate a simplified and concise version of the original text.


## Model Architecture

The model utilizes:
- **Encoder-Decoder with Attention Mechanisms**: To focus on essential parts of the input.
- **LSTM Layers**: Helps the model retain information across longer sequences, improving summary coherence.

## Future Improvements

Potential enhancements include:
- Expanding the dataset for better accuracy across various historical texts.
- Adjusting hyperparameters (e.g., learning rate, layer sizes) to refine model performance.
- Testing the model with different text types to assess its generalizability.

## Conclusion

This project demonstrates a practical approach to transforming historical texts, showcasing deep learning’s ability to bridge linguistic evolution. The generated summaries can support educational needs and broaden access to classical literature for modern readers.


