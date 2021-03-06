
[Source](https://docs.docker.com/engine/reference/commandline/ "Permalink to The Docker commands - Docker")

# The Docker commands - Docker

Estimated reading time:  7 minutes 

This section contains reference information on using Docker's command line client. Each command has a reference page along with samples. If you are unfamiliar with the command line, you should start by reading about how to [Use the Docker command line][1].

You start the Docker daemon with the command line. How you start the daemon affects your Docker containers. For that reason you should also make sure to read the [`dockerd`][2] reference page.

### Docker management commands

| Command      | Description                                          |  
| ------------ | ---------------------------------------------------- |  
| [dockerd][2] | Launch the Docker daemon                             |  
| [info][3]    | Display system-wide information                      |  
| [inspect][4] | Return low-level information on a container or image |  
| [version][5] | Show the Docker version information                  |  

### Image commands

| Command      | Description                                                     |  
| ------------ | --------------------------------------------------------------- |  
| [build][6]   | Build an image from a Dockerfile                                |  
| [commit][7]  | Create a new image from a container's changes                   |  
| [history][8] | Show the history of an image                                    |  
| [images][9]  | List images                                                     |  
| [import][10] | Import the contents from a tarball to create a filesystem image |  
| [load][11]   | Load an image from a tar archive or STDIN                       |  
| [rmi][12]    | Remove one or more images                                       |  
| [save][13]   | Save images to a tar archive                                    |  
| [tag][14]    | Tag an image into a repository                                  |  

### Container commands

| Command       | Description                                                     |  
| ------------- | --------------------------------------------------------------- |  
| [attach][15]  | Attach to a running container                                   |  
| [cp][16]      | Copy files/folders from a container to a HOSTDIR or to STDOUT   |  
| [create][17]  | Create a new container                                          |  
| [diff][18]    | Inspect changes on a container's filesystem                     |  
| [events][19]  | Get real time events from the server                            |  
| [exec][20]    | Run a command in a running container                            |  
| [export][21]  | Export a container's filesystem as a tar archive                |  
| [kill][22]    | Kill a running container                                        |  
| [logs][23]    | Fetch the logs of a container                                   |  
| [pause][24]   | Pause all processes within a container                          |  
| [port][25]    | List port mappings or a specific mapping for the container      |  
| [ps][26]      | List containers                                                 |  
| [rename][27]  | Rename a container                                              |  
| [restart][28] | Restart a running container                                     |  
| [rm][29]      | Remove one or more containers                                   |  
| [run][30]     | Run a command in a new container                                |  
| [start][31]   | Start one or more stopped containers                            |  
| [stats][32]   | Display a live stream of container(s) resource usage statistics |  
| [stop][33]    | Stop a running container                                        |  
| [top][34]     | Display the running processes of a container                    |  
| [unpause][35] | Unpause all processes within a container                        |  
| [update][36]  | Update configuration of one or more containers                  |  
| [wait][37]    | Block until a container stops, then print its exit code         |  

### Hub and registry commands

| Command      | Description                                          |  
| ------------ | ---------------------------------------------------- |  
| [login][38]  | Register or log in to a Docker registry              |  
| [logout][39] | Log out from a Docker registry                       |  
| [pull][40]   | Pull an image or a repository from a Docker registry |  
| [push][41]   | Push an image or a repository to a Docker registry   |  
| [search][42] | Search the Docker Hub for images                     |  

### Network and connectivity commands

### Shared data volume commands

| Command              | Description                                                      |  
| -------------------- | ---------------------------------------------------------------- |  
| [volume create][43]  | Creates a new volume where containers can consume and store data |  
| [volume inspect][44] | Display information about a volume                               |  
| [volume ls][45]      | Lists all the volumes Docker knows about                         |  
| [volume rm][46]      | Remove one or more volumes                                       |  

### Swarm node commands

| Command            | Description                                                   |  
| ------------------ | ------------------------------------------------------------- |  
| [node promote][47] | Promote a node that is pending a promotion to manager         |  
| [node demote][48]  | Demotes an existing manager so that it is no longer a manager |  
| [node inspect][49] | Inspect a node in the swarm                                   |  
| [node update][50]  | Update attributes for a node                                  |  
| [node ps][51]      | List tasks running on a node                                  |  
| [node ls][52]      | List nodes in the swarm                                       |  
| [node rm][53]      | Remove one or more nodes from the swarm                       |  

### Swarm swarm commands

### Swarm service commands

[1]: https://docs.docker.com/engine/reference/commandline/cli.md
[2]: https://docs.docker.com/dockerd.md
[3]: https://docs.docker.com/info.md
[4]: https://docs.docker.com/inspect.md
[5]: https://docs.docker.com/version.md
[6]: https://docs.docker.com/build.md
[7]: https://docs.docker.com/commit.md
[8]: https://docs.docker.com/history.md
[9]: https://docs.docker.com/images.md
[10]: https://docs.docker.com/import.md
[11]: https://docs.docker.com/load.md
[12]: https://docs.docker.com/rmi.md
[13]: https://docs.docker.com/save.md
[14]: https://docs.docker.com/tag.md
[15]: https://docs.docker.com/attach.md
[16]: https://docs.docker.com/cp.md
[17]: https://docs.docker.com/create.md
[18]: https://docs.docker.com/diff.md
[19]: https://docs.docker.com/events.md
[20]: https://docs.docker.com/exec.md
[21]: https://docs.docker.com/export.md
[22]: https://docs.docker.com/kill.md
[23]: https://docs.docker.com/logs.md
[24]: https://docs.docker.com/pause.md
[25]: https://docs.docker.com/port.md
[26]: https://docs.docker.com/ps.md
[27]: https://docs.docker.com/rename.md
[28]: https://docs.docker.com/restart.md
[29]: https://docs.docker.com/rm.md
[30]: https://docs.docker.com/run.md
[31]: https://docs.docker.com/start.md
[32]: https://docs.docker.com/stats.md
[33]: https://docs.docker.com/stop.md
[34]: https://docs.docker.com/top.md
[35]: https://docs.docker.com/unpause.md
[36]: https://docs.docker.com/update.md
[37]: https://docs.docker.com/wait.md
[38]: https://docs.docker.com/login.md
[39]: https://docs.docker.com/logout.md
[40]: https://docs.docker.com/pull.md
[41]: https://docs.docker.com/push.md
[42]: https://docs.docker.com/search.md
[43]: https://docs.docker.com/volume_create.md
[44]: https://docs.docker.com/volume_inspect.md
[45]: https://docs.docker.com/volume_ls.md
[46]: https://docs.docker.com/volume_rm.md
[47]: https://docs.docker.com/node_promote.md
[48]: https://docs.docker.com/node_demote.md
[49]: https://docs.docker.com/node_inspect.md
[50]: https://docs.docker.com/node_update.md
[51]: https://docs.docker.com/node_ps.md
[52]: https://docs.docker.com/node_ls.md
[53]: https://docs.docker.com/node_rm.md

  
