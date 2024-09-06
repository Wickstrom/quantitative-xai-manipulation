
This repository contains code for the paper **[From Flexibility to Manipulation: The Slippery Slope of XAI Evaluation](https://openreview.net/forum?id=fd7g9nwI2R)** by Wickstrøm et al., 2024. See the notebook "getting_started_with_manipulation.ipynb" to get started with the code. 

<!--[![Getting started!](https://colab.research.google.com/assets/colab-badge.svg)](anonymous)-->
<!--![Python version](https://img.shields.io/badge/python-3.7%20%7C%203.8%20%7C%203.9%20%7C%203.10%20%7C%203.11-blue.svg)-->
<!--[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)-->
<!--[![PyPI version](https://badge.fury.io/py/metaquantus.svg)](https://badge.fury.io/py/metaquantus)-->
<!--[![Python package](https://github.com/annahedstroem/MetaQuantus/actions/workflows/python-publish.yml/badge.svg)](https://github.com/annahedstroem/MetaQuantus/actions/workflows/python-publish.yml/badge.svg)-->
<!--[![Launch Tutorials](https://mybinder.org/badge_logo.svg)](anonymous)-->

## Citation

If you find this work interesting or useful in your research, use the following Bibtex annotation to cite us:

```bibtex
@inproceedings{
    anonymous2024from,
    title={From Flexibility to Manipulation: The Slippery Slope of {XAI} Evaluation},
    author={Wickstrøm, Kristoffer K and H{\"o}hne, Marina and Hedstr{\"o}m, Anna"},
    booktitle={ECCV 2024 Workshop on Explainable Computer Vision: Where are We and Where are We Going? (Proceedings Track)},
    year={2024},
    url={https://openreview.net/forum?id=fd7g9nwI2R}
}
```
This work has been published as a part of the ECCV 2024 Workshop on Explainable Computer Vision: Where are We and Where are We Going? (Proceedings Track).


## Paper highlights 📚

The lack of ground truth explanation labels is a fundamental challenge for quantitative evaluation in explainable artificial intelligence (XAI). This challenge becomes especially problematic when evaluation methods have numerous hyperparameters that must be specified by the user, as there is no ground truth to determine an optimal hyperparameter selection. It is typically not feasible to do an exhaustive search of hyperparameters so researchers typically make a normative choice based on similar studies in the literature, which provides great flexibility for the user. In this work, we illustrate how this flexibility can be exploited to manipulate the evaluation outcome. We frame this manipulation as an adversarial attack on the evaluation where seemingly innocent changes in hyperparameter setting significantly influence the evaluation outcome. We demonstrate the effectiveness of our manipulation across several datasets with large changes in evaluation outcomes across several explanation methods and models. Lastly, we propose a mitigation strategy based on ranking across hyperparameters that aims to provide robustness towards such manipulation. This work highlights the difficulty of conducting reliable XAI evaluation and emphasizes the importance of a holistic and transparent approach to evaluation in XAI.

### Thank you

We hope our repository is beneficial to your work and research. If you have any feedback, questions, or ideas, please feel free to raise an issue in this repository. Alternatively, you can reach out to us directly via email for more in-depth discussions or suggestions. 

📧 Contact us: 
- Kristoffer Wickstrom: [kristoffer.k.wickstrom@uit.no](mailto:kristoffer.k.wickstrom@uit.no)
- Anna Hedström: [hedstroem.anna@gmail.com](mailto:hedstroem.anna@gmail.com)

Thank you for your interest and support!
