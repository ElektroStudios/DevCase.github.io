# PermutationCollection(*T*) Constructor (IList(*T*))
 

Initializes a new instance of the <a href="T_DevCase_Core_Collections_PermutationCollection_1">PermutationCollection(T)</a> class. 

 Create a permutation set from the provided list of values. 

 The values `T` must implement IComparable. 

 If `T` does not implement IComparable use a constructor with an explict IComparer. 

 The repetition type defaults to <a href="T_DevCase_Core_Collections_MetaCollectionType">WithoutRepetition</a>

**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections">DevCase.Core.Collections</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PermutationCollection(
	IList<T> values
)
```

**VB**<br />
``` VB
Public Sub New ( 
	values As IList(Of T)
)
```

**VB Usage**<br />
``` VB Usage
Dim values As IList(Of T)

Dim instance As New PermutationCollection(values)
```

**C++**<br />
``` C++
public:
PermutationCollection(
	IList<T>^ values
)
```

**F#**<br />
``` F#
new : 
        values : IList<'T> -> PermutationCollection
```


#### Parameters
&nbsp;<dl><dt>values</dt><dd>Type: System.Collections.Generic.IList(<a href="T_DevCase_Core_Collections_PermutationCollection_1">*T*</a>)<br />List of values to permute.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Collections_PermutationCollection_1">PermutationCollection(T) Class</a><br /><a href="Overload_DevCase_Core_Collections_PermutationCollection_1__ctor">PermutationCollection(T) Overload</a><br /><a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />