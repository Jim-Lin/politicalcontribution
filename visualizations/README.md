## Jupyter Notebooks with Docker
### Data Science Notebook
```bash
$ docker run --rm -it -p 8888:8888 -v ~/politicalcontribution/visualizations/<xxx>:/home/jovyan/work jupyter/datascience-notebook

...
[C 15:58:38.426 NotebookApp]

    Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://localhost:8888/?token=<token>
...
```
