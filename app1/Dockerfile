# Use official Python image
FROM python:3.9-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the app code to the container
COPY app1.py .

# Install Flask
RUN pip install Flask

# Expose the port on which the app will run
EXPOSE 5000

# Run the Flask app
CMD ["python", "app1.py"]

