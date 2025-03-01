# CMaNGOS TBC

CMaNGOS TBC is an [open-source project, known as Continued MaNGOS](https://github.com/cmangos/mangos-tbc), with variants named Classic, TBC and WOTLK. This repository contains configurations with Docker Compose that bring up emulator servers for the TBC variant of CMaNGOS.

These Docker Compose configurations **require** a named volume containing client data to exist. Follow the [ThoriumLXC documentation](thoriumlxc.github.io) to setup such a named volume.

## Configurations

Within this repository, you'll find multiple directories offering preset configuration samples to help you get started quickly. Each directory represents a distinct experience you can set up, guiding you to the appropriate configuration for your needs.

- [Default Experience](./default) - The default environment, designed to get you up and running in minutes.
- [Bot Experience](./bots/) - Focuses on gameplay enhanced by bot activity.

## Running the configurations

You can run the configurations within this repository using `docker compose`. This is done by running:

```bash
docker compose up -d
```

Within the directory/folder that contains these configurations.
