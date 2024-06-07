Instructions to Run the Script
Save the above script to a file named install_docker.sh.
Make the script executable by running:
bash
Copy code
chmod +x install_docker.sh
Run the script with root privileges:
bash
Copy code
sudo ./install_docker.sh
This script updates the system, adds Docker’s official GPG key and repository, installs Docker and Docker Compose, and verifies their installations. Make sure you have an internet connection during this process as it requires downloading packages.
