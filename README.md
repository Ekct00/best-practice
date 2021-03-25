# best-practice

### Install JDK
- Mac
  + brew install --cask adoptopenjdk
  + [.pkg版本](https://adoptopenjdk.net/archive.html?variant=openjdk15&jvmVariant=hotspot)
  
### Install Plantuml
- Mac
  + brew install plantuml  

### switch xci config
```
Add the kip1 patch under the launch options for CFW. Here is an example.

{--- Custom Firmware ---}
[CFW (SYSNAND)]
emummc_force_disable=1
fss0=atmosphere/fusee-secondary.bin
kip1patch=nosigchk
atmosphere=1
logopath=bootloader/bootlogo.bmp
icon=bootloader/res/icon_payload.bmp
{}

[CFW (EMUMMC)]
fss0=atmosphere/fusee-secondary.bin
kip1patch=nosigchk
atmosphere=1
logopath=bootloader/bootlogo.bmp
icon=bootloader/res/icon_payload.bmp
{}
```
