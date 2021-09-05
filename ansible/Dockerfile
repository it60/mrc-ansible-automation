FROM rundeck/rundeck:3.4.2
RUN sudo apt update && \
        sudo apt install -y vim && \
	sudo apt -y install software-properties-common && \
	sudo add-apt-repository --yes --update ppa:ansible/ansible && \
	sudo apt -y install ansible
