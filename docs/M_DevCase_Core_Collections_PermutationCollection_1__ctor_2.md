# PermutationCollection(*T*) Constructor (IList(*T*), IComparer(*T*))
 

Initializes a new instance of the <a href="T_DevCase_Core_Collections_PermutationCollection_1">PermutationCollection(T)</a> class. 

 Create a permutation set from the provided list of values. 

 The values will be compared using the supplied IComparer. 

 The repetition type defaults to <a href="T_DevCase_Core_Collections_MetaCollectionType">WithoutRepetition</a>

**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections">DevCase.Core.Collections</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PermutationCollection(
	IList<T> values,
	IComparer<T> comparer
)
```

**VB**<br />
``` VB
Public Sub New ( 
	values As IList(Of T),
	comparer As IComparer(Of T)
)
```

**VB Usage**<br />
``` VB Usage
Dim values As IList(Of T)
Dim comparer As IComparer(Of T)

Dim instance As New PermutationCollection(values, 
	comparer)
```

**C++**<br />
``` C++
public:
PermutationCollection(
	IList<T>^ values, 
	IComparer<T>^ comparer
)
```

**F#**<br />
``` F#
new : 
        values : IList<'T> * 
        comparer : IComparer<'T> -> PermutationCollection
```


#### Parameters
&nbsp;<dl><dt>values</dt><dd>Type: System.Collections.Generic.IList(<a href="T_DevCase_Core_Collections_PermutationCollection_1">*T*</a>)<br />List of values to permute.</dd><dt>comparer</dt><dd>Type: System.Collections.Generic.IComparer(<a href="T_DevCase_Core_Collections_PermutationCollection_1">*T*</a>)<br />Comparer used for defining the lexigraphic order.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Collections_PermutationCollection_1">PermutationCollection(T) Class</a><br /><a href="Overload_DevCase_Core_Collections_PermutationCollection_1__ctor">PermutationCollection(T) Overload</a><br /><a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />