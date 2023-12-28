# Chat API

Container for chatting peer-to-peer with any registered users

## Setup

On `/etc/hosts` or `C:\Windows\System32\drivers\etc\hosts` file register local domains alias mapped to the localhost IP address

```
127.0.0.1   chat.test
127.0.0.1   api.chat.test
```

## Commands

- Start container

```shell
make start
```

- Stop container

```shell
make stop
```

- Restart container

```shell
make stop start
```

- Rebuild container

```shell
make rebuild
```
