# Nginx Proxy Manager Setup

To connect docker containers to the Nginx Proxy Manager network, use the following command:

```bash
docker network connect <container_name> nginx-proxy-manager_default

# or,

make connect-network container=<container_name>

```
