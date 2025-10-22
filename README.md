# HNG13 Stage 1 Task

This repository contains a production-grade Bash script (`deploy.sh`) developed for the HNG13 Devops Stage 1 task. The script automates the deployment of a Dockerized application to a remote Linux server, including environment setup, Docker/Nginx configuration, and reverse proxy setup.


##  Usage Instructions

### 1. Make the script executable
```bash
chmod +x deploy.sh
```

### 2. Run the script
```bash
./deploy.sh
```

### 3. Provide the following when prompted:
* GitHub repository URL

* GitHub Personal Access Token (PAT)

* Branch name (optional; defaults to main)

* Remote server SSH username

* Server IP address

* SSH key path

* Internal application port (e.g., 80)
