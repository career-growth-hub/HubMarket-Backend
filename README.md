# HubMarket-Backend

## Prerequisites
- Docker
- Kubernetes
- Maven
- Jenkins

## Setup Instructions


1. Click the fork button to fork the HubMarket-Backend repository on GitHub.

2. On the create new fork page, check the details and click the Create fork button.

3. You should automatically be redirected to your fork, the URL should be something like https://github.com/YOUR_USER_NAME/HubMarket-Backend

That’s it! You have successfully forked the freeCodeCamp repository. You can always delete your fork if you want to start fresh.

How to prepare your local machine

## System Requirements - 
Here is a minimum system requirement for running HubMarket-Backend locally:

1. A fast CPU (4+ cores)
2. At least 8 GB RAM
3. macOS, Linux or Windows 10 or 11 (with WSL)
4. 7-8 GB of free disk space
(Optional) 30-50 Mbps internet connection

## Clone your Fork from GitHub

1. Open a terminal in your projects directory, for example:
	/home/username/projects/
2. Clone your fork of freeCodeCamp, replacing YOUR_USER_NAME with your GitHub Username
	git clone https://github.com/username/HubMarket-Backend.git
This will download the entire HubMarket-Backend repository to your projects directory.

## Set up Syncing from Parent

1. Change the directory to the new freeCodeCamp directory if you aren’t already there:
	cd HubMarket-Backend
2. Add a remote reference to the main freeCodeCamp repository:
	git remote add upstream https://github.com/career-growth-hub/HubMarket-Backend.git
3. Ensure the configuration looks correct:
	git remote -v
