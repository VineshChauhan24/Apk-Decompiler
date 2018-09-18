## Fork of Show java

An apk decompiler for android. Built on Android Studio 3.1 

## About
This is a Decompiler that extracts the source code of an Android application (including XML files and image assets). Works directly from your android device.

## Features

- Select either **CFR 0.110**, **JaDX 0.8.0** or **FernFlower (analytical decompiler)** to use as the decompiler (more to come).
- Runs directly on an android device (4.x and above).
- Select apk from sdcard (or) from a list of installed applications.
- Easy to use.
- Decompiles resources too (layouts, Drawables, Menus, AndroidManifest, image assets).
- Displays code in a clean-syntax-highlighted form.
- The decompiled source can easily be copied from the sdcard (source is stored in ShowJava folder in the sdcard).
- Simple source browser with a summary of all decompilation errors.
- Each decompiled source file has commented references to classes that could not be decompiled.
- Share the decompiled source easily with the built in archive + share mechanism.

## Known Issues
1. Does not work with system applications in most of the phones (especially ones that are not de-odexed).
2. Slow on phones with single core processors.

## Contributing to ShowJava

Head over [here](https://github.com/niranjan94/show-java/blob/master/CONTRIBUTING.md) to know more about how to contribute, report bugs and request feature additions.

## Open Source License

Unless explicitly stated otherwise all files in this repository are licensed under the [GNU Affero General Public License v3.0](https://www.gnu.org/licenses/agpl-3.0.txt). All projects **must** properly attribute [The Original Source](https://github.com/niranjan94/show-java). 
    
    Show Java - A java/apk decompiler for android
    Copyright (C) 2017 Niranjan Rajendran

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as published
    by the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU Affero General Public License for more details.

    You should have received a copy of the GNU Affero General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

An unmodified copy of the above license text must be included in all forks.

To obtain the software under a different license, please contact [Niranjan Rajendran](https://niranjan.io) at `me <at> niranjan.io`.

## External Credits

1. A Big-Huge Thanks to Lee Benfield ([lee@benf.org](mailto:lee@benf.org)) for his awesome CFR - Class File Reader
2. Panxiaobo ([pxb1988@gmail.com](mailto:pxb1988@gmail.com)) for dex2jar.
3. [Liu Dong](https://github.com/xiaxiaocao) for apk-parser.
4. [Ben Gruver](https://github.com/JesusFreke/) for dexlib2.
5. [skylot](https://github.com/skylot) for JaDX.
6. [JetBrains](https://github.com/JetBrains) for FernFlower analytical decompiler.

> Android, Google Play and the Google Play logo are trademarks of Google Inc.
