# CombinationCollection(*T*) Constructor (IList(*T*), Int32)
 

Initializes a new instance of the <a href="T_DevCase_Core_Collections_CombinationCollection_1">CombinationCollection(T)</a> class. 

 Create a combination set from the provided list of values. 

 The upper index is calculated as `values.Count`, the lower index is user specified. 

 Collection type defaults to <a href="T_DevCase_Core_Collections_MetaCollectionType">WithoutRepetition</a>

**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections">DevCase.Core.Collections</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CombinationCollection(
	IList<T> values,
	int lowerIndex
)
```

**VB**<br />
``` VB
Public Sub New ( 
	values As IList(Of T),
	lowerIndex As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim values As IList(Of T)
Dim lowerIndex As Integer

Dim instance As New CombinationCollection(values, 
	lowerIndex)
```

**C++**<br />
``` C++
public:
CombinationCollection(
	IList<T>^ values, 
	int lowerIndex
)
```

**F#**<br />
``` F#
new : 
        values : IList<'T> * 
        lowerIndex : int -> CombinationCollection
```


#### Parameters
&nbsp;<dl><dt>values</dt><dd>Type: System.Collections.Generic.IList(<a href="T_DevCase_Core_Collections_CombinationCollection_1">*T*</a>)<br />List of values to select combinations from.</dd><dt>lowerIndex</dt><dd>Type: System.Int32<br />The size of each combination set to return.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Collections_CombinationCollection_1">CombinationCollection(T) Class</a><br /><a href="Overload_DevCase_Core_Collections_CombinationCollection_1__ctor">CombinationCollection(T) Overload</a><br /><a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />