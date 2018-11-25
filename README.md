# Lost Ark - FULL GAME SDK!

Hi! This is a educational project. Don't use it for evil things.

# OFFSETS
**BASE ADRESS:** EFEngine.dll
|   NAME             |OFFSET                         |SIGNATURE                         |
|----------------|-------------------------------|-----------------------------|
|GOBJECTS|`'1D0E7E8'`            |"(+0x99) E8 ? ? ? ? 4C 8D 3D ? ? ? ? 66 0F 1F 44 00 ?"            |
|GNAME|`"1D0E4A0"`            |"(+0x06) 48 63 12 48 8B 05 ? ? ? ? "            |
|PROCESS EVENT|`293A50 - ProcessEventIndex: 0x43`|"40 55 41 56 41 57 48 81 EC ? ? ? ? 48 8D 6C 24 ?"|
|UENGINE|`"1E1B7B0"`            |"(+0x04) 44 89 B0 ? ? ? ? 48 8B 0D ? ? ? ? "            |
|UWORLD|`"1E1FD38"`            |"48 8B 05 ? ? ? ? 48 8B FA 48 8B 88 ? ? ? ? "            |


## How to use SDK

* 1. Make sure to add in your Project both LA_Basic.hpp/cpp and LA_Core_functions.cpp
*  2. Don't forget to set GObjects/Gname adress in LA_BASIC.cpp
* 3. Do your stuff

