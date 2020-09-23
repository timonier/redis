# README

Redis is an open source key-value store that functions as a data structure server

⚠️ This project is no longer maintained. ⚠️

## Installation

```sh
# Define installation folder

export INSTALL_DIRECTORY=/usr/bin

# Use local installation

sudo bin/installer install

# Use remote installation

curl --location "https://gitlab.com/timonier/redis/raw/master/bin/installer" | sudo sh -s -- install
```

__Note 1__: If you do not define `INSTALL_DIRECTORY`, `installer` will use in `/usr/local/bin`.

__Note 2__: `docker-for-mac` users have to configure [native NFS server](https://medium.com/@sean.handley/how-to-set-up-docker-for-mac-with-native-nfs-145151458adc).

## Usage

Run the command `redis-cli`:

```sh
# See all redis-cli options

redis-cli --help

# Run redis-cli

redis-cli -h redis-morgan.docker
```

## Links

* [image "timonier/redis"](https://hub.docker.com/r/timonier/redis/)
* [redis](https://redis.io/)
* [set up docker for mac with native nfs](https://medium.com/@sean.handley/how-to-set-up-docker-for-mac-with-native-nfs-145151458adc)
