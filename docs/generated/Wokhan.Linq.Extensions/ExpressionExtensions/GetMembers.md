# ExpressionExtensions.GetMembers&lt;T,TR&gt; method

Get all members used in a LINQ Expression (built from a lambda for instance)

```csharp
public static IList<MemberInfo> GetMembers<T, TR>(this Expression<Func<T, TR>> expression)
```

| parameter | description |
| --- | --- |
| T | Expression's input type |
| TR | Expression's return type |
| expression | Source expression |

## Return Value

A list of MemberInfo

## See Also

* class [ExpressionExtensions](../ExpressionExtensions.md)
* namespace [Wokhan.Linq.Extensions](../../Wokhan.Core.md)

<!-- DO NOT EDIT: generated by xmldocmd for Wokhan.Core.dll -->
