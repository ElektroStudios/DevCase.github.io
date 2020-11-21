# FileDater.SetFilepath Method (FileInfo)
 

Causes this <a href="T_DevCase_Core_IO_FileDater">FileDater</a> instance to assign a new location for the current file. 

 This could be useful if the saved dates should be restored in a file that has changed its name/ubication. 

 Note: Calling this method does not cause the removal of any saved date.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void SetFilepath(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Overridable Sub SetFilepath ( 
	file As FileInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileDater
Dim file As FileInfo

instance.SetFilepath(file)
```

**C++**<br />
``` C++
public:
virtual void SetFilepath(
	FileInfo^ file
)
```

**F#**<br />
``` F#
abstract SetFilepath : 
        file : FileInfo -> unit 
override SetFilepath : 
        file : FileInfo -> unit 
```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />A FileInfo instance that contains the file info.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileDater">FileDater Class</a><br /><a href="Overload_DevCase_Core_IO_FileDater_SetFilepath">SetFilepath Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />