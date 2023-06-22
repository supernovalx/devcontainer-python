FROM mcr.microsoft.com/devcontainers/python:0-3.9

USER $USER
ARG HOME="/home/$USER"
ENV PATH="${HOME}/.local/bin:$PATH"



RUN curl -sSL https://install.python-poetry.org | python3 - \
    && poetry config virtualenvs.in-project true
