Edit the docker compose file and replace in labels "NAME" with an alias and "youraccessdomain" with the domain that accesses the lamp.

To balance between two Apaches, once the lamp has been raised, we will execute the command "docker compose up -d --scale apache1=2" and automatically Traefik balances between the two Apaches showing its internal IP.
Hola ha sido modificado por Raul
