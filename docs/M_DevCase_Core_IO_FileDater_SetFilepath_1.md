# FileDater.SetFilepath Method (String)
 

Causes this <a href="T_DevCase_Core_IO_FileDater">FileDater</a> instance to assign a new location for the current file. 

 This could be useful if the saved dates should be restored in a file that has changed its name/ubication. 

 Note: Calling this method does not cause the removal of any saved date.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void SetFilepath(
	string filepath
)
```

**VB**<br />
``` VB
Public Overridable Sub SetFilepath ( 
	filepath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileDater
Dim filepath As String

instance.SetFilepath(filepath)
```

**C++**<br />
``` C++
public:
virtual void SetFilepath(
	String^ filepath
)
```

**F#**<br />
``` F#
abstract SetFilepath : 
        filepath : string -> unit 
override SetFilepath : 
        filepath : string -> unit 
```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The file path.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileDater">FileDater Class</a><br /><a href="Overload_DevCase_Core_IO_FileDater_SetFilepath">SetFilepath Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />