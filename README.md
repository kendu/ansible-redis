# Redis role
Installs and configures redis server.

## Optional variables
* redis_port: Port on which redis listens
* redis_bind_address: Address on which redis listens
* redis_base_dir: Redis directory
* redis_dump_file: just a filename for dump, do't include path.


## Edit only if you know what you're doing
* redis_repo: Ppa repo to use for redis.
* redis_config_include_dir: Directory with config  files to include into the main config file.
* redis_pid_file: Pid file for redis process.
