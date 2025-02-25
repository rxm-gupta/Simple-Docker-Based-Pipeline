# Simple-Docker-Based-Pipeline

This pipeline configures a simple build process that:

Uses a Docker container with the node:20-alpine image as the execution environment

Contains a single stage called "Test"

In the Test stage, it executes one step that runs the shell command node -v, which displays the version of Node.js installed in the container
