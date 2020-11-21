# NativeMethods.PathCchAddBackslash Method 
 

Adds a backslash to the end of a string to create the correct syntax for a path. If the source path already has a trailing backslash, no backslash will be added. 

 This function differs from PathCchAddBackslash(StringBuilder, UInt32) in that you are restricted to a final path of length MAX_PATH. 

 This function differs from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathAddBackslash">PathAddBackslash(StringBuilder)</a> in that it accepts paths with "\", "\?" and "\?\UNC" prefixes. 

 Note: This function, or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchAddBackslashEx">PathCchAddBackslashEx(StringBuilder, UInt32, IntPtr, UInt32)</a>, should be used in place of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathAddBackslash">PathAddBackslash(StringBuilder)</a> to prevent the possibility of a buffer overrun.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult PathCchAddBackslash(
	StringBuilder buffer,
	uint bufferSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("KernelBase.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function PathCchAddBackslash ( 
	buffer As StringBuilder,
	bufferSize As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim buffer As StringBuilder
Dim bufferSize As UInteger
Dim returnValue As HResult

returnValue = NativeMethods.PathCchAddBackslash(buffer, 
	bufferSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"KernelBase.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult PathCchAddBackslash(
	StringBuilder^ buffer, 
	unsigned int bufferSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member PathCchAddBackslash : 
        buffer : StringBuilder * 
        bufferSize : uint32 -> HResult 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to the path string. 

 When this function returns successfully, the buffer contains the string with the appended backslash. 

 This value should not be NULL.</dd><dt>bufferSize</dt><dd>Type: System.UInt32<br />The size of the buffer pointed to by *buffer*, in characters.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />This function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if the function was successful, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_FALSE</a> if the path string already ends in a backslash, or an error code otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchaddbackslash" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchaddbackslash</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />