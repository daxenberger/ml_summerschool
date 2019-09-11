# ml_summerschool
Notebooks used for DEEP LEARNING FOR NLP & ARGUMENT MINING workshop at http://ml-school.uni-koeln.de.

## Setup Commands

Download and startup docker container:
``docker pull tensorflow/tensorflow:latest-py3-jupyter``
``docker run -it -v [your_local_workspace]:/tf -p [local_port]:8888 tensorflow/tensorflow:latest-py3-jupyter``, e.g.
``docker run -it -v ~/workspace/p1:/tf -p 8888:8888 tensorflow/tensorflow:latest-py3-jupyter``

Start Jupyter Notebook:
``http://localhost:[local_port]/?token=[token_shown_on_cmdline]``, e.g.
``http://localhost:8888/?token=2b72d3a948dfe5005aa59806c86eb1e339355e79da57eff``

Access the container shell
``docker ps`` to get the id of running containers
``docker exec -it [id_of_container] /bin/bash``
