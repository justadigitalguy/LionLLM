# LionAI Enhanced with LionLLM - A Knowledge Hub for Publicis Groupe

This application, developed as a Proof of Concept (POC), is a significant step towards the goal of establishing a group-wide knowledge repository for Publicis Groupe. Integrating the capabilities of a Large Language Model (LLM) named LionLLM, the application creates a dynamic information pool that consolidates experiences and insights from various global operations within the Publicis Groupe.

## Features

- **Document Upload:** The application allows users to upload multiple PDF documents. These documents represent the diverse datasets - such as presentation decks, campaign reports, and other relevant documents - across different agencies under Publicis Groupe.

- **Text Extraction & Embeddings:** The application extracts text data from the uploaded documents and creates chunks of text data. It then generates embeddings for these text chunks using an LLM.

- **Conversational AI:** Leveraging the capabilities of the LionLLM, the application incorporates a conversational AI feature. This feature enables the application to respond to user queries with relevant information extracted from the uploaded documents.

- **Real-time Insights:** With the combination of document processing, LLM embeddings, and conversational AI, the application provides real-time insights to users. These insights could be relevant sections of text from the uploaded documents that answer user queries.

- **Knowledge Repository:** Above all, the application forms a foundational block for creating a group-wide knowledge repository. This can transform the way Publicis Groupe accesses and utilizes internal knowledge for improved decision-making and enhanced client interactions.

## Setup & Installation

Before proceeding with the setup, ensure that Python 3.7+ is installed on your machine. Follow the steps below to setup the application:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the required packages by running `pip install -r requirements.txt`.
4. Create a `.env` file in the root directory of the project and populate it with the required environment variables (refer to `.env.example` file in the repository for the required variables).
5. Run the application with the command `streamlit run app.py`.

> Note: The application uses Streamlit for the front-end interface, and the back-end logic is primarily written in Python. Also, the application employs watchdog for monitoring changes in file and directories.

## Contribution

We welcome contributions to enhance this POC. Feel free to fork the repository, make changes, and open a pull request. If you have any questions or suggestions, please open an issue.

## Disclaimer

This application is a mockup test for the Publicis Groupe internal LLM model, LionLLM. It serves as a foundational POC for creating a group-wide knowledge hub, aiming to bolster LionAI by integrating LionLLM. It is not intended for commercial use and is not officially affiliated with Publicis Groupe.

## License

This project is open source and available under the [MIT License](LICENSE).
