# Patient Medical Summary with Large Language Models (LLMs) 🏥💡

This project leverages state-of-the-art large language models (LLMs) to generate concise and informative medical summaries for patients based on their detailed medical history. The goal is to automate the summarization process, improving healthcare workflows and making patient data easier to understand for medical professionals.

## Features ⚙️

- **Medical History Summarization**: The project uses pre-trained language models such as BART and GPT to summarize complex patient medical histories into concise summaries.
- **Easy Integration**: The code is designed for easy integration into healthcare systems for real-time patient summary generation.
- **Flexibility**: The system supports multiple LLM architectures to choose the best model for summarization tasks.
- **Scalable**: Can be used to process data for multiple patients simultaneously, supporting batch processing for larger datasets.

## Models Used 🧠

1. **DistilBART (Distilled BART)**: A lighter version of BART used for summarization tasks.
2. **GPT-Neo**: A transformer-based language model by EleutherAI for generating creative and context-aware summaries.
3. **BART (facebook/bart-large-cnn)**: A powerful encoder-decoder architecture fine-tuned for text summarization tasks.

## Requirements 📝

- Python 3.7 or above
- `transformers` library from Hugging Face
- `torch` for model inference
- Other dependencies in `requirements.txt`

## Installation 🔧

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/patient-medical-summary-llm.git
    cd patient-medical-summary-llm
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Contributing 🤝

Feel free to open issues or submit pull requests if you'd like to contribute to this project. We welcome suggestions for improvements and new features, especially for the integration of additional LLMs.

## Acknowledgements 🙏
- Hugging Face Transformers for providing powerful pre-trained models.
- EleutherAI for developing GPT-Neo.
- Facebook for releasing BART.

