# delorean-3 Testnet

## Binary

Ensure the `ethosd` binary is version v0.4.0. The binary included in this repository is 
built against `linux-amd64`. You can verify this via:

```shell
$ ethosd version
0.4.0
```

## Genesis

Ensure you have the correct `genesis.json` file by comparing the SHA256 hash of
the file with the following:

```shell
$ jq -S -c -M . genesis.json | shasum -a 256
37b48fbbd616d3cca1b5da9f1c516f506b8aaef4ed2690762a09aca9a82ff065  -
```

## Persistent Peers

The following nodes can be set as `persistent_peers` in the `config.toml` file:
