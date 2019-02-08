Installs docker onto a linux host and adds a cron/systemd job to cleanup unused
images/containers.

| Option                     | Useage                                       |
| -------------------------- | -------------------------------------------- |
| docker_state               | Ensures the docker package is present/absent |
| docker_listen_interfaces   | List of interfaces to listen on              |
| docker_allow_external_icc  | Connect to public ports on another network   |
| docker_cleanup_enabled     | If cleanup is enabled                        |
| docker_cleanup_file        | Name of the cron file to cleanup docker      |
| docker_cleanup_frequency   | How often to perform cleanup (weekly/hourly) |
| os_proxy                   | Sets the docker system proxy                 |

| Tested on      |
| -------------- |
| ubuntu 14.04.5 |
| ubuntu 18.04   |
