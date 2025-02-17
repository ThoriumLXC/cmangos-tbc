# cMaNGOS Classic

cMaNGOS Classic is an [open-source project, known as Continued MaNGOS](https://github.com/cmangos/mangos-classic), with variants named Classic, TBC and WOTLK. This repository contains configurations with Docker Compose that bring up emulator servers for the classic variant of cMaNGOS.

These Docker Compose configurations **require** a named volume containing client data to exist. Follow the ThoriumLXC documentation to setup such a named volume.

## Running the configurations

You can run the configurations within this repository using `docker compose`. This is done by running:

```bash
docker compose up -d
```

Within the directory/folder that contains these configurations.
