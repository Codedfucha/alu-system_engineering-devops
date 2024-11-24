# Web Stack Debugging - 0

This project is part of the web stack debugging series. The objective of this task is to configure Apache to run in a Docker container and serve a simple HTML page containing the text "Hello Holberton".

## Task Overview

The task requires the following:
1. Running an Apache web server inside a Docker container.
2. Creating a simple webpage that displays "Hello Holberton".
3. Exposing the web page on port 80 inside the container and port 8080 on the host machine.

## Files

- **0-give_me_a_page**: A Bash script that installs Apache, sets up the HTML page, and starts the Apache web server to serve the page.

## Steps to Complete

1. **Build and Run Docker Container**:
   - Pull the required Docker image and run the container.
   - Make sure Apache is installed and running within the container.

2. **Script Execution**:
   - The script installs Apache, creates a simple HTML page with the text "Hello Holberton", and ensures Apache is running in the foreground to keep the container alive.

3. **Verify Apache Service**:
   - After running the container, the web page should be accessible on port 8080 of the host machine, which maps to port 80 inside the container.


