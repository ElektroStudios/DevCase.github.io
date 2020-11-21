# FileDater.File Property 
 

Gets the file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual FileInfo File { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property File As FileInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileDater
Dim value As FileInfo

value = instance.File

```

**C++**<br />
``` C++
public:
virtual property FileInfo^ File {
	FileInfo^ get ();
}
```

**F#**<br />
``` F#
abstract File : FileInfo with get
override File : FileInfo with get
```


#### Property Value
Type: FileInfo<br />A FileInfo instance that contains the file info.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileDater">FileDater Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />