# FileCopyProgressChangedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_Eventing_FileCopyProgressChangedEventArgs">FileCopyProgressChangedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FileCopyProgressChangedEventArgs(
	long filesize,
	long bytesRead
)
```

**VB**<br />
``` VB
Public Sub New ( 
	filesize As Long,
	bytesRead As Long
)
```

**VB Usage**<br />
``` VB Usage
Dim filesize As Long
Dim bytesRead As Long

Dim instance As New FileCopyProgressChangedEventArgs(filesize, 
	bytesRead)
```

**C++**<br />
``` C++
public:
FileCopyProgressChangedEventArgs(
	long long filesize, 
	long long bytesRead
)
```

**F#**<br />
``` F#
new : 
        filesize : int64 * 
        bytesRead : int64 -> FileCopyProgressChangedEventArgs
```


#### Parameters
&nbsp;<dl><dt>filesize</dt><dd>Type: System.Int64<br />The size, in bytes, of the source file being copied.</dd><dt>bytesRead</dt><dd>Type: System.Int64<br />The total amound of copied bytes.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Eventing_FileCopyProgressChangedEventArgs">FileCopyProgressChangedEventArgs Class</a><br /><a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing Namespace</a><br />