# Retrieval-Augmented Generation (RAG) Focused on Farsi Language

## Overview

This project implements Retrieval-Augmented Generation (RAG) to enhance the quality and accuracy of information retrieval and response generation in the Farsi language. Leveraging advanced technologies and models, this project aims to provide precise and up-to-date responses by integrating retrieval mechanisms with generation models.

## Technologies Used

- **Models**: microsoft/Phi-3-mini-4k-instruct
- **Data Processing**: Read and extracted data from files, cleaned and normalized data using [Hazm](https://github.com/roshan-research/hazm) (Farsi NLP Toolkit)
- **Embeddings**: Created embeddings for deep learning models
- **Paraphrasing**: Utilized paraphrasing techniques to enhance generated responses

## Project Steps

1. **Install Dependencies**: Installed necessary libraries and dependencies to work with the tools and models required for the project.
2. **Load and Extract Dataset**: Loaded the dataset and extracted relevant questions and answers from files to make data usable.
3. **Upload Data**: Uploaded data to [Google Drive](https://drive.google.com/file/d/10ubJZ0UgGM9wAHHuyfrhgRAuauLpZjAK/view?usp=sharing) to avoid re-uploading in each session.
4. **Read Data**: Addressed challenges related to various data formats and extracted information into a usable format.
5. **Data Splitting**: Split data into training and testing sets in an 80-20 ratio for model evaluation.
6. **Data Cleaning and Normalization**: Used multiple tools for Farsi text normalization, with [Dadmatools](https://github.com/Dadmatech/DadmaTools) (A Python NLP Library for Farsi) and [Hazm](https://github.com/roshan-research/hazm) (Farsi NLP Toolkit) providing the best results.
7. **Create Embeddings**: Generated embeddings for preparing data for deep learning models.
8. **Load Pre-trained Model**: Utilized the microsoft/Phi-3-mini-4k-instruct model for the RAG implementation.
9. **Question Answering**: Configured the model to generate responses and utilized it to answer questions effectively.
10. **Evaluation**: Assessed the quality of responses using cosine similarity and transformer sentence models.
11. **Paraphrasing**: Applied paraphrasing techniques to further refine generated answers.

## Results

The implementation of RAG has significantly improved the accuracy and quality of responses. The integration of models has enabled the system to provide precise and relevant answers. Additionally, paraphrasing has contributed to the enhancement of response quality.

## Challenges

- **Library Compatibility**: Faced issues with library versions, particularly with Torch, which were resolved by updating to a suitable version.
- **Normalization Tools**: Encountered difficulties finding effective normalization tools for Farsi, with Dadmatools and Hazm ultimately being the most effective.
- **Data Handling**: Manual data handling and custom data loading presented challenges.

## Learnings and Future Work

This project provided valuable insights into RAG technology and its application to Farsi language processing. Future work may include exploring more accurate models and improving data processing techniques. Additionally, optimizing performance and expanding the system's capabilities for other languages could be considered.

## Contributing

Contributions to improve the project are welcome. Please follow the standard GitHub workflow for contributions, including forks, pull requests, and issue tracking.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
