#### Signature

```cs
static void SetSettingValue<Type>(string name, Type value);
```

#### Parameters

- **name:** The name of the setting to set
- **value** The value to set

#### Generics

- **Type** The type of the variable

##### Exceptions

- Throws if the setting is not found
- Throws if the type of the value is incorrect

#### Description

Attempts to set the value of the setting named like `name`. If no setting exists or the type of the value is not correct it throws.
