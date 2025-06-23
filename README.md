# SmallLM-SP25
Small Language Models via GPT4All and OpenAI API

This work is based on work from Greg Merritt - [Ollama Demo](https://github.com/ds-modules/ollama-demo) which was based on work from Pamela Fox [Ollama Python Playground](https://github.com/pamelafox/ollama-python-playground). The OpenAI notebook is based on one from Jedidia Tsang for Data 6 [Proeject Part 2](https://github.com/data-6-berkeley/materials-fa24/blob/main/proj/project-part2.ipynb)

I am not an expert in the field and the speed these things are changing this material and even the approach will be soon obsolete. But it was my objective to illustrate in some small and incremental way what is going on with these models which are changing out lives and disrupting our society every day. I taught these in the last week of my class [Data Science for Economists](https://www.econ148.org/) so these students had 1) already seen quite a bit of Python programming, and 2) I motivated the discussion around the cost of models and the cost of tokens eg elemental economics of language models.   

## There a few key issues for setup
- In the Small Models notebook - the small models "weights" must be downloaded from Huggingface. I include here a separate notebook for this. When I taught this in class I did this step myself, then put the models into a shared directory on the Juptyerhub where I was teaching and where the students could read them from.
- **which models?** I was going for the smallest of models. Partly to fit on the parameters of the teaching Jupyterhub at UC Berkeley where students had 4gb ram and no CPU. But that is precisely what I was trying too teach eg what can a tiny model do. So specifically I used models around a 1gb - which means 1b parameters and quantized.
- In the OpenAI API Notebook you need an API key. I opened an acccount and put $50 down and after 150 students had used the API we had used $0.05 = 5 cents worth of API access.  But that is a learning outcome.

##  Link to Run on Cal-ICOR hub - June 2025
[Interact Link](https://jupyter.cal-icor.org/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fds-modules%2FSmallLM-SP25&urlpath=lab%2Ftree%2FSmallLM-SP25%2F)
