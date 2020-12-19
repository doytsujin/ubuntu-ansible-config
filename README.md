# ubuntu-ansible-config

My ansible configuration files for Ubuntu systems.

It basically installs some packages I always want ready to go, and sets a more complete dark mode.

## Usage

Make sure the host_user is set to your username. Cutting and pasting the following commands into a terminal will do just that.

    sudo apt update
    sudo apt install git ansible
    sudo ansible-pull -U https://github.com/lab1702/ubuntu-ansible-config.git --extra-vars "host_user=$USER"
