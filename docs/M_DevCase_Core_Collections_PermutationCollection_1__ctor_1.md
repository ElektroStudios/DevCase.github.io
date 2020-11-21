# PermutationCollection(*T*) Constructor (IList(*T*), MetaCollectionType)
 

Initializes a new instance of the <a href="T_DevCase_Core_Collections_PermutationCollection_1">PermutationCollection(T)</a> class. 

 Create a permutation set from the provided list of values. 

 If type is <a href="T_DevCase_Core_Collections_MetaCollectionType">WithoutRepetition</a>, then values (`T`) must implement IComparable. 

 If T does not implement IComparable use a constructor with an explict IComparer.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections">DevCase.Core.Collections</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PermutationCollection(
	IList<T> values,
	MetaCollectionType type
)
```

**VB**<br />
``` VB
Public Sub New ( 
	values As IList(Of T),
	type As MetaCollectionType
)
```

**VB Usage**<br />
``` VB Usage
Dim values As IList(Of T)
Dim type As MetaCollectionType

Dim instance As New PermutationCollection(values, 
	type)
```

**C++**<br />
``` C++
public:
PermutationCollection(
	IList<T>^ values, 
	MetaCollectionType type
)
```

**F#**<br />
``` F#
new : 
        values : IList<'T> * 
        type : MetaCollectionType -> PermutationCollection
```


#### Parameters
&nbsp;<dl><dt>values</dt><dd>Type: System.Collections.Generic.IList(<a href="T_DevCase_Core_Collections_PermutationCollection_1">*T*</a>)<br />List of values to permute.</dd><dt>type</dt><dd>Type: <a href="T_DevCase_Core_Collections_MetaCollectionType">DevCase.Core.Collections.MetaCollectionType</a><br />The type of permutation set to calculate.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Collections_PermutationCollection_1">PermutationCollection(T) Class</a><br /><a href="Overload_DevCase_Core_Collections_PermutationCollection_1__ctor">PermutationCollection(T) Overload</a><br /><a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />