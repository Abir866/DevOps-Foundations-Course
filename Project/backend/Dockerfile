# TODO-STEP 1: Choose a base image
FROM python:3.9-slim

# TODO-STEP 2: Set the working directory
WORKDIR /app

# TODO-STEP 3: Copy the requirements file
COPY requirements.txt .

# TODO-STEP 4: Install the Python dependencies
RUN pip install -r requirements.txt

# TODO-STEP 5: Copy the application code
COPY app.py .

# TODO-STEP 6: Specify the command to run the application


# Use an official Python runtime as a parent image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY requirements.txt app.py ./

# Install any needed packages specified in requirements.txt
RUN pip install -r requirements.txt

# Make port 5000 available to the world outside this container
EXPOSE 5000


# Run app.py when the container launches
CMD ["python", "app.py"]