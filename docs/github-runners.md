# GitHub actions runners


## Active Runners

| Name | Location |
|--------|---------|
|gsheet notifier|`/home/pi/actions-runner`|
|video downloader|`/home/pi/actions-runner-ytpi`|

## Useful GitHub Runner Commands

| Command            | Description         | Example Usage                                      |
|--------------------|--------------------|----------------------------------------------------|
| Start        | Start the runner    | `sudo ./svc.sh start`                              |
| Stop        | Stop the runner     | `sudo ./svc.sh stop`                               |
| Restart     | Restart the runner  | `sudo ./svc.sh restart`                            |
| Check Status       | Check runner status | `sudo ./svc.sh status`                             |
| Install     | Install the runner  | `./config.sh --url <repository-url> --token <runner-token>` |
| Uninstall   | Uninstall runner    | `sudo ./svc.sh uninstall`                          |
| Update      | Update the runner   | `sudo ./svc.sh update`                             |

