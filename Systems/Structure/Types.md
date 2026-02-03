
- ### StructureState

Will be used To set the state of a building in the runtime

```cs

public enum StructureState
{
blueprint,
constructing,
active,
damaged,
destroyed,
}

```

- ### StructureType

Used to identify the type of the structure

```cs

public enum StructureType

{
none = 0,
storage,
crafting,
defense,
walls,
decoration,
investigation,
}
```