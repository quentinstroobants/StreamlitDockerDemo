# StreamlitDockerDemo
Demo repo for the course Tooling for Data Scientist at HEC.
The app consists of the Uber demo app of streamlit.

# How to launch the app without Docker
Verify you have Python and streamlit installed.
Run  ```streamlit run uber_app.py ``` in the repo's directory to launch the demo app.
The app will by default be available on your localhost:8501.

# How to launch the app with Docker
To lauch the app with Docker create the docker image:
 ```docker build -t streamlit . ```
You can then run the app with the following command:
 ```docker run -p 8501:8501 streamlit ```
The app will by default be available on your localhost:8501.

