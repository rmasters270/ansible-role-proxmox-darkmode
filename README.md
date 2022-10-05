# Proxmox Dark Mode

Enable dark mode in Proxmox for all users.

## Role Variables

| Variable                | Required | Default | Choices     | Comments                                                 |
|-------------------------|----------|---------|-------------|----------------------------------------------------------|
| pve_dark_mode_enabled   | yes      | false   | true, false | Enable dark mode or restore the default theme.           |

## Dependencies

Uses script created by Weilbyte from this [project](https://github.com/Weilbyte/PVEDiscordDark).

## Example Playbook

```yaml
  - hosts: proxmox

    vars:
      pve_dark_mode_enabled: true

    roles:
        - rmasters270.proxmox_darkmode
```

## License

MIT

## Author Information

Ryan Masters
