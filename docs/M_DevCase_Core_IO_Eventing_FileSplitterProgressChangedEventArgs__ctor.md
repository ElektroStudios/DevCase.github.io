# FileSplitterProgressChangedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_Eventing_FileSplitterProgressChangedEventArgs">FileSplitterProgressChangedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FileSplitterProgressChangedEventArgs(
	double totalProgress,
	double chunkProgress,
	long chunksToCreateOrMerge,
	long chunksCreatedOrMerged
)
```

**VB**<br />
``` VB
Public Sub New ( 
	totalProgress As Double,
	chunkProgress As Double,
	chunksToCreateOrMerge As Long,
	chunksCreatedOrMerged As Long
)
```

**VB Usage**<br />
``` VB Usage
Dim totalProgress As Double
Dim chunkProgress As Double
Dim chunksToCreateOrMerge As Long
Dim chunksCreatedOrMerged As Long

Dim instance As New FileSplitterProgressChangedEventArgs(totalProgress, 
	chunkProgress, chunksToCreateOrMerge, 
	chunksCreatedOrMerged)
```

**C++**<br />
``` C++
public:
FileSplitterProgressChangedEventArgs(
	double totalProgress, 
	double chunkProgress, 
	long long chunksToCreateOrMerge, 
	long long chunksCreatedOrMerged
)
```

**F#**<br />
``` F#
new : 
        totalProgress : float * 
        chunkProgress : float * 
        chunksToCreateOrMerge : int64 * 
        chunksCreatedOrMerged : int64 -> FileSplitterProgressChangedEventArgs
```


#### Parameters
&nbsp;<dl><dt>totalProgress</dt><dd>Type: System.Double<br />The total progress value.</dd><dt>chunkProgress</dt><dd>Type: System.Double<br />The current chunk progress value.</dd><dt>chunksToCreateOrMerge</dt><dd>Type: System.Int64<br />The amount of chunks to create or merge.</dd><dt>chunksCreatedOrMerged</dt><dd>Type: System.Int64<br />The amount of created or merged chunks.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Eventing_FileSplitterProgressChangedEventArgs">FileSplitterProgressChangedEventArgs Class</a><br /><a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing Namespace</a><br />