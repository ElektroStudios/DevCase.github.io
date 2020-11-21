# IMetaCollection(*T*).Count Property 
 

The count of items in the collection. 

 This is not inherited from ICollection since this meta-collection cannot be extended by users.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections">DevCase.Core.Collections</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
long Count { get; }
```

**VB**<br />
``` VB
ReadOnly Property Count As Long
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMetaCollection
Dim value As Long

value = instance.Count

```

**C++**<br />
``` C++
property long long Count {
	long long get ();
}
```

**F#**<br />
``` F#
abstract Count : int64 with get

```


#### Property Value
Type: Int64<br />\[Missing <value> documentation for "P:DevCase.Core.Collections.IMetaCollection`1.Count"\]

## See Also


#### Reference
<a href="T_DevCase_Core_Collections_IMetaCollection_1">IMetaCollection(T) Interface</a><br /><a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />