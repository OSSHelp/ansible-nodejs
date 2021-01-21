# nodejs

[![Build Status](https://drone.osshelp.ru/api/badges/ansible/nodejs/status.svg)](https://drone.osshelp.ru/ansible/nodejs)

Simple role which installs Node.js

## Usage (example)

### Current stable (12)

```yaml
    - role: nodejs
```

### Custom version

```yaml
    - role: nodejs
      nodejs_version: 10
```

## Available parameters

| Param | Default | Description |
| -------- | -------- | -------- |
| `nodejs_setup` | `full` | Setup mode. See [OSSHelp KB article](https://oss.help/kb4895) |
| `nodejs_version` | `12` | Node.js version |
| `nodejs_src_repo_enabled` | `false` | Adds Node.js src repo |
| `nodejs_global_modules` | `[]` | Node.js global modules |

## Useful links

- [Official documentation](https://nodejs.org/en/)

## TODO

- add nodejs app units generation

## License

GPL3

## Author

OSSHelp Team, see <https://oss.help>
