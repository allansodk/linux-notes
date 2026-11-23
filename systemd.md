# systemd

- `systemctl list-units --failed`
- `journalctl -u <unit> --since -1h -f`
- Timer: `systemctl list-timers`
- Drop-in: `systemctl edit <unit>` -> `/etc/systemd/system/<unit>.d/override.conf`
