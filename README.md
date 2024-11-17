# Code-Mix Generation Project

## Abstract
This project focuses on generating code-mixed text, a common phenomenon in multilingual societies where multiple languages blend seamlessly in communication. Specifically, the project addresses the Hindi-English mix known as Hinglish. Utilizing advanced natural language processing techniques such as Long Short-Term Memory (LSTM), Transformer, and T5 models, we evaluate and develop effective methods to replicate this linguistic fusion.

---

## Objectives
- **Algorithm Development**: Create algorithms capable of generating linguistically accurate code-mixed text in Hindi and English.
- **Model Exploration**: Analyze the performance of LSTM, Transformer, and T5 models for their ability to generate code-mixed content.
- **Performance Metrics**: Use the BLEU score to evaluate the fluency and accuracy of the generated text.

---

## Dataset
- The dataset includes a combination of Hinglish sources enhanced via data augmentation for linguistic diversity.
- Challenges faced: Limited initial dataset size and computational constraints.

---

## Methodology
1. **Models Implemented**:
   - **LSTM**: Captures long-range dependencies in text sequences.
   - **Transformer**: Uses self-attention for contextual understanding.
   - **T5**: Frames tasks in a text-to-text format, enabling robust generation.

2. **Evaluation Metric**:
   - BLEU (Bilingual Evaluation Understudy) score is used to measure similarity to reference text.

---

## Results
- BLEU Scores:
  - LSTM: 0.00175
  - Transformer: 0.00216
  - T5: 0.00254
- T5 demonstrated superior performance in generating code-mixed text compared to LSTM and Transformer models.

---

## Challenges
- **Dataset Limitations**: Insufficient diversity in Hinglish datasets required extensive augmentation.
- **Computational Resource Constraints**: Training large models required optimization to manage memory and processing power.
- **Preprocessing Complexity**: Transforming English text to Hinglish while maintaining context and linguistic accuracy.

---

## Future Directions
- Enhance dataset size and diversity.
- Optimize models for efficiency and scalability.
- Integrate innovative techniques to improve code-mixed text generation quality.

---

## Contributors
- Omprateek Shrivastava
- Vishnu Ranjith
- Pradhyumna Palore 
