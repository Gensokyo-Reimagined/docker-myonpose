## udonge
This stack maintains the proxy and minecraft servers

### environment variables

```properties
DIR_MINECRAFT=/opt/docker/data/minecraft/
DIR_DOCKER_DATA=/opt/docker/data
DIR_CONFIGS=/opt/docker/data/server-configs
RESTIC_PASWORD_BUILD=
RESTIC_PASWORD_SURVIVAL=
RCON_PASSWORD=
MYSQL_ROOT_PASSWORD=
BACKUPS_RCLONE_CONF=/opt/docker/compose/secrets/rclone.conf
PRUNE_RESTIC_RETENTION=--keep-daily 7 --keep-weekly 5 --keep-monthly 12 --keep-yearly 75
GITHUB_TOKEN=
REPOSILITE_PLUGINS_TOKEN=
```
