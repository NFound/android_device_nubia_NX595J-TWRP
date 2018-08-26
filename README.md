## How-to compile it:

To build:

```sh
. build/envsetup.sh
lunch lineage_NX595J-eng
make recoveryimage
```

TO flash

```sh
fastboot oem nubia_unlock NUBIA_NX595J
fastboot flash recovery recovery.img
```
