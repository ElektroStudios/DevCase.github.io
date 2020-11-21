# DevListViewItemCollection.RemoveAtRange Method 
 

Removes a collection of items from the collection.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevListViewData">DevCase.Controls.DevListViewData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void RemoveAtRange(
	int[] indices
)
```

**VB**<br />
``` VB
Public Overridable Sub RemoveAtRange ( 
	indices As Integer()
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListViewItemCollection
Dim indices As Integer()

instance.RemoveAtRange(indices)
```

**C++**<br />
``` C++
public:
virtual void RemoveAtRange(
	array<int>^ indices
)
```

**F#**<br />
``` F#
abstract RemoveAtRange : 
        indices : int[] -> unit 
override RemoveAtRange : 
        indices : int[] -> unit 
```


#### Parameters
&nbsp;<dl><dt>indices</dt><dd>Type: System.Int32[]<br />An array with the indices of the items to remove from the collection.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListViewData_DevListViewItemCollection">DevListViewItemCollection Class</a><br /><a href="N_DevCase_Controls_DevListViewData">DevCase.Controls.DevListViewData Namespace</a><br />