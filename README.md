# momento-proxy-demo
Quickstart dev demo for momento proxy

_Warning: This repo has binary's for OSx only currently. Will add docker support soon for better cross-platform experience soon._ 

### Quickstart

Create cache with momento-cli
```console
momento cache create --name test
```

Start Momento Proxy:
```console
MOMENTO_AUTHENTICATION=*** ./bin/momento_proxy configs/momento-proxy-config.toml&
```

Start RPC Perf:
```console
bin/rpc-perf configs/rpc-perf-config.toml
```
