# How to Install Grafana on Ubuntu 22.04 or 20.04 LTS Linux
Step 1: Start with Ubuntu System Update
We need to run the system update command on the  Linux system from time to time, especially before  installing some software package. It is because it not only installs the latest updates available for the  installed applications but even refreshes the package index cache of APT. So, open your  Ubuntu command terminal and run:

sudo apt update && sudo apt upgrade
Step 2: Install the required extra packages
There are a few packages that we will require to perform the commands given in this tutorial, so install them using the given syntax.

sudo apt install -y apt-transport-https software-properties-common wget
