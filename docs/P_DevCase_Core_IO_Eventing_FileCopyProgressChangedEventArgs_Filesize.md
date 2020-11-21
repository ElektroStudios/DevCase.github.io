# FileCopyProgressChangedEventArgs.Filesize Property 
 

Gets the size, in bytes, of the source file being copied.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public long Filesize { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Filesize As Long
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileCopyProgressChangedEventArgs
Dim value As Long

value = instance.Filesize

```

**C++**<br />
``` C++
public:
property long long Filesize {
	long long get ();
}
```

**F#**<br />
``` F#
member Filesize : int64 with get

```


#### Property Value
Type: Int64<br />The size, in bytes, of the source file being copied.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Eventing_FileCopyProgressChangedEventArgs">FileCopyProgressChangedEventArgs Class</a><br /><a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing Namespace</a><br />