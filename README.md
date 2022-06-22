# Proxmox Dark Mode

Enable dark mode in Proxmox for all users.

## Role Variables

### pve_dark_mode_enabled

Enable or dark mode or restore the default light theme.

default: `false`

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
