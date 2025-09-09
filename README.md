# Data_Mining_Judgement_Topic_Classification
The project tends to create a model to classify judgements in various courts of the Zambian legal system, the CRISP-DM model is used to make the model.
With the use of tools like jupyter and google colab to implement the project 

# Data Description (CRISP-DM Step 2.2) #
The document describes the dataset in our project: Classification of legal Judgements into Law Categories.
- Source:
  - Zambia Legal Information Institute (ZambiaLII)
  - National Assembly of Zambia
- Time Period Covered: 2010-2024
- Size: ~...

foler structure:
data/
 ├── raw/              # Original scraped files (PDF/HTML)
 ├── clean/            # Preprocessed text files
 ├── doc_metadata.csv  # Metadata with case info
 └── annotations.csv   # Labels added by P3 (law categories)
