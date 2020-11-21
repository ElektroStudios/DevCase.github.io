# NativeMethods.PathCchStripPrefix Method 
 

Removes the "\?" prefix, if present, from a file path.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult PathCchStripPrefix(
	StringBuilder path,
	uint pathSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("KernelBase.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function PathCchStripPrefix ( 
	path As StringBuilder,
	pathSize As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim path As StringBuilder
Dim pathSize As UInteger
Dim returnValue As HResult

returnValue = NativeMethods.PathCchStripPrefix(path, 
	pathSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"KernelBase.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult PathCchStripPrefix(
	StringBuilder^ path, 
	unsigned int pathSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member PathCchStripPrefix : 
        path : StringBuilder * 
        pathSize : uint32 -> HResult 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.Text.StringBuilder<br />A pointer to the path string. 

 When this function returns successfully, the same path string will have had the prefix removed, if the prefix was present. 

 If no prefix was present, the string will be unchanged.</dd><dt>pathSize</dt><dd>Type: System.UInt32<br />The size of the buffer pointed to by *path*, in characters.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if the prefix was removed, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_FALSE</a> if the path did not have a prefix to remove, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> failure code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchstripprefix" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchstripprefix</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />