# Changelog
## Unreal Essentials 1.2.0
- Added IUnrealMemory to the API to help working with memory using the native UE allocator (@TheBestAstroNOT)
  - This is included in version 1.1.0 of the interfaces nuget package

## UTOC Emulator 1.1.3
- Fixed IO Store files not being emulated if the file was created/opened multiple times
- Removed the file size hack as the related bug has now been fixed in File Emulation Framework (see [#15](https://github.com/Sewer56/FileEmulationFramework/issues/15))

## Unreal Essentials 1.1.5
- Added support for The Callisto Protocol