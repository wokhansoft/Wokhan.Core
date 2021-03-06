# EnumerableExtensions.Pivot&lt;T,TKeys,TPivoted,TAggregate&gt; method

Creates a pivot table (a table where columns are created from specified values in a collection) from a IEnumerable of *T*, using the specified selector and aggregators.

```csharp
Example to be added soon
```

```csharp
public static IEnumerable<object> Pivot<T, TKeys, TPivoted, TAggregate>(this IEnumerable<T> src, 
    Expression<Func<T, TKeys>> keysSelector, Expression<Func<T, TPivoted>> pivotSelectorExpr, 
    Func<IEnumerable<T>, TAggregate> aggregateSelector)
```

| parameter | description |
| --- | --- |
| T | Items type |
| TPivoted | Type of the pivoted data |
| TKeys | Type of the keys |
| TAggregate | Type of computed aggregated data for each pivot |
| src | Source collection |
| keysSelector | Keys selector (used as keys for the groups aggregation for pivoted values will be computed on) |
| pivotSelectorExpr | Expression to get the properties to compute the pivot on |
| aggregateSelector | Aggregation calculation method |

## See Also

* class [EnumerableExtensions](../EnumerableExtensions.md)
* namespace [Wokhan.Collections.Generic.Extensions](../../Wokhan.Core.md)

<!-- DO NOT EDIT: generated by xmldocmd for Wokhan.Core.dll -->
