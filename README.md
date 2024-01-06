# Dockerized Paper server

This is a dockerized Paper server. On start up, the current Paper version is downloaded. If the server crashes, it will get restarted by Docker automatically.

Exposed ports:

- `25565` for Minecraft
- `8123` for [Dynmap](https://www.spigotmc.org/resources/dynmap%C2%AE.274/)

## Usage

```sh
# Start server
docker compose up -d

# Stop server
docker compose down

# Attach to server console (detach with ^P^Q)
docker attach paper
```
