---
title: "Compose Pause unpause Command"
slug: "Compose Pause unpause Command"
weight: 37
---

```sh
 example-voting-app git:(main) docker compose pause
[+] Running 4/0
 ⠿ Container example-voting-app-db-1      Paused                                                                                                                                     0.0s
 ⠿ Container example-voting-app-redis-1   Paused                                                                                                                                     0.0s
 ⠿ Container example-voting-app-worker-1  Paused                                                                                                                                     0.0s
 ⠿ Container example-voting-app-result-1  Paused                                                                                                                                     0.0s
➜  example-voting-app git:(main) 
```


#### Pauses running containers of a service. They can be unpaused with docker compose unpause.

```sh
docker compose unpause
[+] Running 4/0
 ⠿ Container example-voting-app-worker-1  Unpaused                                                                                                                                   0.0s
 ⠿ Container example-voting-app-redis-1   Unpaused                                                                                                                                   0.0s
 ⠿ Container example-voting-app-result-1  Unpaused                                                                                                                                   0.0s
 ⠿ Container example-voting-app-db-1      Unpaused                                                                                                                                   0.0s
➜  example-voting-app git:(main) 

```


