## Jupyter Notebook repository
- pull Anaconda3 image

```
docker pull suganoyuya/anaconda3
```
- run a container with Jupyter

```
docker run -p 3000:8888 -v ${PWD}/notebooks:/opt/notebooks anaconda3
```
