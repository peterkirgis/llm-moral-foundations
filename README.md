# Differences in the Moral Foundations of Large Language Models

This repository contains the code and data for the paper "Difference in the Moral Foundations of Large Language Models" by Peter Kirgis. 


## Project Overview

The paper utliizes a synthetic experiment administered to 21 large language models from most major model providers using Jonathan Haidt's influential moral foundations theory (MFT) to elicit diverse value judgments from LLMs. Using multiple descriptive statistical approaches, the paper documents the bias and variance of large language model responses relative to a human baseline in the original survey. The results suggest that models rely on different moral foundations from one another and from a nationally representative human baseline, and these differences increase as model capabilities increase. 

## Repisitory Structure

The repository is organized into the following folders:
- `analysis/`: All code used to analyze the data and generate figures in the paper. 
    - `final_analysis.ipynb`: all code used to generate each plot and table in the paper.
- `data/`: All data used in the paper, including the survey responses from the models and the human baseline. 
    - `embeddings/`: results of the FrameAxis embedding analysis using different moral foundations dictionaries.
    - `results/`: results of the synethetic experiment, including separate files for sampled and logprob responses, and a unified `cleaned_model_responses.csv` file used in the `analysis/` folder.
    - `survey/`: the original survey data from Clifford et al. (2015), with the full initial survey and a shortened version `vignettes_short.csv` used in the paper.
- `plots/`: All plots used in the paper.
- `surveys/`: The code to run the Expected Parrot surveys in the final analysis.

## Requirements

Install the required packages using the following command:

```bash
pip install -r requirements.txt
```




