# Automation: Docker Compose

This Bash script may be executed on a terminal or by a task scheduler such as [cron](https://linux.die.net/man/8/cron) and it does the following:

1. Install [Docker](https://docs.docker.com/engine/install/);
2. Install [Docker Compose](https://docs.docker.com/compose/install/); and
3. Provide Docker Compose with execute permission.

A detailed walk-through is available [here](https://kurtcms.org/automation-docker-compose/).

## Table of Content

- [Getting Started](#getting-started)
  - [Git Clone](#git-clone)
  - [Permission](#permission)
  - [Run](#run)

## Getting Started

Get started in three simple steps:

1. [Download](#git-clone) a copy of the script;
2. Provide the script with execute [permission](#permission); and
3. [Run](#run) the script manually.

### Git Clone

Download a copy of the script with `git clone`.

```shell
$ git clone https://github.com/kurtcms/docker-compose /app/docker-compose/
```

### Permission

Provide the script with execute permission.

```shell
$ chmod +x /app/docker-compose/docker-compose.sh
```

### Run

Run the script.

```shell
$ /app/docker-compose/docker-compose.sh
```

And have Docker Compose installed.