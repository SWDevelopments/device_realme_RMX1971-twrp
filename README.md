# android_device_realme_RMX1971
For building PBRP for Realme 5 pro

## Features

Works:

- Everything

## Compile

First checkout manifest :

```
repo init -u git://github.com/PitchBlackRecoveryProject/manifest_pb.git -b android-9.0
repo sync
```

Finally execute these:

```
. build/envsetup.sh
lunch omni_RMX1971-eng
mka pbrp
```

To test it:

```
flash via recovery
```


## Thanks

- Thanks to @pjgowtham for the OFOX Bringup
- Thanks to @mauronfrio for the TWRP trees
