# Howto
## Preparation
Issues creating bootable USB from Windows 10 - balenaEtcher worked, Rufus/Unetbootin/UniversalUSB did not :-(

## Configuration preparation
1. in github repo create config.yaml - https://github.com/rancher/k3os
2. shorten url using bit.ly
3. on boot use command arguments
```
k3os.install.device=[device]
k3os.install.config_url=https://bit.ly/[url]
```

For password encryption used `openssl passwd -1`.
