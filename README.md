# GitWorkshop
just a small git workshop for gamejams.

## General

### 1 File 1 Person principle
To avoid conflicts, it is best to have only one person responsible for one file.
In order to reduce coordination efforts it is suggested to have personal directories for your private playgrounds (especially Scenes)

example Unity
```
/Assets/Scenes/mainScene1.scene
/Assets/Scenes/level1.scene
/Assets/Scenes/thomas/testScenePhysics.scene
/Assets/Scenes/anita/testSceneAirplane.scene
/Assets/Prefabs/
```

### Unix style Line Endings
Windows uses CRLF for line endings, other OS use LF.
committing UNix-style line endings decreases further merges and conflicts.
It is default "ON" for "Git for Windows" anyway. and can be enforeced by setting ´core.autocrlf´ to `true`

## Unity3D

- use your own playground scene (don't do testing / firther development of assets in )
