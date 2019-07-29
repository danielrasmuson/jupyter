To have jupyter always avaiable at http://127.0.0.1:8888 when you computer boots up run the following command...

```
docker run -d -p 8888:8888 -v ~/jupyter:/home/jovyan --restart=always jupyter/scipy-notebook:17aba6048f44
```