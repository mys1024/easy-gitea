# docker-gitea

Provide `docker-compose.yaml` based on [Installation with Docker - Gitea Document](https://docs.gitea.io/en-us/install-with-docker/).

## Usage

1. Install docker and docker-compose (or podman and podman-compose)

2. Change to a proper directory (such as '/gitea')

   ```bash
   cd /path/to/proper/directory
   ```

3. Run

    ```bash
    git clone https://github.com/mys1024/docker-gitea.git \
    && cd docker-gitea \
    && docker-compose up  # or "podman-compose up"
    ```
