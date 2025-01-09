# Resume Screening Using NLP

## Project Overview
This project leverages Natural Language Processing (NLP) and Deep Learning to automate the resume screening process. By reducing biases and improving efficiency, the system ensures accurate and fair candidate evaluations for recruitment.

## Features
- **Automated Information Extraction**: Skills, experience, and education.
- **Objective Analysis**: Eliminates human bias.
- **Domain Adaptability**: Handles synonyms and skill variations.
- **Efficient Candidate Comparison**: Outputs structured data.

## Challenges
- Variability in resume formats.
- Synonym handling and ambiguous language.
- Precise skill tagging with Named Entity Recognition (NER).
- Addressing biases in training data.

## Methodology
### Data Preprocessing
- Removal of special characters and extra spaces.
- Tokenization and lowercase conversion.

### Model Selection
- **BERT**:
  - Contextual text understanding.
  - Named Entity Recognition (NER).
- **Transfer Learning**:
  - Fine-tuned pre-trained BERT models.
- **Tools**:
  - PyTorch for model training.
  - SpaCy for NER.
  - NLTK for tokenization.

## Results
- **Accuracy**: High precision in identifying key resume information.
- **Metrics**:
  - F1-Score: Balanced performance evaluation.
  - Matthews Correlation Coefficient: Reliable binary classification.
  - Cohen’s Kappa: High agreement with human judgment.

## Impacts
- **Social**: Enhances diversity and fairness.
- **Economic**: Reduces recruitment costs and time.
- **Business**: Boosts talent acquisition processes.
- **Scientific**: Advances NLP applications.

## Limitations and Future Work
- Address biases in training data using adversarial debiasing.
- Expand domain adaptability for varied resume formats.
- Enable real-time resume processing.

## References
1. Nunna et al., 2024. *Automated Resume Analysis and Skill Suggestion Website*.
2. Lakshmi Padmaja et al., 2023. *Automated Resume Screening Using NLP*.
3. Sroison et al., 2024. *Resume Parser with NLP*.

---

## Feedback
Building this system applied NLP knowledge to a practical challenge. The results validated the approach and highlighted areas for future exploration.
