```
░█▀▄░█▀█░▀█▀░▀█▀░█▀▀░█▀▄░█░█░░░█▀█░█▀█░▀█▀░▀█▀░█▀▀░█░█░░
░█▀▄░█▀█░░█░░░█░░█▀▀░█▀▄░░█░░░░█░█░█░█░░█░░░█░░█▀▀░░█░░░
░▀▀░░▀░▀░░▀░░░▀░░▀▀▀░▀░▀░░▀░░░░▀░▀░▀▀▀░░▀░░▀▀▀░▀░░░░▀░░░
```

A simple battery level notifier

## USAGE
- copy the `check-batt` script into $HOME/bin/
- copy the systemd service and timer into $HOME/.config/systemd/user/
- modify the timer period if you wish
- enable and start the service
    ```
    systemctl --user enable battery-notify
    systemctl --user start battery-notify
    ```
