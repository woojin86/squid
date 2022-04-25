# squid
ready squid srv (based on sameersbn/squid:3.5.27-2)

install docker-compose by commands: 

curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
&&
chmod +x /usr/local/bin/docker-compose

and run the squid server:

docker-compose up -d
