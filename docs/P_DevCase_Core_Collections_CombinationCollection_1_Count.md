# CombinationCollection(*T*).Count Property 
 

Gets the number of unique combinations that are defined in this meta-collection. 

 This value is mathematically defined as `Choose(M, N)` where `M` is the set size and `N` is the subset size. 

 This is, `M! / (N! * (M-N)!)`.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections">DevCase.Core.Collections</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public long Count { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Count As Long
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As CombinationCollection
Dim value As Long

value = instance.Count

```

**C++**<br />
``` C++
public:
virtual property long long Count {
	long long get () sealed;
}
```

**F#**<br />
``` F#
abstract Count : int64 with get
override Count : int64 with get
```


#### Property Value
Type: Int64<br />\[Missing <value> documentation for "P:DevCase.Core.Collections.CombinationCollection`1.Count"\]

#### Implements
<a href="P_DevCase_Core_Collections_IMetaCollection_1_Count">IMetaCollection(T).Count</a><br />

## See Also


#### Reference
<a href="T_DevCase_Core_Collections_CombinationCollection_1">CombinationCollection(T) Class</a><br /><a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />