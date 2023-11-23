```markdown
# Generative AI for Video Analytics with Vertex AI

## Project Overview
This repository contains the code for a project that demonstrates how to analyze the impact of influencers on YouTube regarding company or product opinions using Google's Generative AI capabilities. The project taps into the insights from a wide range of sources, and specifically focuses on influencers in the Tech & Finance sectors.

## What You'll Build
You will explore how the PaLM2 model and Langchain are utilized in VertexAI for a YouTube influencer analytics solution. The project showcases the process from installation and authentication of necessary packages to the initialization of the Vertex AI project and the deployment of a Gradio application for user interaction.

## Getting Started

### Installation
Clone this repository and install the required packages:

```bash
git clone https://github.com/vinthagunasekhar/Gen_AI_for_Video_Analytics_with_Vertex_AI.git
cd Gen_AI_for_Video_Analytics_with_Vertex_AI
pip install google-cloud-aiplatform langchain chromadb pytube youtube-transcript-api gradio
```

### Authentication
Ensure that your Google Cloud account has the Vertex AI user role. Authenticate your account using the instructions provided in the notebook.

### Project Initialization
Set your project ID in the code to initialize the Vertex AI project:

```python
import vertexai
PROJECT_ID = "<your-project-id>"
vertexai.init(project=PROJECT_ID)
```

## Usage
The notebook is divided into the following sections:

1. **Installation and Authentication**: Set up your environment and authenticate your Google Cloud account.
2. **Initialization**: Import the necessary libraries and initialize your Vertex AI project.
3. **Video Loading and Chunking**: Load and chunk the video for analysis.
4. **Embeddings Initialization**: Set up the Vertex AI embeddings.
5. **Storing and Retrieving Documents**: Use ChromaDB for indexing and retrieving document embeddings.
6. **Question-Answering Chain**: Create a chain to answer questions using the Vertex AI model.
7. **Defining Prompts**: Set up prompts to ask questions and receive answers.
8. **Gradio Integration**: Use Gradio to create a visual interface for interaction.

Run the provided notebook to go through each of these steps.

## Results
The model will provide insights into the opinions expressed by YouTube influencers about companies or products. The results can be visualized and interacted with using the integrated Gradio app.

## Contributing
Contributions to this project are welcome. Please follow the standard fork, branch, and pull request workflow.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- Google Cloud for Vertex AI , LLM model and Text-Bison from Langchain.
- Langchain for providing a streamlined approach to leveraging LLMs.
- The creators of the various Python packages used in this project and the respective youtube video owner.
- Code Vippasana Season-4 Team, Abhirami Sukumaran and Ravi Manjunatha.

## Contact
If you have any questions about the project, feel free to reach out.

Guna Sekhar Vintha - vinthagunasekhar@gmail.com
```
