 Text Summarization Using Deep Learning

 1. Project Overview
This project implements an abstractive text summarization system using the T5-small Transformer model. The model generates concise summaries from longer text while attempting to preserve the main information.

 2. Objectives
- Develop an automated text summarization system.
- Fine-tune the T5-small model using the CNN/DailyMail dataset.
- Evaluate generated summaries using ROUGE metrics.
- Provide a simple user interface using Streamlit.

 3. Technologies Used
- Python
- PyTorch
- Hugging Face Transformers
- T5-small
- CNN/DailyMail dataset
- ROUGE evaluation metrics
- Streamlit
- Matplotlib

 4. Project Workflow
Dataset Preparation → Text Preprocessing → Model Fine-Tuning → Evaluation → Summary Generation

5. Main Features
- Abstractive text summarization.
- Transformer-based text generation.
- ROUGE-based evaluation.
- Training and evaluation visualizations.
- Streamlit interface for entering text and viewing summaries.
- Chunking support for long input text, if enabled in the application.

6. Dataset
The project uses the CNN/DailyMail dataset. The model was trained and evaluated using selected subsets of the dataset.

7. Evaluation
The model is evaluated using ROUGE-1, ROUGE-2, and ROUGE-L. The evaluation results and plots are provided in the `results/` directory when available.

8. Installation
Install the required Python libraries:

```bash
pip install -r requirements.txt
```

9. Running the Application
From the repository root directory, run:

```bash
streamlit run app/app.py
```

Ensure that the trained model is available at the path configured in `app/app.py`.

10. Project Structure
- `notebooks/` — Model development, training and evaluation.
- `app/` — Streamlit application.
- `results/` — Evaluation results and plots.
- `report/` — Final project report.
- `requirements.txt` — Required Python libraries.

11. Future Scope
- Improve summary quality and evaluation.
- Support additional document formats.
- Explore deployment as a web application.
