# ml-template-tabular

## Description
This repo collects guidelines, recommendations and useful links and sources for a ML (supervised or unsupervised) student project using tabular data. The structure and content of the Jupyter notebooks represent a very high-level outline of a student ML project and should not be considered as an exact recipe.

## Setting up your workspace
1. Register and create an account on [GitHub](https://github.com/). **Familiarise youself with this resource as it is going to be the main place for code storage and version control.**
2. Create **public** repo on GitHub, give it a sensible name, make sure you include README.md.
3. Open your repository, click on the **Code** green button, select 'Codespaces' tab and click 'Create codespace on master'. Codespace looking something like this:

![codespace](./assets/img/codespace.jpg)

will be created. The colour theme may be different and can be configured.

4. Create jupyter_notebooks folder. This can be done via project explorer of terminal using command line.
5. In this folder create 1_data_collection.ipynb file. There will be more Jupyter notebooks in the project covering the entire ML pipeline. File format *.ipynb will authomatically be recognised as Jupyter Notebook.
6. Open this notebook and select jupyter kernel. **You need to choose Python**
7. In the project root directory create two files:
- .gitignore
(to list files/folders not to be pushed to GitHub due to size limitation or sensitive information, such as secret keys)
- requirements.txt (to list packages required to run the project and indicate their versions for compatibility)
8. **Familiarise yourself with the [Jupyter Notebok](https://jupyter.org/) as it is going to be your main development tool in this project.**

Your are now pretty much set to start your ML journey.

## Data acquisition
In this project you will obtain dataset (fitting the context of your project context) from [Kaggle](https://www.kaggle.com/)

## ML pipeline concept

**ML pipeline** is the core concept in the field of ML and it is particularly important for tabular data. It is therefore critical to understand all steps which it follows. The is a huge number of books and online sources you can use.

## CRISP-DM

The **Cross-industry standard process for data mining**, known as **CRISP-DM**, is an open standard process model that describes common approaches used by data mining experts. It is the most widely-used analytics model [Wiki](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining). Get understanding of the workflow and main steps.


## Required libraries

Essential Python libraries:

[NumPy](https://numpy.org/)

[Pandas](https://pandas.pydata.org/)

[MatPlotLib](https://matplotlib.org/)

[Feature-Engine](https://feature-engine.trainindata.com/en/latest/)

[Scikit-learn](https://scikit-learn.org/stable/index.html)

Depending on the scope of your project you might need other Python packages.





### Useful links:
1. [Markdown on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

2. [Conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)

### Where to search for help if you are stuck.

### Git commands:
#### Usually go in sequence:
---
`git add --all`
(or `git add .`) (add changes to the commit)

`git commit -m "add commit message here"` (commit changes)

`git push` (push to GitHub)

---

`git status` (check current commit status)

## Credits
**It is ok to reuse someone else's code. It is absolutely not ok to keep quiet about it.**