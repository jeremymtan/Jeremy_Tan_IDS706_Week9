[![Install](https://github.com/jeremymtan/Jeremy_Tan_IDS706_Week9/actions/workflows/install.yml/badge.svg)](https://github.com/jeremymtan/Jeremy_Tan_IDS706_Week9/actions/workflows/install.yml)
[![Format](https://github.com/jeremymtan/Jeremy_Tan_IDS706_Week9/actions/workflows/format.yml/badge.svg)](https://github.com/jeremymtan/Jeremy_Tan_IDS706_Week9/actions/workflows/format.yml)
[![Lint](https://github.com/jeremymtan/Jeremy_Tan_IDS706_Week9/actions/workflows/lint.yml/badge.svg)](https://github.com/jeremymtan/Jeremy_Tan_IDS706_Week9/actions/workflows/lint.yml)
[![Test](https://github.com/jeremymtan/Jeremy_Tan_IDS706_Week9/actions/workflows/test.yml/badge.svg)](https://github.com/jeremymtan/Jeremy_Tan_IDS706_Week9/actions/workflows/test.yml)
## Cloud-Hosted Notebook Data Manipulation

## Google Collab Link
[Google Collab Link](https://colab.research.google.com/github/jeremymtan/Jeremy_Tan_IDS706_Week9/blob/main/main.ipynb)

### Directory Tree Structure 
```
Jeremy_Tan_IDS706_Week9
├── .devcontainer/
│   ├── devcontainer.json
│   └── Dockerfile
├── .github/
│   └── workflows/
│       ├── format.yml
│       ├── install.yml
│       ├── lint.yml
│       └── test.yml
├── .gitignore
├── Dockerfile
├── LICENSE
├── main.ipynb
├── main.py
├── Makefile
├── mylib/
│   ├── __init__.py
│   └── lib.py
├── README.md
├── repeat.sh
├── requirements.txt
├── setup.sh
├── test_lib.py
└── test_main.py
```
### Purpose of Project
TThe project's purpose is to demonstrate proficiency in setting up and utilizing a cloud-hosted Jupyter Notebook environment, specifically using Google Colab. This includes performing data manipulation tasks on a provided sample dataset. 

## Preparation 
1. Open codespaces 
2. Wait for container to be built and pinned requirements from `requirements.txt` to be installed 
3. If running locally, `git clone` the repository and use `make install`

## Check format and test errors
1. Format code `make format`
2. Lint code `make lint`

## References 
https://github.com/nogibjj/python-ruff-template
