# Proxmox Restore Size

# Summary

* how to resize
* donation

# how to resize

from datacenter go to the storage and remove lm-vm storage then go to the bash shell and write the following:

```
lvremove /dev/pve/data
lvresize -l +100%FREE /dev/pve/root
resize2fs /dev/mapper/pve-root

```

# Donation

If this repo helped you, you can donate me at the following monero address:
```

4B9WQivaHfd3miDfPKEfCianocGpBx9d8FXycz2vmNW3aBDVKHgkBd9Gmapt4RBVEpTwnehujsiUBBehUiLvnEHs7VFstCC

```

or donate with paypal:
```
https://www.paypal.me/francescodisales
```

