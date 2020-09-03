
## Prerequisites:

- 💻 **Installed**: **docker** and **docker-compose**
- ☁ If using a cloud provider:
    - You need to allow ingress to port `51820`

To get started all you need to do is clone the repository and spin up the containers.

```bash
git clone https://github.com/IAmStoxe/wirehole.git
cd wirehole
docker-compose up
```

Within the output of the terminal will be QR codes you can (if you choose) to setup it WireGuard on your phone.

```bash
wireguard    | **** Internal subnet is set to 10.6.0.0 ****
wireguard    | **** Peer DNS servers will be set to 10.1.0.100 ****
wireguard    | **** No found wg0.conf found (maybe an initial install), generating 1 server and 1 peer/client confs ****
wireguard    | PEER 1 QR code:
wireguard    | █████████████████████████████████████████████████████████████████
wireguard    | █████████████████████████████████████████████████████████████████
wireguard    | ████ ▄▄▄▄▄ █▀▀▀▄ ▀▀▀▀▄█ ██   ▄▀ ██ ██▄▀█    █▄▄█▀ ▄ ██ ▄▄▄▄▄ ████
wireguard    | ████ █   █ █▀▄█▀█▄█▄██▀▄   ▀▀██▀▄█ ▀▄█  ▀ █▀▄█▄ ▄▄▄ ██ █   █ ████
wireguard    | ████ █▄▄▄█ █▀█   ▀▀▄                               ▄██ █▄▄▄█ ████
wireguard    | ████▄▄▄▄▄▄▄█   ▀ ▀   █                         █▄█▄▀ █▄▄▄▄▄▄▄████
wireguard    | ████ ▄▄  █▄▄▄  ▄▀█▀▀▄    ▀█ ▀█  ▄  █▀▀▄▄██▄▄▀▀█▄ ██▀▀ █ █▄█ ▀████
wireguard    | █████  ▄█ ▄  ▀▀█▄▄  █▀ ▀ ▀ ▄  ▄ ▀▄▀▀█ ██ ▀██▀   ▀ ▀▀   ▀  ▀▄ ████
wireguard    | ████▀▀██  ▄▄▄ ██▀▄▄██▀ ██▀▄  ▀▀ █▄█   ▄ ▄█▄██   ▀▄▄█  █▀▀█ ▄▀████
wireguard    | ████ ▄█▀█▀▄▄   ▄███ ▄█ ▀▀▀▀█ ▄█ ▀▀▀▀▀▄ █   █ ███▄ █ ▄▄▄▄▀▀▀ █████
wireguard    | ████▀▄ ▀▀ ▄▄ ▄▄  █▀██    ▀▀▀▀▀  ▄  █▀▀██  ██▀   ▀█▄█▄█  ▄▄▀ ▀████
wireguard    | ████   ▀█ ▄▄                                          █  ▀▀██████
wireguard    | ███████  ▄▄█ █                                        ▄█▀█▀▀▄████
wireguard    | ████ ▄  █▄▄▀  ▄   ▀▄ █ ▄██▀▀█▀   █▄▄█▀▄█▀█▄ █ ▀▄█ ▄█ ▀   █  █████
wireguard    | ████▄██▀█▄▄ ▀ ▄▀                       ▀▄  ▄█ ▀▄  █▀ ▀██▀▄███████
wireguard    | ████ ▀█  ▄▄▄ ██▀███▄█▄█ █▄█▀ ▀ ▄▄▄ ▀▀  ▀▄ ▀▀█   █ █  ▄▄▄   ▄▀████
wireguard    | ████▄██  █▄█  █                                          ▀▀ ▀████
wireguard    | █████▀█▄▄▄▄▄ █▄ ▀▄ ██  ██▀ ▄ █▄ ▄▄▄▀ ▀▄▀█  █▀ █▄ ▄ ▄▄▄  ▄ ▀▄█████
wireguard    | █████▀▄▀  ▄▄█▄▀ ██▄▄▄    █▀  ██    ██ █▄   ██▄ ▄▀█▄██▀▄█   █▀████
wireguard    | ████▄   ▀ ▄ ▀ ▀▀▀▀▀▀█▀██▀ █  █▀█▀███ ▀▄█  █▄ █     ▀▀█▀██▀ ▄█████
wireguard    | ████ ▀ ▄   ██▄ ▀▀▀▄▀█  ▀▀▄ ▄ ▄  █▀▀▄█ ▄█▄▀█▄█▀ ▄▀█▄▀ ▀▀▀ ▀▀ ▀████
wireguard    | ███████ ▄█▄  ▀█▄▄  ▀█ █▀ █▀▄ ▄ ▀▄█▄▄█▀▄█▄▄▄▄█▀ ▀█ █▀  ▄ ██▀▄█████
wireguard    | ████▀█ █▀ ▄                                             █ ▄▀█████
wireguard    | ████▀▄ ▄▄█▄▄  ▄ ▄██▄ ▀ █ ▀ ▄▄█▀▀ ▄ ▀▀▄█▀▄██▀▀ ▄   ▄▄▄▄▀▀▄▀▀▀ ████
wireguard    | ████ ▀▄▄▀▀▄▀▀▀▄ ▄ █▄▄▀ ██▀▄▀ █▄██▀▀▄█▄▄█ ████▄ ▀█▄█▀▄▀ ▀▄ ▀ █████
wireguard    | ████ ▀ ▀▀▄▄ ▄ █▄ ▄ ██ ▄▀█▄▄  ▄ ▄ █▄▀ ▄▄▀██▄▀▀██▀▀▄▄ ▄   ██ ▄▀████
wireguard    | ██████████▄█▀▀█ ▄█ █▄▄ ▀▄▀█▀▀  ▄▄▄ ▀█▀█ ▄▀█▀█▀▀ ██▄▀ ▄▄▄ ▄██▄████
wireguard    | ████ ▄▄▄▄▄ █▄▄▄█▀▄█▀██ ▄ ▀█ ▀  █▄█ ▀▀█▄ ██▄█ ▀▄ ▀█▄▄ █▄█    █████
wireguard    | ████ █   █ █  ▄▄ ▄█   ▄▄█ █▀   ▄ ▄  █ ▄█▄▄█ █▀ ▄████ ▄▄  ▀▀▄▄████
wireguard    | ████ █▄▄▄█ █ ▀ ▄▄█ ▄ ▀▀▄██▄▀█▀█ █▀█▀▀▀▄   ▄ █▀▀▄▀ ▄▀███▀██▀██████
wireguard    | ████▄▄▄▄▄▄▄█▄██▄▄█▄▄▄▄▄██▄█▄▄▄█▄█▄█▄▄▄▄█▄▄▄█████▄▄█▄█▄▄████▄█████
wireguard    | █████████████████████████████████████████████████████████████████
wireguard    | █████████████████████████████████████████████████████████████████
wireguard    | [cont-init.d] 30-config: exited 0.
wireguard    | [cont-init.d] 99-custom-scripts: executing...
wireguard    | [custom-init] no custom files found exiting...
wireguard    | [cont-init.d] 99-custom-scripts: exited 0.
wireguard    | [cont-init.d] done.
wireguard    | [services.d] starting services
```

## Recommended configuration / Split tunnel:

Modify your wireguard client `AllowedIps` to `10.1.0.0/24` to only tunnel the web panel and DNS traffic.

## Access PiHole

While connected to WireGuard, navigate to http://10.1.0.100/admin

*The password (unless you set it in `docker-compose.yml`) is blank.*

![](https://i.imgur.com/hlHL6VA.png)