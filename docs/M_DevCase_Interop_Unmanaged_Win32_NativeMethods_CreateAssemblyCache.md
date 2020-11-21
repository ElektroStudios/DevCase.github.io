# NativeMethods.CreateAssemblyCache Method 
 

Gets a pointer to a new <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAssemblyCache">IAssemblyCache</a> instance that represents the global assembly cache.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Fusion.dll")]
public static HResult CreateAssemblyCache(
	ref IAssemblyCache refAsmCache,
	int reserved
)
```

**VB**<br />
``` VB
<DllImportAttribute("Fusion.dll">]
Public Shared Function CreateAssemblyCache ( 
	ByRef refAsmCache As IAssemblyCache,
	reserved As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim refAsmCache As IAssemblyCache
Dim reserved As Integer
Dim returnValue As HResult

returnValue = NativeMethods.CreateAssemblyCache(refAsmCache, 
	reserved)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Fusion.dll")]
static HResult CreateAssemblyCache(
	IAssemblyCache^% refAsmCache, 
	int reserved
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Fusion.dll")>]
static member CreateAssemblyCache : 
        refAsmCache : IAssemblyCache byref * 
        reserved : int -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refAsmCache</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAssemblyCache">DevCase.Interop.Unmanaged.Win32.Interfaces.IAssemblyCache</a><br />The returned <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAssemblyCache">IAssemblyCache</a> pointer.</dd><dt>reserved</dt><dd>Type: System.Int32<br />Reserved for future extensibility. 

*reserved* must be Zero.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />An IntPtr that points to an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a>.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/ms230575%28v=vs.110%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/ms230575%28v=vs.110%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />