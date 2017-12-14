# README

Redis is an open source key-value store that functions as a data structure server

## Installation

Linux users can use the [installer](https://github.com/timonier/redis/blob/master/bin/installer):

```sh
curl --location "https://github.com/timonier/redis/raw/master/bin/installer" | sudo sh -s -- install
```

## Usage

Run the command `redis-cli`:

```sh
# See all redis-cli options

redis-cli --help

# Run redis-cli

redis-cli -h redis-morgan.docker
```

## Contributing

1. Fork it.
2. Create your branch: `git checkout -b my-new-feature`.
3. Commit your changes: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin my-new-feature`.
5. Submit a pull request.

__Note__: Use the script `bin/build` to test your modifications locally.

## Links

* [image "timonier/redis"](https://hub.docker.com/r/timonier/redis/)
* [redis](https://redis.io/)
* [timonier/dumb-entrypoint](https://github.com/timonier/dumb-entrypoint)
* [timonier/version-lister](https://github.com/timonier/version-lister)
