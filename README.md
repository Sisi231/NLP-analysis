![Python](https://img.shields.io/badge/Python-3.x-blue)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)
![NLP](https://img.shields.io/badge/Focus-NLP-green)
![Status](https://img.shields.io/badge/Project-Analysis--Focused-lightgrey)

# UN Security Council Discourse Analysis
Data-driven analysis of UN discourse on Ukraine and Gaza using NLP to uncover differences in geopolitical framing and narrative priorities.

This project presents a **comparative discourse analysis** of United Nations communications, focusing on language used by the **UN Security Council (UNSC)** and the **Office of the United Nations High Commissioner for Human Rights (OHCHR)**.

The analysis examines institutional narratives across two major conflicts:

* Ukraine War
* Gaza Conflict

Although implemented using Python and text-processing techniques, this project is fundamentally an **analytical study of political language**, where programming serves as a tool to enable structured insight.

## Key Objective

To investigate how institutional discourse differs across geopolitical contexts by analyzing:

* Narrative framing
* Thematic emphasis
* Language consistency
* Humanitarian focus

## Tech Stack

* **Python 3**
* **Jupyter Notebook**
* **Pandas** – data structuring and manipulation
* **NLTK / spaCy** – text processing and tokenization
* **re (Regex)** – text cleaning and filtering
* **Matplotlib / Seaborn** *(optional)* – visualization

## Project Structure

├── Notebooks-and-Data/
    ├── Palestine-vs-Israel.ipynb          
    ├── Ukraine-vs-Russia.ipynb
    ├── Combined_notebook.ipynb
    ├── .ipynb_checkpoints
    └── Data
        ├── pic2.jpg
        ├── UkraineDocuments
        └── PalestineDocuments
├── Presentation/
    └── Data Science Presentation
├── Report/
    └── Report
├── README.md

## Methodology
### 1. Data Collection

* Official UN and OHCHR documents
* Focus on conflict-related communications
* Keyword-based filtering for relevance

### 2. Data Preprocessing (Programmatic Pipeline)
A structured pipeline was developed to prepare the text:

* Removal of formatting and metadata
* Text normalization (lowercasing, token standardization)
* Filtering for conflict-specific terms
* Segmentation into analyzable units

This ensures **consistency and comparability across datasets**.

### 3. Text Analysis
The project applies computational techniques to extract patterns from text:

* **Tokenization & frequency analysis** → identify dominant terms

* **Thematic grouping** → detect recurring narratives

* **Comparative analysis** → contrast:

  * UNSC vs OHCHR
  * Ukraine vs Gaza

* **Tone evaluation** → assess neutrality vs sensitivity

### 4. Interpretation

The outputs are analyzed qualitatively to understand:

* Narrative consistency vs variability
* Institutional framing differences
* Influence of geopolitical context on language

## Key Findings

* Ukraine discourse shows **greater consistency and structured framing**
* Gaza discourse shows **higher variability and sensitivity**
* Institutional language reflects **underlying political dynamics**
* Differences between UNSC and OHCHR highlight **distinct institutional roles**

## Installation & Setup

### 1. Clone the repository
### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate    # On Mac/Linux
venv\Scripts\activate       # On Windows
```

### 3. Install dependencies
```bash
pip install pandas nltk spacy matplotlib seaborn
```
## How to Run

### Option 1: Jupyter Notebook (Recommended)
```bash
jupyter notebook
```
* Open:

  * `notebooks/gaza.ipynb`
  * `notebooks/ukraine.ipynb`

Run cells sequentially to reproduce the analysis.

## Reproducibility

The project is designed to be reproducible:

* All preprocessing steps are programmatically defined
* Analysis follows a structured pipeline
* New datasets can be integrated with minimal changes

## Key Takeaway
This project demonstrates how **computational methods can support deep analytical work**, particularly in:

* political analysis
* discourse studies
* text-based data science

It emphasizes that the value lies not just in code, but in the **insights derived from structured analysis**.

## Future Improvements

* Apply advanced NLP techniques (e.g., topic modeling, embeddings)
* Expand dataset to additional conflicts or institutions
* Build interactive dashboards for visualization

## Final Note

This is not just a coding project—it is a **data-driven analytical investigation**.
The programming component enables the analysis, but the primary goal is to **understand how institutional language reflects global power and priorities**.

## Author
Silvia Andreeva
