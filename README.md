# Spine

### Import + Settings

[Importing Spine Assets into Unity](http://ru.esotericsoftware.com/spine-unity#Importing-Spine-Assets-into-Unity)

```
1. an \_Atlas asset for the texture atlas file (`.atlas.txt`). It holds a reference to the material and the `.atlas.txt` file.
2. a \_Material asset for each texture atlas page (`.png`). It holds references to the shader and the `.png` texture.
3. a \_SkeletonData asset for skeleton data files (`.json`, `.skel.bytes`). 
It holds a reference to the `.json` or `.skel.bytes` file and the generated 
**\_Atlas** asset. It additionally provides custom import and animation settings 
for your skeleton, see section [Skeleton Data Asset](http://ru.esotericsoftware.com/spine-unity#Skeleton-Data-Asset).

Предварительный просмотр, быстрая замена
Устранение неполадок - https://www.youtube.com/watch?v=AoTRahDLKjs + см.документация
Edit - Preferences - Spine
```

### Getting started scenes

https://www.youtube.com/watch?v=DxDZtTK2nlE

1:
````
Скрипты:

SceletonAnimation.cs - основной скрипт spine (main anim)
SpineBlink - skeletonAnimation.AnimationState.SetAnimation (blonk anim) 

````
2:

````
SetAnimation, Mix, AddAnimation, Events, TrackEntry(management through throw code)
````
3:
````
Two Objects interaction: SetAnimation, AddAnimation (trackIndex, loop), Events
````
**4!(TrackEntry)**:
````
Control animations with input (MVC): Findbone, SetLocalPosition, WASD,SPACE,
Attach,entThreshold, AddEmptyAnimation 
````
5:
````
Platformer: shadows, events(sound,ps), Transitions&GetCurrent, Pixel Lit shader, 
SkeletonUtilityBone - SkeletonUtility GroundConstraint (other examples)
````
6:
````
SkeletonGraphic(in UI) BoneFollowerGraphic
````

Sceleton Mecanim - управление через Анимтор юнити

Other examples - unity + yt