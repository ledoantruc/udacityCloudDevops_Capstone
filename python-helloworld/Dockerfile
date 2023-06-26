FROM python:3.10
LABEL maintainer="Udacity"

COPY . /app
WORKDIR /app

# hadolint ignore=DL3013
RUN pip install --no-cache-dir --upgrade pip && pip install --no-cache-dir -r requirements.txt

# Expose port 80
EXPOSE 80

# Run app.py at container launch
CMD [ "python", "app.py" ]