# fedora-ansible-configuration
This ansible playbook installs and configures a number of various services, applications, and other tools I like having for an out-of-the-box ansible deployment

Feel free to customize this to your liking.
# Usage
This is designed for use on a brand new installation of Fedora Workstation with Gnome as the preferred GUI. It can be either physical or virtual.  Networking must be up enough to get to both the fedora package repositories and to GitHub to download the role.

To run, download kickoff.sh, edit any necessary variables in the top (TODO: add details), make the script executable, and run the bash script.  This script will download ansible first, download the repo from github (be sure to change the default from this repo to your own copy if you change things) and then run the ansible playbook
