FROM jupyter/all-spark-notebook

RUN conda install --quiet --yes \
    'mlflow=1.4.0' \
    'psycopg2'

RUN jupyter lab build
