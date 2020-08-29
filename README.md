# workHORSE ShinyProxy dockerfile

This repo hosts the dockerfile for the [ShinyProxy](https://www.shinyproxy.io/) v2.3.1 that deploys the workHORSE app.

Every time a change is pushed on this repo a new docker container is built automatically at dockerhub. 

To install and push to dockerhub manually on would do,
```bash
sudo docker build -t [docker-USERNAME]/workhorse-shinyproxy . # replace [docker-USERNAME] with your docker usename
sudo docker login
sudo docker push [docker-USERNAME]/workhorse-shinyproxy . # replace [docker-USERNAME] with your docker usename