#### Description

FieldGetter is a wrapper record for a public property with a backer field ment to be initialized on first access.

#### Signature

```cs
record FieldGetter<FieldType>
```

#### API Reference

<div class="borderless-table">

> [!example] Generics
> | Name | Description |
> | :------- | :-------------------------------------------- | :--------------------- |
> | **FieldType:** | The underlying type of the value to store |

> [!example] Fields
> | Name | Type |Description |
> | :------- | :-------------------------------------------- | :--------------------- |
> | **value:** | `FieldType` | Property that returns the value though calling the `getter` passed in the constructor |

> [!example] Constructors
> | Name | Description | Ref |
> | :------- | :-------------------------------------------- | :--------------------- |
> | **Default:** | Creates a new FieldGetter with the passed getter | [Default constructor](./Constructors/Default%20constructor.md) |

</div>

###### Namespace

[ThriveOrDie.Settings](../ThriveOrDie.Settings.md)
