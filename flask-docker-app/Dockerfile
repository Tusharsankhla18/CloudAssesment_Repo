# Use the official Python 3.8 image as base
FROM python:3.8

# Set the working directory in the container to /app
WORKDIR /app

# Copy the contents of the current directory to /app
COPY . /app

# Install dependencies from requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Expose the default Flask port
EXPOSE 5000

# Command to run the application
CMD ["python", "app.py"]
