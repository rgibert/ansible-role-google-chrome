# Role Name

Installs Google Chrome

## Requirements

- none

## Role Variables

| Variable | Default | Description |
|----------|---------|-------------|
| google_chrome_stability | stable | Stability level of Chrome to install (stable, unstable, beta) |

## Dependencies

- none

## Example Playbook

```
- hosts:
    - servers
  roles:
    - role: rgibert.google-chrome
```

## License

GPLv3

## Author Information

Richard Gibert <richard@gibert.ca>
