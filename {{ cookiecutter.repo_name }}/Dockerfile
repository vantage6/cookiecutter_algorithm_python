# basic python3 image as base
FROM harbor2.vantage6.ai/algorithms/algorithm-base

# This is a placeholder that should be overloaded by invoking
# docker build with '--build-arg PKG_NAME=...'
# TODO: should this be repo_name or algorithm_name?
ARG PKG_NAME="{{ cookiecutter.repo_name }}"

# install federated algorithm
# TODO: Check if this is correct
COPY ./ /app
RUN pip install /app

ENV PKG_NAME=${PKG_NAME}

# Tell docker to execute `docker_wrapper()` when the image is run.
CMD python -c "from vantage6.tools.docker_wrapper import docker_wrapper; docker_wrapper('${PKG_NAME}')"