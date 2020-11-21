# DebugUtil.MiniDumpToFile Method (Process, FileInfo, MiniDumpType)
 

Dumps debug information from a process to a local file. 

 With this, you can dump the entire allocated memory by a external process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void MiniDumpToFile(
	Process p,
	FileInfo fileToDump,
	MiniDumpType miniDumpType
)
```

**VB**<br />
``` VB
Public Shared Sub MiniDumpToFile ( 
	p As Process,
	fileToDump As FileInfo,
	miniDumpType As MiniDumpType
)
```

**VB Usage**<br />
``` VB Usage
Dim p As Process
Dim fileToDump As FileInfo
Dim miniDumpType As MiniDumpTypeDebugUtil.MiniDumpToFile(p, fileToDump, 
	miniDumpType)
```

**C++**<br />
``` C++
public:
static void MiniDumpToFile(
	Process^ p, 
	FileInfo^ fileToDump, 
	MiniDumpType miniDumpType
)
```

**F#**<br />
``` F#
static member MiniDumpToFile : 
        p : Process * 
        fileToDump : FileInfo * 
        miniDumpType : MiniDumpType -> unit 

```


#### Parameters
&nbsp;<dl><dt>p</dt><dd>Type: System.Diagnostics.Process<br />The target Process.</dd><dt>fileToDump</dt><dd>Type: System.IO.FileInfo<br />The FileInfo where to create the .dmp file.</dd><dt>miniDumpType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MiniDumpType">DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType</a><br />The type of MiniDump information to be generated.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="Overload_DevCase_Core_Diagnostics_Tools_DebugUtil_MiniDumpToFile">MiniDumpToFile Overload</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />