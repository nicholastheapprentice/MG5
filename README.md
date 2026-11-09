# MG5
## Devlog
1. I think NavMesh works better on plain, simple terrains, since it has pre-made all the necessary functions for pathfinding. For example, Ape Out is a simple topdown 2D game that I like, and you could definetely use NavMesh in it. But if you designed a map that has some unique mechanics or too complicated for NavMesh, then you would have to write your own scripts. For example, the FPS game Isonzo, which has steep mountain terrains, would not be applicable for NavMesh.

2. The loop would check each bird by the iteration. The Vector3.Distance is used to detect the distance between Pudu and a Sparrow. If the distance is less than the _interactDistance, the bird runs away.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)