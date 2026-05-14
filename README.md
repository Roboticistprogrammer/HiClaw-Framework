# HiClaw-Framework

Custom util functions and setup scripts for my personal HiClaw Agent Framework.

## Docker Tools

```bash
docker stop $(docker ps -q --filter "name=hiclaw-")
docker start hiclaw-controller hiclaw-manager hiclaw-worker-alice
```
