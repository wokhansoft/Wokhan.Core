# DictionaryExtensions.Flatten method

Flattens a dictionary (concatenating the keys using the specified separator, or "." if none.

```csharp
public static IEnumerable<KeyValuePair<object, object>> Flatten(
    this IEnumerable<KeyValuePair<object, object>> src, string parentKey = "", 
    string separator = ".")
```

| parameter | description |
| --- | --- |
| src | Source Dictionary (as a IEnumerable) |
| parentKey | Initial key |
| separator | Keys separator (default: ".") |

## See Also

* class [DictionaryExtensions](../DictionaryExtensions.md)
* namespace [Wokhan.Collections.Generic.Extensions](../../Wokhan.Core.md)

<!-- DO NOT EDIT: generated by xmldocmd for Wokhan.Core.dll -->
