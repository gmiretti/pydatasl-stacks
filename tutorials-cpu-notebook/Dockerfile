FROM jupyter/tensorflow-notebook

# Install additional packages for PyDataSL 2017 tutorials
RUN conda install --quiet --yes 'pymc3' && \
    conda install --quiet --yes -c anaconda 'quiver_engine' && \
    conda clean -tipsy && \
    fix-permissions $CONDA_DIR