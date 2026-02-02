#### Description

The Time Manager manages the in-game clock. The day/night cycle, time speed...

#### API Reference

<div class="borderless-table">

> [!example] Methods
> | Name | Description | Ref |
> | :------- | :-------------------------------------------- | :--------------------- |
> | **GetCurrentTime** | Gets the current in-game time | [GetCurrentTime](./Methods/GetCurrentTime.md) |

</div>

<br/>

#### Internal Reference

<div class="borderless-table">

> [!example] Fields
> | Name | Type |Description |
> | :------- | :-------------------------------------------- | :--------------------- |
> | **TimeSpeed** | `const float` | Time speed multiplyer <br/>Defaults to `72` (1 in-game day every 20 minutes) |
> | **timeSpeedModifier** | `float` | Modifyer for the time speed that can be adjusted dynamically |
> | **inGameTime** | `FieldGetter<DateTime>` | [FieldGetter](../../../Utils/FieldGetter/FieldGetter.md) of the In-Game time. It's hooked to loading the start time from persistent data |

> [!example] Methods
> | Name | Description | Ref |
> | :------- | :-------------------------------------------- | :--------------------- |
> | **HasTimeSpanPassedThisFrame** | Gets the current in-game time | [HasTimeSpanPassedThisFrame](./Methods/HasTimeSpanPassedThisFrame.md) |

</div>

###### Namespace

[ThriveOrDie.TimeProgression](../ThriveOrDie.TimeProgression.md)
