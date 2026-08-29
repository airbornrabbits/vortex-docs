---
title: Attributes
description: Attributes are custom properties that can be added to instances which contain your own data. Attributes are similar to properties but you can create and edit your attributes for any instance. Attributes can store Booleans, Numbers, and Strings.
---

## Creating Attributes
Stub

# Methods
### SetAttribute
```
Instance:SetAttribute(Attribute: String, Value: Variant)
```
#### Parameters

```
Attribute: string
The Name of the attribute being set.
```
```
Value: Variant
The Value to set the specified Attribute to.
```

#### Returns
```
()
```
The SetAttribute Method is used for modifying an attributes value. If the value given is nil, the attribute will be removed.
#### Examples
In the code snippet below, it sets the `"Transparent"` Attribute of the Part to `true`.
```luau
local Part = workspace:WaitForChild("Part")
Part:SetAttribute("Transparent", true)
```



Stub
