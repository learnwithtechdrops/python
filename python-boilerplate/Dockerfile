FROM python:3.14-rc-alpine3.22

WORKDIR /app

# Copy the local code to the container
COPY . /app

# Install Flask
RUN pip install --no-cache-dir -r requirements.txt

# Expose port 5000 for Flask
EXPOSE 5000

# Set the command to run the app
CMD ["python", "helloworld.py"]