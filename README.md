cd flask-kubernetes

docker build . -t flask-kubernetes-example

docker run -d -p 5000:5000 flask-kubernetes

curl http://localhost:5000

```
