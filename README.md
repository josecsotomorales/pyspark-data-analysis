# PySpark Data Analysis - Immigration and Temperature Data Project

## PySpark Jupyter Docker
It is very convenient to use Jupyter Notebook for an interactive development environment with Spark through PySpark on Jupyter Notebook.

To create a docker container run:
```
docker run -it --rm -p 8888:8888 jupyter/pyspark-notebook
```

To persist data, add a volume with `-v` flag:
```
docker run -it --rm -p 8888:8888 -v /Users/Jose/Workspace/capstone-dend:/home/Jose/work jupyter/pyspark-notebook
```

## Access to Jupyter Notebook
Open a browser and put the token geerated in the container logs:
```
http://localhost:8888/?token=e144d004f6652ae6406a78adf894621e62fdeb1fc57d02e8
```
