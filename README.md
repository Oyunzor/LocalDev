# LocalDev Testing Environment
This repository aims to provide a local testing environment for Oyunzor plugins.

# Prequisites
You need a docker installation in your system to use this environment. Docker Desktop is recommended.

Also it is recommended to change the `OP_PLAYER_USERNAME` setting in `.env` file to your in game nickname.

# How to Start
Just start the compose project by executing below command in the project's root directory:

    docker compose up -d

# Usage
## Plugins
Just put the plugins in the corresponding folder. For example:

Velocity Plugins -> velocity/plugins/

Lobby Plugins -> lobby/plugins/

Channel Plugins -> channel/plugins/

Note: The old jar files will be automatically deleted and replaced by the ones in the plugins directories during every server start.
