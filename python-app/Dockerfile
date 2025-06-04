From python:38
WORKDIR /app
COPY requirements.txt .
RUN pip install -r requirements.txt

#copy the application code into the container
COPY . .

#expose the port the flask application will be listening on
EXPOSE 5000

#set env variables if necessary
#ENV MY_ENV_VAR = value

CMD ["python", "app.py"]
