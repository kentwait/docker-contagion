# docker-contagion

Docker container for epidemic modelling and forward-time simulations using nxsim and contagion Python packages.
This container is based on `kentwait/miniconda-mpi` which means it can run MPI applications natively and through Python using Jupyter notebook.

## Install

	docker pull kentwait/docker-contagion

## Usage

The following command runs the container which launches a Jupyter notebook running Python 3.5 and IPython 4.1.1.

	docker run -d -p <port>:8888 -v <directory>:/home/docker/notebooks kentwait/docker-contagion

Replace `<port>` with 8888 (default) or any unused port on the host machine.
Replace `<directory>` with the directory where notebooks will be stored on the host machine.
