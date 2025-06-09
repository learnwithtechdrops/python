#FROM python:3.11-alpine
FROM python:3.9.23-slim-bookworm

WORKDIR /app

# Copy the local code to the container
COPY . /app

# Install Flask
RUN pip install --no-cache-dir -r requirements.txt

# Expose port 5000 for Flask
EXPOSE 5000

# Set the command to run the app
CMD ["python", "helloworld.py"]