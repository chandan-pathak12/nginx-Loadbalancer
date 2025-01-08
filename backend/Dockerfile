# Use the official Python image as the base
FROM python:3.9-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the application files into the container
COPY . /app

# Install Flask and any dependencies
RUN pip install flask

# Expose the port the app runs on
EXPOSE 5000

# Default command to run the application (can be overridden)
CMD ["python", "app.py"]
