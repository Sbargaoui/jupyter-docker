FROM jupyter/datascience-notebook

WORKDIR /home/notebook/

RUN pip install findspark

CMD jupyter notebook --port=8888 --no-browser --ip=0.0.0.0 --allow-root

