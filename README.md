# redis-docker-dev-boilerplate
REDIS For Local Dev.
## Direnv
Use direnv to export environment variables for docker redis.

- example
```.envrc
export REDIS_PORT=6379
```


## Connect
### Fron Container
```
% docker-compose exec redis bash

% redis-cli

127.0.0.1:6379> keys *
```

### Host Machine
```sh
# Install Only Cli
% yarn global add redis-cli

% rdcli
> keys *
```
