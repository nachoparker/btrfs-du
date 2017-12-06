# btrfs-du
Easily print BTRFS subvolume/snapshot disk usage

## Usage

```
# btrfs-du /home

Snapshot                       Total      Exclusive  ID
────────────────────────────────────────────────────────────
.snapshot2017-08-09            68.89GB    1.90GB     343
.snapshot2017-08-10            81.36GB    111.10MB   346
.snapshot2017-08-11            81.37GB    108.49MB   347
.snapshot2017-08-23            81.38GB    539.47MB   348
.snapshot2017-09-05            81.68GB    595.71MB   349
.snapshot2017-10-11            82.32GB    680.01MB   391
.snapshot2017-11-13            68.20GB    2.91GB     392
.snapshot2017-11-29            67.41GB    1.18GB     410
────────────────────────────────────────────────────────────
                            Total exclusive data: 7.48GB
```

Without arguments, defaults to `/`

Inspired by [btrfs-size](https://github.com/agronick/btrfs-size) by Kyle Agronick
                                                                                                                                                                                                      
More at [ownyourbits.com](https://ownyourbits.com/2017/12/06/check-disk-space-of-your-btrfs-snapshots-with-btrfs-du/)
