FROM python:3.10-slim-buster

# inside container
# make a new folder inside container
WORKDIR /backend-flask

# outside container -> inside container
# contains the libraries installed to run the app
COPY requirements.txt requirements.txt

# inside container
# install the python libraries used for the app
RUN pip3 install -r requirements.txt

# outside container -> inside container
COPY . .

# set enviroment variables
ENV FLASK_ENV=development

EXPOSE ${PORT}
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]