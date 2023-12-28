FROM mambaorg/micromamba:1.5-jammy

RUN micromamba install -y -n base -c conda-forge -c bioconda \
        python=3.9 git gcc \
        r-base r-essentials r-seurat r-seuratobject r-liger r-conos r-harmony bioconductor-batchelor && \
    micromamba clean --all --yes