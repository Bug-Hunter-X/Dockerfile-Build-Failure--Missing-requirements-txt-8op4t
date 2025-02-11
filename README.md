# Dockerfile Bug: Missing requirements.txt

This repository demonstrates a common error in Dockerfiles:  forgetting to include or correctly referencing a `requirements.txt` file when installing Python dependencies. The original `Dockerfile` attempts to install dependencies using `pip3 install -r requirements.txt`, but the `requirements.txt` file is missing, leading to a build failure.

The solution demonstrates the correct way to include the `requirements.txt` file and ensure the Dockerfile builds successfully.