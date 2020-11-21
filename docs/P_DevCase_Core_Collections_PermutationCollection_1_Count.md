# PermutationCollection(*T*).Count Property 
 

The count of all permutations that will be returned. 

 If type is <a href="T_DevCase_Core_Collections_MetaCollectionType">WithoutRepetition</a>, then this does not double count permutations with multiple identical values. 

 I.e. count of permutations of "`AAB`" will be `3` instead of `6`. If type is <a href="T_DevCase_Core_Collections_MetaCollectionType">WithRepetition</a>, then this is all combinations and is therefore `N!`, where `N` is the number of values.

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
Dim instance As PermutationCollection
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
Type: Int64<br />\[Missing <value> documentation for "P:DevCase.Core.Collections.PermutationCollection`1.Count"\]

#### Implements
<a href="P_DevCase_Core_Collections_IMetaCollection_1_Count">IMetaCollection(T).Count</a><br />

## See Also


#### Reference
<a href="T_DevCase_Core_Collections_PermutationCollection_1">PermutationCollection(T) Class</a><br /><a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />