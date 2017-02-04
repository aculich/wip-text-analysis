# docker build --rm --tag wip-text-analysis .

FROM jupyter/datascience-notebook

RUN conda install --name python2 -y nltk

RUN pip2 install html2text

# RUN source activate python2 *this doesn’t work

# RUN python -m nltk.downloader stopwords

# RUN python -m nltk.downloader words