<div align="center">

# Spring Constraint

[![Generic badge](https://img.shields.io/github/downloads/VRLabs/Spring-Constraint/total?label=Downloads)](https://github.com/VRLabs/Spring-Constraint/releases/latest)
[![Generic badge](https://img.shields.io/badge/License-MIT-informational.svg)](https://github.com/VRLabs/Spring-Constraint/blob/main/LICENSE)
[![Generic badge](https://img.shields.io/badge/Unity-2019.4.31f1-lightblue.svg)](https://unity3d.com/unity/whats-new/2019.4.31)
[![Generic badge](https://img.shields.io/badge/SDK-AvatarSDK3-lightblue.svg)](https://vrchat.com/home/download)

[![Generic badge](https://img.shields.io/discord/706913824607043605?color=%237289da&label=DISCORD&logo=Discord&style=for-the-badge)](https://discord.vrlabs.dev/)
[![Generic badge](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3Dvrlabs%26type%3Dpatrons&style=for-the-badge)](https://patreon.vrlabs.dev/)

A constraint system with spring behavior

![SpringConstraint](https://github.com/VRLabs/Spring-Constraint/assets/76777936/0a21419d-49d6-4054-8265-9d25850dab11)

### ⬇️ [Download latest Unitypackage](https://github.com/VRLabs/Spring-Constraint/releases/latest)

<!-- 
### 📦 [Add to VRChat Creator Companion]() -->

</div>

---

## How it works

* The constraint is weighted between 3 sources to achieve a spring-like effect.

## Install Guide

https://github.com/VRLabs/Spring-Constraint/assets/76777936/6a5056c7-9f47-4caf-bef0-8eae04f84613

* Drag & drop the ``Spring Constraint`` prefab into the base of your Hierarchy.
* Right click and unpack the prefab, then drag & drop it onto your avatar.
* Expand the prefab hierarchy and find ``Spring Target``
* Move ``Spring Target`` outside of ``Spring Constraint`` and place it anywhere in your avatars hierarchy as needed.

## How to use

* Place your objects inside ``Spring Constraints`` -> ``Container``.
  * Alternatively you can constrain the objects to ``Container``.
* To change the characteristics of the spring, change the position constraint values on the ``Motion`` object:
  * Sources > Spring Target (default 1.1) controls the strength of the spring. Higher values make it harder to stretch the spring. Min: 1, Max: 2
  * Sources > Motion (default 4) dampens acceleration, the higher the value the slower ``Container`` accelerates.

## Performance stats

```c++
Constraints:        2
```

## Hierarchy layout

```html
Spring Constraint
|-Container
|  |-Cube
|-Motion
|-Spring Target
```

## Contributors

* [lin](https://github.com/oofdesu)

## License

Spring Constraint is available as-is under MIT. For more information see [LICENSE](https://github.com/VRLabs/Spring-Constraint/blob/main/LICENSE).

​

<div align="center">

[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/VRLabs.png" width="50" height="50">](https://vrlabs.dev "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Discord.png" width="50" height="50">](https://discord.vrlabs.dev/ "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Patreon.png" width="50" height="50">](https://patreon.vrlabs.dev/ "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Twitter.png" width="50" height="50">](https://twitter.com/vrlabsdev "VRLabs")

</div>

---
