# manage_ap
Wrapper for [create_ap](https://github.com/oblique/create_ap) to switch an AP together with airplane mode (NetworkManager).

```
Usage: manage_ap [option]

Options:
-h, --help        Show this help
-u, --up          Start create_ap
-d, --down        Stop create_ap
-s, --sleep       Stop create_ap instance and activate plane mode
-r, --resume      Deactivate plane mode and start create_ap

NOTE: create_ap instances are created/destroyed using the commands specified in the script parameters, edit them as you need first
```
Can be used with cron or sleep to setup snooze times or simply as an alias.
