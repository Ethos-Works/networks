# delorean-1 Testnet

## Genesis

Ensure you have the correct `genesis.json` file by comparing the SHA256 hash of
the file with the following:

```shell
$ jq -S -c -M '' genesis.json | shasum -a 256
26349e0b16071d15fb0de8021121bbf88293cca182e0ba87ff3626a574033cf2  -
```

## Persistent Peers

The following nodes can be set as `persistent_peers` in the `config.toml` file:

* `1ada2153b1948032d0de14fbbe7653e026fd4569@172.25.0.3:26656`
* `11b2b636246e9ef05fac81ff3d084ed2839996ba@172.25.0.2:26656`
* `f49d25edac6d494498fd198f0f7f46455892565b@172.25.0.4:26656`

## Seeds
