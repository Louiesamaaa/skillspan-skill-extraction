# Skill Extraction from Job Postings

Extracting skills and knowledge from job posting sentences, comparing a CRF baseline, BERT, and JobBERT.

## Status
🚧 In progress: data cleaning and EDA done; baseline next.

## Data
[SkillSpan](https://huggingface.co/datasets/jjzha/skillspan) (Zhang et al., NAACL 2022), CC-BY-4.0.
Not stored in this repo. Run `notebooks/01_data_exploration_and_cleaning.ipynb` to download it into `data/`.

## Notebooks
1. `01_data_exploration_and_cleaning`: load, validate, fix broken spans
2. `02_eda`: label distribution, span lengths, sentence lengths

## Setup
pip install -r requirements.txt
