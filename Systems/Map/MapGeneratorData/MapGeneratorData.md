#### Description

MapGeneratorData is a [ScriptableObject](https://docs.unity3d.com/6000.3/Documentation/Manual/class-ScriptableObject.html) that stores the data for the geeneration of the map.

The default settings are stored in `Resources/MapGenerationData.asset`

#### Shape

```cs
  int mapSize; // The map size
  TileBase[] groundTiles; // The collection of ground tiles to use
```

###### Namespace

[ThriveOrDie.Map](../ThriveOrDie.Map.md)
