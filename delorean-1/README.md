# delorean-1 Testnet

## Binary

Ensure the `ethosd` binary is version v0.2.2. The binary included in this repository is 
built against `linux-amd64`. You can verify this via:

```shell
$ ethosd version
0.2.2
```

## Genesis

Ensure you have the correct `genesis.json` file by comparing the SHA256 hash of
the file with the following:

```shell
$ jq -S -c -M '' genesis.json | shasum -a 256
26349e0b16071d15fb0de8021121bbf88293cca182e0ba87ff3626a574033cf2  -
```

## Persistent Peers

The following nodes can be set as `persistent_peers` in the `config.toml` file:

* `11b2b636246e9ef05fac81ff3d084ed2839996ba@34.28.105.161:26656`
* `1ada2153b1948032d0de14fbbe7653e026fd4569@34.28.105.161:26666`
* `f49d25edac6d494498fd198f0f7f46455892565b@34.28.105.161:26667`

## Seeds
