## Odoo Installation in production (Behind Nginx Reverse Proxy)

$ git clone https://github.com/QaidjoharBarbhaya/odoo-deployment.git

$ cd odoo-deployment

$ mkdir extra-addons

$ docker swarm init

$ docker stack deploy -c deploy-stack-compose.yml odoo
