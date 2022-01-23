# docker-gitea

Provide `docker-compose.yaml` based on [Installation with Docker - Gitea Document](https://docs.gitea.io/en-us/install-with-docker/), to run a **Gitea** server quickly.

## Usage

1. Install docker and docker-compose (or podman and podman-compose).

2. Change to a proper directory.

   ```bash
   cd /path/to/proper/directory
   ```

3. Clone and change directory to this repository.

    ```bash
    git clone https://github.com/mys1024/docker-gitea.git && \
    cd docker-gitea
    ```

4. Edit `.env` file to configure environment variables.

    ```bash
    vim .env
    ```

4. Run Gitea server.

    ```bash
    docker-compose up -d
    # or
    podman-compose up -d
    ```

6. Access your Gitea via browser.
