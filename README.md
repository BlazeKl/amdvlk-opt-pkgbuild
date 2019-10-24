# amdvlk-opt-pkgbuild
optional amdvlk driver pkgbuild for arch based distros

keep RADV the default vulkan driver, use amdvlk only if you need it

### Usage

from terminal
```
VK_ICD_FILENAMES=/opt/amdvlk/usr/share/vulkan/icd.d/amd_icd64.json yourcommand
```
steam launch options
```
VK_ICD_FILENAMES=/opt/amdvlk/usr/share/vulkan/icd.d/amd_icd64.json %command%
```
