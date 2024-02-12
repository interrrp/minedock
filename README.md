# Pave

An easy-to-use Minecraft server template with Docker, complete with a proxy configuration.

## Running the server

To run the server, you will need:

- [Git](https://git-scm.com)
- [Docker](https://www.docker.com) 24.0 or later
- [Docker Compose](https://docs.docker.com/compose) 3

After ensuring that you have all the prerequisites, run the following commands:

```sh
git clone https://github.com/interrrp/pave
cd pave
docker compose up -d
```

Your server is now up at port 25565. Good job! 😀👍

### Additional commands

```sh
# Check the logs of the server
docker compose logs pave

# Check the logs of the server (follow)
docker compose logs pave -f

# Check the logs of a specific server (lobby in this example)
docker compose logs pave lobby
```
