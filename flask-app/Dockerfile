#base image with python
FROM python:3.9

#working directory from the app
WORKDIR app/

#copy the code from system
COPY app.py .

#instal the required directories
RUN pip install Flask

#run the application
CMD ["python","app.py"]

