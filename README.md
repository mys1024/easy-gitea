# easy-postgresql

Easily startup a [**Gitea**](https://about.gitea.com/) container with [**Docker Compose**](https://docs.docker.com/compose/).

## Usage

1. Create a `.env` file in the root of the project with the following configurations:

    ```sh
    # Gitea
    GITEA_IMAGE=docker.io/gitea/gitea:1.22
    GITEA_PORT_SSH=22
    GITEA_PORT_HTTP=3000

    # DB
    POSTGRES_IMAGE=docker.io/library/postgres:17
    ```

2. Startup:

    ```sh
    docker-compose up -d
    ```

## License

[MIT](./LICENSE) License &copy; 2024-PRESENT [mys1024](https://github.com/mys1024)
