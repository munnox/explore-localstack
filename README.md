# Exploring the localstack system

https://docs.localstack.cloud/getting-started/quickstart/

using sample and main code as submodules to version commits


Notes on Sample:

* Need to set DNS for `localhost.localstack.cloud` for `127.0.0.1`.

Looking at Debugging

```bash
LAMBDA_DOCKER_FLAGS='-p 19891:19891' localstack start
```

