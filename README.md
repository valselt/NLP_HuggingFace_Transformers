<h1 align="center"> NLP With HuggingFace Transformers 🤖✨ </h1>
<p align="center"> This project contains various NLP pipelines using HuggingFace Transformers for different natural language processing tasks. </p>

<div align="center">

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">

</div>

## Content Overview 📚

1. **Zero-Shot Classification** 🎯

   - Classifies text into categories without the need for specific training data for those categories.

2. **Text Generation** ✍️

   - Generates coherent and relevant text based on a given prompt.

3. **Fill-Mask** 📝

   - Predicts missing words in a sentence, which is useful for text correction and completion.

4. **Named Entity Recognition (NER)** 🔍

   - Identifies and classifies entities in the text, such as names, organizations, and locations.

5. **Question Answering** ❓

   - Answers questions based on provided context, enabling information retrieval.

6. **Sentiment Analysis** ❤️

   - Analyzes text to determine the sentiment expressed, whether positive, negative, or neutral.

7. **Summarization** 📄
   - Creates a concise summary of longer texts while retaining key information.

## Setup ⚙️

### Locally (via Anaconda + Tensorflow) 🖥️[![My Skills](https://skillicons.dev/icons?i=java,kotlin,nodejs,figma&theme=light)](https://skillicons.dev)

1. **Install Anaconda**

   - Download Anaconda from [Anaconda Download](https://www.anaconda.com/download) and install it on your system.

2. **Open Anaconda Navigator**

   - Launch the Anaconda Navigator application.

3. **Create a New Environment**

   - Click on the "Environments" tab on the left sidebar.
   - Click "Create" at the bottom left.
   - Name the environment `tensorflow` and choose Python version `3.10.x`.

4. **Import TensorFlow Configuration**
   - Import the `tensorflow.yaml` file into your new environment to set up the required packages and dependencies.

### Locally via Ananconda + Tensorflow 🖥️

### Google Colab ☁️

1. **Install Transformers Library**
   - Run the following command in a cell:
     ```python
     !pip install transformers
     ```
   - This command installs the HuggingFace Transformers library, allowing you to utilize its powerful features for natural language processing tasks.
