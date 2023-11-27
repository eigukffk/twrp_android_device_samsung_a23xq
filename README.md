# TWRP device tree for samsung SM-A236E (a23xq)

Add to
`.repo/local_manifests/a23xq.xml`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <project name="mrx7014/twrp_android_device_samsung_a23xq" path="device/samsung/a23xq" remote="github" revision="twrp_a23xq" />
</manifest>

```
Then run `repo sync` to check it out.

Kernel sources are available at: https://opensource.samsung.com/uploadList, tap the link, and type in the search bar: SM-A236B, This fork version is using "A236BXXU2BVK7", Use WinRAR or 7-Zip to extract Kernel.tar.gz


Release: https://github.com/eigukffk/Action-TWRP-Builder/releases/tag/6974728754 (Touch isn't working on TWRP for some reason, well maybe it's the kernel touchscreen detection problem, probably, like idk)
