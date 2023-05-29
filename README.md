# Better-ChatGPT

This is a professional version of the Better-ChatGPT project, developed by harshitethic. It is a clone of ChatGPT with enhanced features and improved code. You are welcome to contribute to the project by suggesting improvements or making code changes.

<img width="1470" alt="image" src="https://user-images.githubusercontent.com/98614666/232768610-fdeada85-3d21-4cf9-915e-a0ec9f3b7a9f.png">

## Introduction

Better-ChatGPT is an interactive chatbot powered by the GPT-3.5 language model. It allows users to have conversations with the AI model and provides various functionalities, including conversation deletion confirmation, user preferences, theme customization, conversation loading/exporting, speech input/output, file loading, and more.

## Getting Started

To get started with Better-ChatGPT, follow the steps below:

### Prerequisites

Before setting up Better-ChatGPT, ensure that you have Python 3.8 installed on your system. You can download Python from the official website: [Python Downloads](https://www.python.org/downloads/)

### Cloning the Repository

Clone the Better-ChatGPT repository by running the following command:

git clone https://github.com/harshitethic/better-chatgpt.git

### Setting up a Virtual Environment

To set up a virtual environment for Better-ChatGPT, perform the following steps:

1. Navigate to the root directory of the project:

cd better-chatgpt

2. Create a new virtual environment by running the command:

python -m venv venv

3. Activate the virtual environment with the following command:

source venv/bin/activate

(Note: If you are using the fish shell, the command will be slightly different. For Windows, the command will also differ.)

4. Install the required dependencies by executing the following command:

pip install -r requirements.txt

### Configuring the Application

To configure Better-ChatGPT, you can set certain properties either via environment variables or through the `config.json` file. The environment variables take priority over the `config.json` file.

| Field               | Env Variable    | config.json    | Examples                                           |
|---------------------|-----------------|----------------|----------------------------------------------------|
| The OpenAI API Key  | OPENAI_API_KEY  | openai_key     | sk-...                                              |
| The OpenAI Base URL | OPENAI_API_BASE | openai_api_key | https://api.openai.com <br> http://my-reverse-proxy/ |

If you need to run your queries through a reverse proxy, such as Azure's OpenAI endpoints, use the Base URL field.

### Running the Application

To run Better-ChatGPT, ensure that the virtual environment is active and execute the following command:

python run.py

### Docker

The easiest way to run Better-ChatGPT is by using Docker. Execute the following command:

docker-compose up

## Contribution

You are welcome to contribute to the improvement of Better-ChatGPT by suggesting code enhancements or providing valuable feedback.

## To-Do List

- [x] Double confirm when deleting conversation
- [x] Remember user preferences
- [x] Theme changer
- [ ] Loading/exporting a conversation
- [ ] Speech output and input (elevenlabs; ex: [Chat with GPT](https://github.com/cogentapps/chat-with-gpt))
- [ ] Load files, ex: [GPT4 PDF Chatbot LangChain](https://github.com/mayooear/gpt4-pdf-chatbot-langchain)
- [ ] Better documentation
- [ ] Use React or a faster backend language? (Newbies may be more confused and discouraged to use it)

Feel free to enhance the code and suggest improvements.
