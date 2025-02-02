# Text-Summarization-using-Topsis

## Overview
This project evaluates text summarization models (**BART**, **T5**, **Pegasus**, **GPT-3.5**) using performance metrics like ROUGE, BLEU, inference time, and model size. The **TOPSIS** method ranks models for a balanced assessment of performance and efficiency.

---

## Evaluation Metrics
- **ROUGE-1**, **ROUGE-2**, **ROUGE-L**: Measure summary quality.
- **BLEU**: Evaluates n-gram overlap with reference summaries.
- **Inference Time**: Critical for real-time applications.
- **Model Size**: Indicates resource requirements.

---

## Models Evaluated
- BART
- T5
- Pegasus
- GPT-3.5

---

## Results
### TOPSIS Rankings
1. **Pegasus** - Best balance of performance and efficiency.
2. **T5** - Strong performance, slightly higher resource usage.
3. **BART** - Moderate performance, reasonable resource usage.
4. **GPT-3.5** - Competitive performance but higher resource demands.

### Visualizations
 ![Image](https://github.com/Baneet2s/Text-Summarization-using-Topsis/blob/main/download.png)

---

## Files Included
- **topsis_results.csv**: Performance metrics and rankings.
- **topsis_report.md**: Summary of results.
- **topsis_evaluation.ipynb**: Code for evaluation.

---

## Conclusion
Pegasus is the top-performing model based on TOPSIS ranking, offering the best balance of performance and efficiency.
