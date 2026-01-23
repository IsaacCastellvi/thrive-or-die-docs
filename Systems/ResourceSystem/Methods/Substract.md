#### Signature

```cs
bool Substract(int amount, bool zeroOut = false);
```

#### Parameters

- **amount:** The amount to set as the resource amount
- **zeroOut:** Whether to set to 0 in case of insuficient funds <br> Default `FALSE`

#### Returns

Whether the funds were substracted

#### Description

Substracts the passed amount from the current resource amount.
If the amount to substract is grater than the current funds it will:

- Set to `0` if `zeroOut` is true
- **NOT** substract anything
