# Nginx Proxy Manager

This repository contains the configuration and setup for running Nginx Proxy Manager using Docker.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

1. Clone the repository:
    ```sh
    git clone https://github.com/onovaes/nginx-proxy-manager.git
    cd nginx-proxy-manager
    ```

2. Create and start the Docker containers:
    ```sh
    docker-compose up -d
    ```

3. Access the Nginx Proxy Manager web interface:
    - Open your browser and navigate to `http://localhost:81`
    - Default login credentials:
        - **Email:** `admin@example.com`
        - **Password:** `changeme`

## Configuration

Edit the `docker-compose.yml` file to customize the setup according to your needs.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## Acknowledgements

- [Nginx Proxy Manager](https://nginxproxymanager.com/)
