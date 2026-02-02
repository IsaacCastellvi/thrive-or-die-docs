#### Description

The Map Generator is a static class that manages the generation of the `GROUND` tilemap.

This class acts according to the data stored in the [MapGenerationData](../MapGeneratorData/MapGeneratorData.md)

#### API Reference

<div class="borderless-table">

> [!example] Fields
> | Name | Type |Description |
> | :------- | :-------------------------------------------- | :--------------------- |
> | **groundMap** | `IReadOnlyList<IReadOnlyList<MapTile>>` | Getter for a readonly version of the ground MapTile store |

> [!example] Methods
> | Name | Description | Ref |
> | :------- | :-------------------------------------------- | :--------------------- |
> | **PopulateMap** | Populates the map (Gennerates it) | [PopulateMap](./Methods/PopulateMap.md) |

</div>

###### Namespace

[ThriveOrDie.Map](../ThriveOrDie.Map.md)
