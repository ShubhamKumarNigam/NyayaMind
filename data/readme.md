Nyayamind - Data Repository

This repository contains the datasets used for training, validating, and testing various models for structured legal reasoning in legal documents. The datasets are provided in JSON formats. Below is a detailed explanation of the dataset organization and file structure. This repository also contains the NyayaMindDB dataset that forms the core of the RAG setup for NyayaMind system. The NyayaMindDB consists of 4 different collections 

- Supremene Court Judgments (SC)
- High Court Judgment (HC)
- State Acts (SA)
- Central Acts (CA)

The NyayaMindDB dataset is available in CSV format. 

Use the respective ingestion scripts to create collections in RAG setups - Endee, Vespa, Milvus for the above CSV files. 

Copy the following files in a folder named as dataset inside the code directory to run training or inference scripts. 

- train.json
- val.json
- test.json

data/
│
├── train.json            # Training data partition
├── val.json              # Validation data partition
├── test.json             # Test data partition
├── SC/                   # Supreme Court records
├── HC/                   # High Court records
├── SA/                   # State Acts
└── CA/                   # Central Acts