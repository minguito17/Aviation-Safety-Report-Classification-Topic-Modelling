
# Aviation Safety Incident Classification and Topic Modeling

## Description / Overview

This project analyzes aviation safety reports using natural language processing (NLP) and machine learning. The goal is to automatically classify incident narratives into relevant safety categories and uncover hidden themes using topic modeling techniques. The source dataset is NASA’s Aviation Safety Reporting System (ASRS).

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Authors / Credits](#authors--credits)
- [Contact Information](#contact-information)
- [References / Acknowledgments](#references--acknowledgments)

## Installation

1. Clone the repository:
   ```
   git clone <YOUR_REPO_URL>
   cd <YOUR_REPO_DIRECTORY>
   ```

2. Install required Python libraries:
   ```
   pip install pandas numpy scikit-learn nltk spacy gensim matplotlib seaborn jupyter
   ```

3. Download NLTK stopwords and spaCy language models if needed:
   ```python
   import nltk
   nltk.download('stopwords')

   # For spaCy
   python -m spacy download en_core_web_sm
   ```

## Usage

- Open the Jupyter Notebook in the repository.
- Load the ASRS dataset (CSV).
- Run the cells to:
  - Clean, tokenize, and lemmatize text.
  - Train supervised models (Naive Bayes, Logistic Regression, SVM).
  - Evaluate accuracy and precision.
  - Apply topic modeling (LDA, NMF, LSA).
  - Visualize topic-word distributions and top terms.

## Features

- Classification of aviation safety narratives into categories:
  - Aircraft
  - Human Factors
  - Weather
  - Environment
  - ATC/Navigation Equipment
- Unsupervised topic modeling to uncover hidden themes.
- Preprocessing pipeline: cleaning, tokenization, stopword removal, lemmatization.
- Uses TF-IDF for better feature weighting.
- Model evaluation with accuracy, precision, recall, confusion matrix.

## Contributing

Pull requests are welcome. For major changes, open an issue first to discuss your ideas or improvements.

## License

This project is for academic and research use only.

## Authors / Credits

- Marinela Inguito
- Bobby Marriott
- Edgar Rosales

## Contact Information

Please contact the team through your university or course platform for any questions.

## References / Acknowledgments

- NASA Ames Research Center. Aviation Safety Reporting System (ASRS). [https://asrs.arc.nasa.gov/](https://asrs.arc.nasa.gov/)
- Python NLP libraries: NLTK, spaCy, gensim, scikit-learn
