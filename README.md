# Zabbix Proxy Compose

> [Info]
> fork of [nnnc-org/zabbix-proxy](https://github.com/nnnc-org/zabbix-proxy) without *wireguard*. ([License](./LICENSE))
>
> if you need *wireguard*, check out above repo.

This is a docker-compose file to run a Zabbix Proxy with a sqlite3 database.

## Configuration

Configuration is very easy.

1. clone the repo:

    ```sh
    git clone https://github.com/ymargreth/zabbix-proxy.git
    ```

2. copy the `.env.example` file to `.env` and change the values to your needs.

3. start the container:

    ```sh
    docker-compose up -d
    ```
