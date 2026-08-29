# Attributes
Attributes are basically custom properties that can be given to an Instance. These properties can be Strings, Booleans, and Numbers (Bare Minimum, confirmation is needed for other datatypes.)

### Creating Attributes
Stub

## Methods
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
