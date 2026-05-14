# HiClaw-Framework

Custom util functions and setup scripts for my personal HiClaw Agent Framework.

## Docker Tools

Use these commands to stop currently running `hiclaw-` containers and then start the core services again.
If no matching containers are running, the `docker stop` command may report that no containers were provided.

```bash
docker stop $(docker ps -q --filter "name=hiclaw-")
docker start hiclaw-controller hiclaw-manager hiclaw-worker-alice
```
