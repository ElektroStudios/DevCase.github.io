# NativeMethods.PathCchAddBackslashEx Method 
 

Adds a backslash to the end of a string to create the correct syntax for a path. If the source path already has a trailing backslash, no backslash will be added. 

 This function differs from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchAddBackslash">PathCchAddBackslash(StringBuilder, UInt32)</a> in that it can return a pointer to the new end of the string and report the number of unused characters remaining in the buffer. 

 This function differs from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathAddBackslash">PathAddBackslash(StringBuilder)</a> in that it accepts paths with "\", "\?" and "\?\UNC" prefixes. 

 Note: This function, or PathCchAddBackslashEx(StringBuilder, UInt32, IntPtr, UInt32), should be used in place of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathAddBackslash">PathAddBackslash(StringBuilder)</a> to prevent the possibility of a buffer overrun.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult PathCchAddBackslashEx(
	StringBuilder buffer,
	uint bufferSize,
	out IntPtr refEnd,
	out uint refRemaining
)
```

**VB**<br />
``` VB
<DllImportAttribute("KernelBase.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function PathCchAddBackslashEx ( 
	buffer As StringBuilder,
	bufferSize As UInteger,
	<OutAttribute> ByRef refEnd As IntPtr,
	<OutAttribute> ByRef refRemaining As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim buffer As StringBuilder
Dim bufferSize As UInteger
Dim refEnd As IntPtr
Dim refRemaining As UInteger
Dim returnValue As HResult

returnValue = NativeMethods.PathCchAddBackslashEx(buffer, 
	bufferSize, refEnd, refRemaining)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"KernelBase.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult PathCchAddBackslashEx(
	StringBuilder^ buffer, 
	unsigned int bufferSize, 
	[OutAttribute] IntPtr% refEnd, 
	[OutAttribute] unsigned int% refRemaining
)
```

**F#**<br />
``` F#
[<DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member PathCchAddBackslashEx : 
        buffer : StringBuilder * 
        bufferSize : uint32 * 
        refEnd : IntPtr byref * 
        refRemaining : uint32 byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to the path string. 

 When this function returns successfully, the buffer contains the string with the appended backslash. 

 This value should not be NULL.</dd><dt>bufferSize</dt><dd>Type: System.UInt32<br />The size of the buffer pointed to by *buffer*, in characters.</dd><dt>refEnd</dt><dd>Type: System.IntPtr<br />A value that, when this function returns successfully, receives the address of a pointer to the terminating null character at the end of the string.</dd><dt>refRemaining</dt><dd>Type: System.UInt32<br />A pointer to a value that, when this function returns successfully, is set to the number of unused characters in the destination buffer, including the terminating null character.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />This function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if the function was successful, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_FALSE</a> if the path string already ends in a backslash, or an error code otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchaddbackslashex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchaddbackslashex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />