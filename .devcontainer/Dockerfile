FROM mambaorg/micromamba:1.5-jammy

RUN micromamba install -y -n base -c conda-forge -c bioconda \
        python=3.9 git gxx \
        r-base && \
    micromamba clean --all --yes

ENV PATH /opt/conda/bin:/home/mambauser/.local/bin:$PATH