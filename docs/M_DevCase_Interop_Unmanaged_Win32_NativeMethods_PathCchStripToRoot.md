# NativeMethods.PathCchStripToRoot Method 
 

Removes all file and directory elements in a path except for the root information. 

 This function differs from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathStripToRoot">PathStripToRoot(StringBuilder)</a> in that it accepts paths with "\", "\?" and "\?\UNC" prefixes. 

 Note: This function should be used in place of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathStripToRoot">PathStripToRoot(StringBuilder)</a> to prevent the possibility of a buffer overrun.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult PathCchStripToRoot(
	StringBuilder buffer,
	uint bufferSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("KernelBase.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function PathCchStripToRoot ( 
	buffer As StringBuilder,
	bufferSize As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim buffer As StringBuilder
Dim bufferSize As UInteger
Dim returnValue As HResult

returnValue = NativeMethods.PathCchStripToRoot(buffer, 
	bufferSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"KernelBase.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult PathCchStripToRoot(
	StringBuilder^ buffer, 
	unsigned int bufferSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member PathCchStripToRoot : 
        buffer : StringBuilder * 
        bufferSize : uint32 -> HResult 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to the path string. 

 When this function returns successfully, this string contains only the root information taken from that path.</dd><dt>bufferSize</dt><dd>Type: System.UInt32<br />The size of the buffer pointed to by *buffer*, in characters.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />This function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if the path was truncated, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_FALSE</a> if the path was already just a root, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> failure code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchstriptoroot" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchstriptoroot</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />