# 参考: https://github.com/jupyter/docker-stacks/blob/main/images/base-notebook/Dockerfile
FROM quay.io/jupyter/base-notebook

RUN mamba install --yes \
    'mlflow' \
    'scikit-learn' \
    'polars'
