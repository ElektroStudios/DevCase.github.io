# FileSignature.Equals Method (FileSignature)
 

Determines whether the specified <a href="T_DevCase_Core_IO_FileSignature">FileSignature</a> is equal to this instance.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Advanced)]
public bool Equals(
	FileSignature signature
)
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Advanced)>
Public Function Equals ( 
	signature As FileSignature
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileSignature
Dim signature As FileSignature
Dim returnValue As Boolean

returnValue = instance.Equals(signature)
```

**C++**<br />
``` C++
public:
[EditorBrowsableAttribute(EditorBrowsableState::Advanced)]
bool Equals(
	FileSignature^ signature
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Advanced)>]
member Equals : 
        signature : FileSignature -> bool 

```


#### Parameters
&nbsp;<dl><dt>signature</dt><dd>Type: <a href="T_DevCase_Core_IO_FileSignature">DevCase.Core.IO.FileSignature</a><br />Another <a href="T_DevCase_Core_IO_FileSignature">FileSignature</a> to compare to.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified <a href="T_DevCase_Core_IO_FileSignature">FileSignature</a> is equal to this instance; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileSignature">FileSignature Class</a><br /><a href="Overload_DevCase_Core_IO_FileSignature_Equals">Equals Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />