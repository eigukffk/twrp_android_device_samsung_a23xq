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

Kernel sources at: https://github.com/eigukffk/android_kernel_samsung_galaxy_a23_5g *The Kernel is not yet changed, It's still the original*

Release: https://github.com/eigukffk/Action-TWRP-Builder/tags (Touch isn't working on TWRP for some reason, well maybe it's the kernel touchscreen detection problem, probably, like idk)
