# Third-party notices and licensing status

This inventory is based on the names and version/copyright metadata embedded in the files currently tracked by this repository. It is not a complete software bill of materials, legal advice, or confirmation that this repository has permission to redistribute every file. The build/source provenance of several binaries has not been established.

## Components identified in the package

| Files | Available identification | License / source information |
|---|---|---|
| `mikohime/windows/OpenAL32.dll`, `OpenAL64.dll` | OpenAL Soft 1.25.1; embedded copyright resource identifies GNU Library General Public License, version 2, June 1991 | [OpenAL Soft 1.25.1 COPYING](https://github.com/kcat/openal-soft/blob/1.25.1/COPYING). Verify source correspondence, modifications, and applicable source-code/relinking obligations for this distribution. |
| `mikohime/alsoft-config/Qt6Core.dll`, `Qt6Gui.dll`, `Qt6Widgets.dll`, `platforms/qwindows.dll` | Qt 6.10.0; The Qt Company Ltd. and other contributors | Qt is offered under multiple license options. The binary metadata does not establish which terms apply to these exact builds. See [Qt 6.10 licensing](https://doc.qt.io/qt-6.10/licensing.html), [LGPL guidance](https://doc.qt.io/qt-6.10/lgpl.html), and [Qt 6.10 third-party components](https://doc.qt.io/qt-6.10/licenses-used-in-qt.html). Confirm the distribution's Qt source package, license choice, and applicable component notices. |
| `mikohime/alsoft-config/zlib1.dll` | zlib 1.3.1; copyright metadata names Jean-loup Gailly and Mark Adler | [zlib license](https://www.zlib.net/zlib_license.html). Confirm that this DLL corresponds to the identified release and retain the applicable notice. |
| `mikohime/alsoft-config/libgcc_s_seh-1.dll`, `libstdc++-6.dll` | GCC runtime DLL names; build/version metadata is not present | Identify the compiler/runtime build and include its corresponding license and exception notices. |
| `mikohime/alsoft-config/libwinpthread-1.dll` | MinGW-w64 Project; embedded copyright says 2010–2023; version resource says 1.0.0.0 | Confirm the exact MinGW-w64 source/build and its license before documenting redistribution terms. |
| `mikohime/alsoft-config/alsoft-config.exe` | No useful product, version, company, or copyright metadata found | Identify the author/source and obtain documentation of redistribution permission and applicable license. |
| `oalinst.exe` | OpenAL Installer 2.0.7.0; Creative Labs Inc.; copyright 2009 | The embedded metadata does not state redistribution terms. Confirm permission for this exact installer before redistributing it. |

## Project and author permissions

The README credits Yue (Himemiko) as the author of the add-on. The repository maintainer reports that Yue authorized “full redistribution rights for noncommercial uses.” No standard license name, version, or license text was provided. This records noncommercial redistribution permission only; it does not assert additional permissions, such as commercial use, or apply to third-party components.

No license is applied to the repository as a whole by this notice. Each component remains subject to its own rights and terms. The license texts included with release archives are reference copies for the identified LGPL options; their inclusion does not establish that a particular binary is licensed under those terms or satisfy all source, relinking, attribution, or redistribution obligations.

## Release license texts

Release archives include copies of the GNU Library General Public License version 2 and GNU Lesser General Public License version 3 from the GNU website. These are included because the bundled OpenAL Soft metadata identifies LGPL version 2 and Qt 6.10 documents LGPL version 3 as an available license option. Confirm the applicable terms for the actual distributed builds and provide any additional required source, notices, and materials.
