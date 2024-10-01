# RAG System for ICD Code Classification

## Project Overview
This project involves developing a **Retrieval-Augmented Generation (RAG) system** that leverages **OpenAI’s GPT** and **LangChain** to extract **ICD codes** from medical symptom descriptions in **English** and **Indonesian**. The system utilizes a bilingual knowledge base of ICD code descriptions to assist physicians in determining more accurate ICD codes, particularly when using local Indonesian language symptom descriptions.

## Key Features
- **Multilingual Support**: Extracts ICD codes from symptom descriptions in both **English** and **Indonesian**.
- **Bilingual Knowledge Base**: The system is powered by a knowledge base containing ICD code descriptions in both languages, enhancing its ability to provide accurate results in diverse settings.
- **RAG Architecture**: Combines retrieval capabilities with GPT’s generative abilities, optimizing both the retrieval of relevant information and the generation of appropriate ICD codes.
- **Healthcare Application**: Specifically designed to assist **physicians** by streamlining the process of matching symptoms to ICD codes, improving diagnosis accuracy in Indonesia's healthcare system.

### Prerequisites
- Python 3.7+
- OpenAI API Key and Org ID
- LangChain
- Pandas

### Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/RAG-ICD-Classification.git
    cd RAG-ICD-Classification
    ```
2. Set up your OpenAI API Key and Org ID.

3. Run the notebook to test the system.

## Future Work
- Expand the knowledge base to include more languages.
- Fine-tune the model for specific regions and healthcare systems.
- Integrate with **Electronic Health Records (EHR)** systems for real-time ICD classification.

## Contact
For further questions or collaboration, feel free to contact me at hafizhry@umich.com.