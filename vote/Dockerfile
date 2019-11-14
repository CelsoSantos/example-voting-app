# Using official python runtime base image
FROM python:2.7-alpine

# Set the application directory


# Install our requirements.txt


# Copy our code from the current folder to /app inside the container


# Make port 80 available for links and/or publish


# Define our command to be run when launching the container
CMD ["gunicorn", "app:app", "-b", "0.0.0.0:80", "--log-file", "-", "--access-logfile", "-", "--workers", "4", "--keep-alive", "0"]
