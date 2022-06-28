FROM python:3.8-alpine

# Create app directory
WORKDIR /app
COPY . /app

# Install app dependencies
RUN pip install -r requirements.txt

# Bundle app source
CMD [ "python","-u", "app.py" ]