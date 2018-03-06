## Nginx Proxy

Getting started:

Launch the container with docker compose:    
`docker-compose up -d`

Then you need to specify a VIRTUAL_HOST environment variable either in your docker-compose file or docker run command.    
`VIRTUAL_HOST=subdomain.youdomain.com`

See https://github.com/jwilder/nginx-proxy for more details.

You will probably also want to setup a dns server and resolver for local development:    
https://blog.thesparktree.com/local-development-with-wildcard-dns
