# Indian Litigation ChatBot

# Index

- [Indian Litigation ChatBot](#indian-litigation-chatbot)
- [Index](#index)
- [About](#about)
  - [Techstack](#techstack)
- [How to setup](#how-to-setup)
  - [Clone the repo](#clone-the-repo)
  - [Install dependencies](#install-dependencies)
  - [Download the LLM Model](#download-the-llm-model)
- [Finally run the project](#finally-run-the-project)
- [License](#license)

# About

Our Chatbot for Crime Litigation Assistance is designed to provide accurate and contextually relevant legal information related to crime. It bridges the gap between legal knowledge and the general public by offering generic responses, referencing case laws, and citing research papers.

## Techstack

    - Python

# How to setup

## Clone the repo

Fork and clone the repo

```bash
git@github.com:shreyanshsinghks/Indian-Litigation-ChatBot-AIML.git
cd Indian-Litigation-ChatBot-AIML
```

## Install dependencies

```bash
pip install -r requirements.txt
```
## Download the LLM Model

To download the LLM Model click here [here](https://cloud.walletconnect.com/sign-in)
 - After when it is download copy that file and paste it in this project root directory

# Finally run the project

First run ingest.py file

```bash
python ingest.py
```
or (if above command does not work)

```bash
python3 ingest.py
```
After that run the model.py

```bash
chanlit run model.py -w
```
or (if above command does not work)
```bash
python -m chanlit run model.py -w
```

or (if above command does not work)
```bash
python3 -m chanlit run model.py -w
```

The project will be running on `localhost:8000`

To open the same application of another device for testing purposes, make sure that the device is connected to the same network as the device on which the project is running. Then visit `http://<IP_ADDRESS_OF_THE_DEVICE_RUNNING_THE_WEBAPP>:8000`

# License

The projects is licensed under [MIT](https://choosealicense.com/licenses/mit/)
