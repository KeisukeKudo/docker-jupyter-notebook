# docker-jupyter-notebook
### It takes time to complete  
```bash
$ docker-compose up -d
```
### Please check the log when it starts
```bash
$ docker-compose logs

notebook_1  | [C 06:37:14.395 LabApp]
notebook_1  |
notebook_1  |     To access the notebook, open this file in a browser:
notebook_1  |         file:///home/jovyan/.local/share/jupyter/runtime/nbserver-20-open.html
notebook_1  |     Or copy and paste one of these URLs:
notebook_1  |         http://(container-id or 127.0.0.1):8888/?token=XXXXXXXX
```
### Please copy and access the URL of the log
```
http://127.0.0.1:8888/?token=XXXXXXXX
```

That's all.
