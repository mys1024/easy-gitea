# easy-gitea

Easily startup a [**Gitea**](https://about.gitea.com/) container with [**Docker Compose**](https://docs.docker.com/compose/).

## Usage

1. **(Optional)** Create a `.env` file with your custom configurations:

    ```sh
    GITEA_PORT_SSH=22
    GITEA_PORT_HTTP=3000
    ```

2. Startup:

    ```sh
    docker-compose up -d
    ```

## License

[MIT](./LICENSE) License &copy; 2024-PRESENT [mys1024](https://github.com/mys1024)
