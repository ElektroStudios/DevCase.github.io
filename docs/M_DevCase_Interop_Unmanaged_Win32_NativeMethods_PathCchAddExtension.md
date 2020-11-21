# NativeMethods.PathCchAddExtension Method 
 

Adds a file name extension to a path string. 

 This function differs from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathAddExtension">PathAddExtension(StringBuilder, String)</a> in that it accepts paths with "\", "\?" and "\?\UNC" prefixes. 

 Note: This function should be used in place of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathAddExtension">PathAddExtension(StringBuilder, String)</a> to prevent the possibility of a buffer overrun.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult PathCchAddExtension(
	StringBuilder buffer,
	uint bufferSize,
	string ext
)
```

**VB**<br />
``` VB
<DllImportAttribute("KernelBase.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function PathCchAddExtension ( 
	buffer As StringBuilder,
	bufferSize As UInteger,
	ext As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim buffer As StringBuilder
Dim bufferSize As UInteger
Dim ext As String
Dim returnValue As HResult

returnValue = NativeMethods.PathCchAddExtension(buffer, 
	bufferSize, ext)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"KernelBase.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult PathCchAddExtension(
	StringBuilder^ buffer, 
	unsigned int bufferSize, 
	String^ ext
)
```

**F#**<br />
``` F#
[<DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member PathCchAddExtension : 
        buffer : StringBuilder * 
        bufferSize : uint32 * 
        ext : string -> HResult 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to the path string. 

 When this function returns successfully, the buffer contains the string with the appended extension. 

 This value should not be NULL.</dd><dt>bufferSize</dt><dd>Type: System.UInt32<br />The size of the buffer pointed to by *buffer*, in characters.</dd><dt>ext</dt><dd>Type: System.String<br />A pointer to the file name extension string. This string can be given either with or without a preceding period (".ext" or "ext").</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchaddextension" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchaddextension</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />