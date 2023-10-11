FROM ghcr.io/hoglandets-it/awx-ee-extended:latest

ADD ./executor_files /tmp/install_exec
RUN cd /tmp/install_exec \
    && ansible-playbook -i /executor_filesinventory-yml install_receptor.yml

