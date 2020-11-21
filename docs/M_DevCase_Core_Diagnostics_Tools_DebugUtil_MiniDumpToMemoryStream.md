# DebugUtil.MiniDumpToMemoryStream Method 
 

Dumps debug information from a process to a MemoryStream. 

 With this, you can dump the entire allocated memory by a external process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static MemoryStream MiniDumpToMemoryStream(
	Process p,
	MiniDumpType miniDumpType
)
```

**VB**<br />
``` VB
Public Shared Function MiniDumpToMemoryStream ( 
	p As Process,
	miniDumpType As MiniDumpType
) As MemoryStream
```

**VB Usage**<br />
``` VB Usage
Dim p As Process
Dim miniDumpType As MiniDumpType
Dim returnValue As MemoryStream

returnValue = DebugUtil.MiniDumpToMemoryStream(p, 
	miniDumpType)
```

**C++**<br />
``` C++
public:
static MemoryStream^ MiniDumpToMemoryStream(
	Process^ p, 
	MiniDumpType miniDumpType
)
```

**F#**<br />
``` F#
static member MiniDumpToMemoryStream : 
        p : Process * 
        miniDumpType : MiniDumpType -> MemoryStream 

```


#### Parameters
&nbsp;<dl><dt>p</dt><dd>Type: System.Diagnostics.Process<br />The target Process.</dd><dt>miniDumpType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MiniDumpType">DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType</a><br />The type of MiniDump information to be generated.</dd></dl>

#### Return Value
Type: MemoryStream<br />A MemoryStream containing the raw data of the dump file.

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />