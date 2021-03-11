FROM continuumio/miniconda3:4.7.10

COPY environment.yaml /home
WORKDIR /home
RUN conda env create -f environment.yaml
ENV PATH /opt/conda/envs/eyespace-python/bin:$PATH
