# Baritone Spawner Helper v2

A lightweight Fabric client-side helper for Baritone on Minecraft `1.21.4`.

This mod helps Baritone during spawner mining. When a spawner drops as an item, the helper detects the drop, cancels the current route, and sends Baritone to the dropped spawner coordinates using `#goto`.

## Features

- Fabric client-side mod
- Built for Minecraft `1.21.4`
- Works with Baritone
- Simple F7 GUI
- ON/OFF control buttons
- Auto runs `#mine minecraft:spawner`
- Detects dropped spawner items
- Routes to the drop position with `#goto`

## Requirements

- Minecraft `1.21.4`
- Fabric Loader
- Fabric API
- Java `21`
- Baritone for Fabric

Baritone is required and must be installed separately.

## Controls

Press `F7` to open the helper GUI.

Buttons:

```text
ON     Enable helper and start spawner mining
OFF    Disable helper and cancel Baritone routing
Close  Close the GUI
````

## Commands

```text
/baritonespawnerhelperv2
/baritonespawnerhelperv2 config
```

## Build

Windows:

```bat
.\gradlew.bat clean build
```

Linux/macOS:

```bash
chmod +x gradlew
./gradlew clean build
```

Output:

```text
build/libs/baritone-spawner-helper-v2-2.0.0.jar
```

## Notes

This is a companion helper for Baritone, not an official Baritone addon. It only sends client-side Baritone commands such as `#mine`, `#goto`, and `#forcecancel`.

Use responsibly and follow server rules.

## License

MIT License.

````

Repo description GitHub:

A lightweight Fabric companion mod for Baritone that detects dropped spawners and routes to them automatically.
````

Commit message:

```text
Update README for v2
```
