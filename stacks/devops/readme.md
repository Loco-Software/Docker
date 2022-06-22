# `@LOCO-SOFTWARE/DOCKER/STACKS/DEVOPS`

## Port Ranges
| Range-from | Range-to | Service |
|------------|----------|---------|
| 30000      | 32000    | GitLab  |

## Port Mappings
| Host-Port | Container-Port | Service | Endpoint Description |
|-----------|----------------|---------|----------------------|
| 30022     | 22             | GitLab  | GitLab SSH           |
| 30080     | 80             | GitLab  | GitLab HTTP          |
| 30443     | 443            | GitLab  | GitLab HTTPS         |