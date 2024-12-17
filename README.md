# Simple_Docker_Flask_1

docker-flask-app/

├── app.py

├── requirements.txt

├── Dockerfile



## 1. app.py

A simple Flask app:

[app.py](app.py)

## 2. requirements.txt<br>
Specify Flask and Werkzeug versions to ensure compatibility:

[requirements.txt](requirements.txt)<br>
## 3. Dockerfile<br>
Use Python as the base image and install the dependencies:

[Dockerfile](Dockerfile)

## 4. Build and Run the Docker Image<br>
### 1.Build the Docker Image:

Run the code in the terminal

`docker build -t docker-flask-app`

### 2.Run the Docker Container:

After running docker build run this code for running the container

`docker run -p 5000:5000 docker-flask-app`

### 3.Access the App in the Browser:<br>
Open http://localhost:5000 in your browser, you we see the text or message that is written in the flask.py

Hello, Flask with Docker!



