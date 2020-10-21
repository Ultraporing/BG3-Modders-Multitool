# bg3-mod-packer
Utility for quickly generating Baldur's Gate 3 mod packs from an unpacked workspace.

To use, simply drop the bg3-mod-packer.bat file into your LSLib root directory where it can access divine.exe. Drag and drop your unpacked workspace into the .bat to generate an info.json file and .pak with the same name as your workspace. The workspace name should be the same as your modpack name.

Correct folder structure of mod workspace:

```
ModName
|->Mods
  |->ModName
    |->meta.lsx
|->Public
  |->ModName
    |->Folder1
      |->File.lsx
    |->Folder2
      |->File.lsb
    |->Folder3
      |->File.lsf
```
