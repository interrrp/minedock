# Minedock

An easy-to-use Minecraft server template with Docker, complete with a proxy configuration.

## Running the server

To run the server, you will need:

- [Git](https://git-scm.com)
- [Docker](https://www.docker.com) 24.0 or later
- [Docker Compose](https://docs.docker.com/compose) 3

After ensuring that you have all the prerequisites, run the following commands to clone the repository:

```sh
git clone https://github.com/interrrp/minedock
cd minedock
```

You will need to create a `forwarding.secret` file in the `proxy` directory. The contents have to be something secure.

After doing that, run the server:

```sh
docker compose up -d
```

Your server is now up at port 25565. Good job! 😀👍

### Additional commands

```sh
# Check the logs of the server
docker compose logs minedock

# Check the logs of the server (follow)
docker compose logs minedock -f

# Check the logs of a specific server (lobby in this example)
docker compose logs minedock lobby
```

## License

This project is licensed under the [MIT license](./LICENSE).
