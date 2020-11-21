# DevFileSystemWatcher Constructor (String, String)
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_DevFileSystemWatcher">DevFileSystemWatcher</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public DevFileSystemWatcher(
	string path,
	string filter
)
```

**VB**<br />
``` VB
Public Sub New ( 
	path As String,
	filter As String
)
```

**VB Usage**<br />
``` VB Usage
Dim path As String
Dim filter As String

Dim instance As New DevFileSystemWatcher(path, filter)
```

**C++**<br />
``` C++
public:
DevFileSystemWatcher(
	String^ path, 
	String^ filter
)
```

**F#**<br />
``` F#
new : 
        path : string * 
        filter : string -> DevFileSystemWatcher
```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.String<br />The directory to monitor, in standard or Universal Naming Convention (UNC) notation.</dd><dt>filter</dt><dd>Type: System.String<br />The type of files to watch. For example, "*.txt" watches for changes to all text files.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_DevFileSystemWatcher">DevFileSystemWatcher Class</a><br /><a href="Overload_DevCase_Core_IO_DevFileSystemWatcher__ctor">DevFileSystemWatcher Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />