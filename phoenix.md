## 1.2 Phoenix 

-  fingerprint: Uprev to 2.3 HAL
-  fingerprint: Clang-format and clean up the code
-  Drop unnecessary fqnames from manifests
-  Sync idle/touch timer to raven
-  Sync durations props with raven
-  Switch to SF phase offsets from redfin
-  Drop surfaceflinger vsync phase offsets
-  Copy DispSync offsets from cmi
-  overlays: Swtich to RRO
- "[TEMP] -  Disable wfd for now"
-  Switch to AOSP WFD
-  parts: Change dirac_enable string
-  Update blobs from PHOENIX 21.11.17

## 1.3 Phoenix

- phoenix: props: Don't write binary XML files
- phoenix: overlay: do not specify quick_qs_offset_height
- phoenix: rootdir: Configure dynamic schedtune boost
- phoenix: rootdir: Set schedtune.boost to 1
- phoenix: rootdir: Set swappiness to 100
- phoenix: Enable idle_state mechanism
- phoenix: rootdir: Modify the cpuset setting
- phoenix: rootdir: Add SchedTune configuration
- phoenix: use sunfish cpusets
- phoenix: rootdir: set zram size to 50% of total ram
- phoenix: Configure zram from separate fstab
- phoenix: adjust zram write back policy
