# Financial Report Retrieval Augmented Generation

## Objective:
There can be multiple similar industry stock that are interesting to analyst but time consuming to go through each of the report. This repo is using current RAG method to index in one or more company and make comparison between two or more different companies.

## Stack in use
- llama-parse for document parsing
- GPT4o-mini for query and embedding
- langsmith for observability

## STEP 1 : Start
```
To start with :
edit .env with llamaindex and openAI API key.
llamaindex : sign up at https://cloud.llamaindex.ai > API Key > Generate New Key
openAI : sign up and go to https://platform.openai.com/api-keys > create new secret key

Insert both key into .env
```

## STEP 2: Report parser
run through notebook/financial_report.ipynb

## Suggestion of what to add and enhance
Please log functionalities that you wish to add or enhance in issues section.

## Contributor are all welcome
