# FileSplitterProgressChangedEventArgs.ChunkProgress Property 
 

Gets the current chunk progress value. 

 (From 0 to 100)

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public double ChunkProgress { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property ChunkProgress As Double
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileSplitterProgressChangedEventArgs
Dim value As Double

value = instance.ChunkProgress

```

**C++**<br />
``` C++
public:
property double ChunkProgress {
	double get ();
}
```

**F#**<br />
``` F#
member ChunkProgress : float with get

```


#### Property Value
Type: Double<br />The current chunk progress value.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Eventing_FileSplitterProgressChangedEventArgs">FileSplitterProgressChangedEventArgs Class</a><br /><a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing Namespace</a><br />