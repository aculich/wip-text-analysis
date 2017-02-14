# docker build --rm --tag wip-text-analysis .

# start with datascience notebook
FROM jupyter/datascience-notebook

# add packages in import
RUN conda install --name python2 -y nltk
RUN pip2 install html2text

#get packages from nltk.downloader (it was installed in conda python2 environment)
RUN /opt/conda/envs/python2/bin/python -m nltk.downloader stopwords words wordnet