# FileSplitterProgressChangedEventArgs.ChunksCreatedOrMerged Property 
 

Gets the amount of created or merged chunks.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public long ChunksCreatedOrMerged { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property ChunksCreatedOrMerged As Long
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileSplitterProgressChangedEventArgs
Dim value As Long

value = instance.ChunksCreatedOrMerged

```

**C++**<br />
``` C++
public:
property long long ChunksCreatedOrMerged {
	long long get ();
}
```

**F#**<br />
``` F#
member ChunksCreatedOrMerged : int64 with get

```


#### Property Value
Type: Int64<br />The amount of created or merged chunks.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Eventing_FileSplitterProgressChangedEventArgs">FileSplitterProgressChangedEventArgs Class</a><br /><a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing Namespace</a><br />