# change_pheus_v1

for nginx deployement, put your server IP in
[line:49] with port which serves the application.

edit hosts to put your server IP.
then run, 

$ ansible-playbook auto_node_deployement.yml

# for best practice make an initial script that configures
# nginx-IP, node-IP, hosts-data,
# git-URL e.t.c.