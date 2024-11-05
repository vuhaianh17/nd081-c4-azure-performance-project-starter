# Pull the base image
FROM tiangolo/uwsgi-nginx-flask:python3.7
# Install depndencies 
RUN pip install redis
RUN pip install opencensus
RUN pip install opencensus-ext-azure
RUN pip install opencensus-ext-flask
RUN pip install opencensus-ext-logging
RUN pip install jinja2==3.0.3
RUN pip install itsdangerous==2.0.1
RUN pip install werkzeug==2.0.3
RUN pip install flask==1.1.2

# Copy the content of the current directory to the /app of the container
ADD . /app
