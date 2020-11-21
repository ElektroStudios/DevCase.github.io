# FileSignature.Equals Method (Object)
 

Determines whether the specified Object is equal to this instance.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Advanced)]
public override bool Equals(
	Object obj
)
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Advanced)>
Public Overrides Function Equals ( 
	obj As Object
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileSignature
Dim obj As Object
Dim returnValue As Boolean

returnValue = instance.Equals(obj)
```

**C++**<br />
``` C++
public:
[EditorBrowsableAttribute(EditorBrowsableState::Advanced)]
virtual bool Equals(
	Object^ obj
) override
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Advanced)>]
abstract Equals : 
        obj : Object -> bool 
[<EditorBrowsableAttribute(EditorBrowsableState.Advanced)>]
override Equals : 
        obj : Object -> bool 
```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: System.Object<br />Another object to compare to.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified Object is equal to this instance; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileSignature">FileSignature Class</a><br /><a href="Overload_DevCase_Core_IO_FileSignature_Equals">Equals Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />