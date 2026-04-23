# ML Model Containerization - MLOps Lab

## Objective

To containerize a machine learning model using Docker and run it as a web service.

## Tools Used

* Python
* Flask
* Docker

## Files in this Repository

* app.py → Flask API for prediction
* Dockerfile → Instructions to build Docker image
* requirements.txt → Dependencies

## Docker Commands

### Build Image

docker build -t ml-model .

### List Images

docker images

### Run Container

docker run -p 5000:5000 ml-model

### Check Running Containers

docker ps

### Stop Container

docker stop <container_id>

### Remove Container

docker rm <container_id>

## Output

The application runs on:
http://localhost:5000

## Conclusion

Successfully containerized and deployed a machine learning model using Docker.
