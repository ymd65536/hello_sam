# SAM TEST

## Setup

```bash
pip install aws-sam-cli
```

## Run

```bash
DOCKER_HOST=unix://$HOME/.rd/docker.sock sam local invoke
```

## HelloWorldFunction

```bash
DOCKER_HOST=unix://$HOME/.rd/docker.sock sam local invoke "HelloWorldFunction"
```

## Troubleshooting

> Error: Running AWS SAM projects locally requires Docker. Have you got it installed and running?

```bash
export DOCKER_HOST="unix://$HOME/.rd/docker.sock"
```

## Switch To Context

```bash
docker context use rancher-desktop
```
