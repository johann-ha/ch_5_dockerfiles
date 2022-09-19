FROM miniconda3

LABEL maintainer=@joha80

RUN conda update conda && \
    conda install --quiet --yes ipython && \
    conda clean -tipsy

CMD [ "ipython" ]
