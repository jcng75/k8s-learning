# k8s-learning report

This documetnation covers what was done differently in comparison to DevOps Directive's video.  

- Instead of running `uvicorn`, I followed the documentation to run `fastapi dev app/main.py`
- Ran `docker build -t k8s-learning .` to build the Dockerfile and assign it a tag name
- Ran `docker run -p 8080:80 k8s-learning`