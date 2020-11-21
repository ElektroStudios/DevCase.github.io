# AestheticList(*T*) Constructor (IEnumerable(*T*))
 

Initializes a new instance of the <a href="T_DevCase_Core_Design_AestheticList_1">AestheticList(T)</a> class that contains elements copied from the specified collection and has sufficient capacity to accommodate the number of elements copied.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public AestheticList(
	IEnumerable<T> collection
)
```

**VB**<br />
``` VB
Public Sub New ( 
	collection As IEnumerable(Of T)
)
```

**VB Usage**<br />
``` VB Usage
Dim collection As IEnumerable(Of T)

Dim instance As New AestheticList(collection)
```

**C++**<br />
``` C++
public:
AestheticList(
	IEnumerable<T>^ collection
)
```

**F#**<br />
``` F#
new : 
        collection : IEnumerable<'T> -> AestheticList
```


#### Parameters
&nbsp;<dl><dt>collection</dt><dd>Type: System.Collections.Generic.IEnumerable(<a href="T_DevCase_Core_Design_AestheticList_1">*T*</a>)<br />The collection whose elements are copied to the new list.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Design_AestheticList_1">AestheticList(T) Class</a><br /><a href="Overload_DevCase_Core_Design_AestheticList_1__ctor">AestheticList(T) Overload</a><br /><a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />