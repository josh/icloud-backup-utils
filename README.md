# icloud-backup-utils

Scripts creating backups of iCloud data.

## Apps

- [x] iCloud Drive
- [ ] Photos
- [ ] Mail
- [ ] Contacts
- [ ] Calendar
- [x] Reminders
- [x] Notes
- [x] Keychain

## Support

- [x] macOS Mojave 10.14
- [x] macOS Catalina 10.15
- [ ] macOS Big Sur 11

## Install

```sh
$ brew install josh/tap/icloud-backup-utils
```

## Enable security permissions

On macOS 10.15+, running the backup script from launchd will error unless Full Disk Access is given to `/bin/bash`.

```
tar: Could not pack extended attributes: Operation not permitted
```

Add `/bin/bash` to "Full Disk Access":

![](https://user-images.githubusercontent.com/137/90440061-78347080-e08b-11ea-915f-dc72beaf0ba4.png)
