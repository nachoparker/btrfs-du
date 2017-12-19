# btrfs-du
Easily print BTRFS subvolume/snapshot disk usage

## Usage

```
# btrfs-du /home

Subvolume                                                         Total  Exclusive  ID
─────────────────────────────────────────────────────────────────────────────────────────
.snapshot2017-08-09                                            75.77GiB  105.95MiB  343
.snapshot2017-08-10                                            75.78GiB  103.46MiB  346
.snapshot2017-08-11                                            75.78GiB  514.47MiB  347
.snapshot2017-08-23                                            76.07GiB  568.11MiB  348
.snapshot2017-09-05                                            76.66GiB  648.50MiB  349
.snapshot2017-10-11                                            63.51GiB    2.71GiB  391
.snapshot2017-11-13                                            62.78GiB    1.09GiB  392
.snapshot2017-11-29                                            63.40GiB  974.05MiB  410
.snapshot2017-12-11                                            64.21GiB  682.08MiB  455
─────────────────────────────────────────────────────────────────────────────────────────
Total exclusive data                                                            7.32GiB
```

Without arguments, defaults to `/`

Inspired by [btrfs-size](https://github.com/agronick/btrfs-size) by Kyle Agronick
                                                                                                                                                                                                      
More at [ownyourbits.com](https://ownyourbits.com/2017/12/06/check-disk-space-of-your-btrfs-snapshots-with-btrfs-du/)
