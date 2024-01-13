FROM mambaorg/micromamba:1.5-jammy

COPY --chmod=777 environment.yml /tmp/environment.yml

RUN micromamba install -y -n base -f /tmp/environment.yml && \
    micromamba clean --all --yes

ENV PATH /opt/conda/bin:/home/mambauser/.local/bin:$PATH