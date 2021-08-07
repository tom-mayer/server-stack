# server-stack

This is a docker-compose stack running wordpress and using traffic to handle routing if you have multiple applications on the server as 
well as getting certs from letsencrypt. Portainer is there to monitor / restart / manage things. If you add services I would suggest forking
and adding new compose files. Stacks can be managed through portainer. 

#Startup

- Run `setup.sh` then fill in the variables in the generated `.env` file. 
- Use portainer or docker-compose up to run the stacks
