FROM python:3-alpine

# Set the working directory
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install Flask
RUN pip install flask

# Expose port 81
EXPOSE 81

# Command to run the application
CMD ["python", "app.py"]
