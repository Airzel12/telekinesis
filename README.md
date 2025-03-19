# Telekinesis Mod

This mod adds telekinesis functionality to **Lethal Company** using **BepInEx**.

## Mod Information

- **Mod Name**: Telekinesis
- **Version**: 1.0.0
- **Dependencies**: 
  - **BepInEx-BepInExPack** version 5.4.2100

## Runtime Target

This mod is built with **.NET Core 8.0** as the runtime target.

```json
{
    "runtimeTarget": {
        "name": ".NETCoreApp,Version=v8.0",
        "signature": ""
    },
    "compilationOptions": {},
    "targets": {
        ".NETCoreApp,Version=v8.0": {
            "Telekinesis 1/1.0.0": {
                "runtime": {
                    "Telekinesis 1.dll": {}
                },
                "dependencies": {
                    "BepInEx-BepInExPack": "5.4.2100"
                }
            }
        }
    },
    "libraries": {
        "Telekinesis 1/1.0.0": {
            "type": "project",
            "serviceable": false,
            "sha512": ""
        },
        "BepInEx-BepInExPack/5.4.2100": {
            "type": "package",
            "serviceable": true,
            "sha512": ""
        }
    }
}
