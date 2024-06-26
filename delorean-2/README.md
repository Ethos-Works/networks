# delorean-2 Testnet

## Binary

Ensure the `ethosd` binary is version v0.3.0. The binary included in this repository is 
built against `linux-amd64`. You can verify this via:

```shell
$ ethosd version
0.3.0
```

## Genesis

Ensure you have the correct `genesis.json` file by comparing the SHA256 hash of
the file with the following:

```shell
$ jq -S -c -M . genesis.json | shasum -a 256
7490e6a5b67c3a101d3fb3bd3934404ab1439696653f66c84e709408ec8b7fba  genesis.json  -
```

## Persistent Peers

The following nodes can be set as `persistent_peers` in the `config.toml` file:

* `11b2b636246e9ef05fac81ff3d084ed2839996ba@34.28.105.161:26656`
* `1ada2153b1948032d0de14fbbe7653e026fd4569@34.28.105.161:26666`
* `f49d25edac6d494498fd198f0f7f46455892565b@34.28.105.161:26667`

## Seeds
