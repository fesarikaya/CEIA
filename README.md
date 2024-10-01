# CEIA: Contextual Embedding Inversion Attack

## Overview

CEIA (Contextual Embedding Inversion Attack) is a novel adversarial attack method targeting BERT-based models, particularly question-answering systems. This repository contains the implementation and documentation of the CEIA method.

## Files

1. `CreateAttackDataset_CEIA.ipynb`: Jupyter notebook containing the implementation of the CEIA method.
2. `Contextual Embedding Inversion Attack.pdf`: Detailed documentation of the CEIA method.

## About CEIA

CEIA is a sophisticated approach to creating adversarial examples for BERT-based models. Key features include:

- **Semantic Inversion**: Alters the meaning of parts of the context and questions without making them grammatically incorrect.
- **Contextual Understanding Exploitation**: Leverages BERT's own contextual embeddings to create effective adversarial examples.
- **Preservation of Key Information**: Keeps answer phrases intact, ensuring questions remain answerable.
- **Noun Chunk Targeting**: Focuses on inverting noun chunks for maximum impact.
- **Robustness Testing**: Tests the robustness of QA models against subtle semantic changes.

## Implementation

The main implementation is in `CreateAttackDataset_CEIA.ipynb`. This notebook includes:

- Import and model loading
- BERT embedding generation
- Antonym phrase finding
- Main CEIA attack function
- SQuAD dataset processing

## Usage

To use the CEIA method:

1. Ensure you have the required dependencies installed (spaCy, PyTorch, Transformers).
2. Open and run `CreateAttackDataset_CEIA.ipynb` in a Jupyter environment.
3. The notebook will guide you through the process of applying the CEIA attack to the SQuAD dataset.

## Documentation

For a detailed explanation of the CEIA method, including its theoretical background and potential applications, please refer to https://doi.org/10.5281/zenodo.13869177 

## Citation

If you use this method in your research, please cite:
Sarikaya, F. (2024). Contextual Embedding Inversion Attack (CEIA): A Novel Adversarial Method Targeting BERT Models. Department of Informatics, University of Sussex, Brighton, UK.

## Contact
Email: ferhatsarikaya@hotmail.com
