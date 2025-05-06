# Use an appropriate base image
FROM python:3.10

# Set the working directory
WORKDIR /app

# Copy all files into the container
COPY . /app

# Create the missing directory
RUN mkdir -p /app/data

# Install Python dependencies
RUN pip install -r requirements.txt

# Set Streamlit as the default command (or change if needed)
CMD ["streamlit", "run", "streamlit_app.py"]