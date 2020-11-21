# IAssemblyCache.QueryAssemblyInfo Method 
 

Gets the requested data about the specified assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult QueryAssemblyInfo(
	QueryAssemblyInfoFlags flags,
	string assemblyName,
	ref AssemblyInfo refAssemblyInfo
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function QueryAssemblyInfo ( 
	flags As QueryAssemblyInfoFlags,
	assemblyName As String,
	ByRef refAssemblyInfo As AssemblyInfo
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAssemblyCache
Dim flags As QueryAssemblyInfoFlags
Dim assemblyName As String
Dim refAssemblyInfo As AssemblyInfo
Dim returnValue As HResult

returnValue = instance.QueryAssemblyInfo(flags, 
	assemblyName, refAssemblyInfo)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult QueryAssemblyInfo(
	QueryAssemblyInfoFlags flags, 
	String^ assemblyName, 
	AssemblyInfo% refAssemblyInfo
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract QueryAssemblyInfo : 
        flags : QueryAssemblyInfoFlags * 
        assemblyName : string * 
        refAssemblyInfo : AssemblyInfo byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_QueryAssemblyInfoFlags">DevCase.Interop.Unmanaged.Win32.Enums.QueryAssemblyInfoFlags</a><br />Flags defined in `Fusion.idl`. The following values are supported: 

 QUERYASMINFO_FLAG_VALIDATE (0x00000001) 

 QUERYASMINFO_FLAG_GETSIZE (0x00000002)</dd><dt>assemblyName</dt><dd>Type: System.String<br />The name of the assembly for which data will be retrieved.</dd><dt>refAssemblyInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_AssemblyInfo">DevCase.Interop.Unmanaged.Win32.Structures.AssemblyInfo</a><br />An <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_AssemblyInfo">AssemblyInfo</a> structure that contains data about the assembly.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />An IntPtr that points to an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a>.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAssemblyCache">IAssemblyCache Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />