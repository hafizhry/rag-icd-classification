# RAG System for ICD Code Classification

## Project Overview
This project involves developing a **Retrieval-Augmented Generation (RAG) system** that leverages **OpenAI’s GPT** and **LangChain** to extract **ICD codes** from medical symptom descriptions in **English** and **Indonesian**. The system utilizes a bilingual knowledge base of ICD code descriptions to assist physicians in determining more accurate ICD codes, particularly when using local Indonesian language symptom descriptions.

## Key Features
- **Multilingual Support**: Extracts ICD codes from symptom descriptions in both **English** and **Indonesian**.
- **Bilingual Knowledge Base**: The system is powered by a knowledge base containing ICD code descriptions in both languages, enhancing its ability to provide accurate results in diverse settings.
- **RAG Architecture**: Combines retrieval capabilities with GPT’s generative abilities, optimizing both the retrieval of relevant information and the generation of appropriate ICD codes.
- **Healthcare Application**: Specifically designed to assist **physicians** by streamlining the process of matching symptoms to ICD codes, improving diagnosis accuracy in Indonesia's healthcare system.

## Project Structure
- `src/`: Contains the core Python scripts for the RAG implementation using **LangChain** and **OpenAI’s GPT** API.
- `data/`: Includes the **bilingual ICD knowledge base** in **CSV format**, containing both English and Indonesian ICD descriptions.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and system demonstration.
- `docs/`: Documentation and system overview, including project reports and presentations.
- `models/`: Pre-trained model weights and fine-tuning scripts for handling ICD code classification.
- `README.md`: This file, providing an overview of the project.

## Setup & Installation

### Prerequisites
- Python 3.7+
- OpenAI API Key
- LangChain
- Pandas
- Scikit-learn

### Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/RAG-ICD-Classification.git
    cd RAG-ICD-Classification
    ```
2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Set up your OpenAI API Key:
    ```bash
    export OPENAI_API_KEY='your-api-key-here'
    ```

4. Run the notebook to test the system:
    ```bash
    jupyter notebook notebooks/demo.ipynb
    ```
## Future Work
- Expand the knowledge base to include more languages.
- Fine-tune the model for specific regions and healthcare systems.
- Integrate with **Electronic Health Records (EHR)** systems for real-time ICD classification.

## Contact
For further questions or collaboration, feel free to contact me at hafizhry@umich.com.