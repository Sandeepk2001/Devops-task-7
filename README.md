# Devops-task-7
# Task 7: Monitor System Resources Using Netdata

## Objective
To install Netdata and visualize system and application performance metrics using Docker.

 Steps Taken
1. Docker Setup: Verified Docker Desktop was installed and running.
2. Deployment: Ran the Netdata container using the official image:
   ```bash
   docker run -d --name netdata -p 19999:19999 netdata/netdata
