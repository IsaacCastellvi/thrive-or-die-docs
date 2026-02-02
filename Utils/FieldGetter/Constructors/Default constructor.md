#### Signature

```cs
FieldGetter(Func<FieldType, FieldType> getter)
```

#### Parameters

- **getter** The getter function to use when getting the value.

##### Getter example

```cs
static FieldType Getter(FieldType _backer)
{
  #region Getter
  if (_backer == null) _backer = newValue;
  return _backer;
  #endregion
}
```

#### Description

The getter is intended that this getter initializes the value if none is present.
The getter gets passed a paramenter of type `FieldType` witht he current value of the backer
