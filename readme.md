# Steps to build and run the Docker container:
Create a Dockerfile and a requirements.txt file in the same directory.
In the terminal, navigate to that directory and build the Docker image:
```bash
docker build -t datascience-dev .
```

Once the image is built, run the container:
```bash
docker run -p 8888:8888 -v .:/workspace datascience-dev
```