# NativeMethods.PathCchRemoveBackslashEx Method 
 

Removes the trailing backslash from the end of a path string. 

 This function differs from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchRemoveBackslash">PathCchRemoveBackslash(StringBuilder, UInt32)</a> in that it can return a pointer to the new end of the string and report the number of unused characters remaining in the buffer. 

 This function differs from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathRemoveBackslash">PathRemoveBackslash(StringBuilder)</a> in that it accepts paths with "\", "\?" and "\?\UNC" prefixes. 

 Note This function, or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchRemoveBackslash">PathCchRemoveBackslash(StringBuilder, UInt32)</a>, should be used in place of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathRemoveBackslash">PathRemoveBackslash(StringBuilder)</a> to prevent the possibility of a buffer overrun.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult PathCchRemoveBackslashEx(
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
Public Shared Function PathCchRemoveBackslashEx ( 
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

returnValue = NativeMethods.PathCchRemoveBackslashEx(buffer, 
	bufferSize, refEnd, refRemaining)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"KernelBase.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult PathCchRemoveBackslashEx(
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
static member PathCchRemoveBackslashEx : 
        buffer : StringBuilder * 
        bufferSize : uint32 * 
        refEnd : IntPtr byref * 
        refRemaining : uint32 byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to the path string. 

 When this function returns successfully, the string contains the path with any trailing backslash removed. 

 If no trailing backslash was found, the string is unchanged.</dd><dt>bufferSize</dt><dd>Type: System.UInt32<br />The size of the buffer pointed to by *buffer*, in characters.</dd><dt>refEnd</dt><dd>Type: System.IntPtr<br />A value that, when this function returns successfully, receives the address of a pointer to end of the new string. 

 If the string is a root path such as "C:", the pointer points to the backslash; otherwise the pointer points to the string's terminating null character.</dd><dt>refRemaining</dt><dd>Type: System.UInt32<br />A pointer to a value that, when this function returns successfully, receives the number of unused characters in the destination buffer, including the terminating null character. 

 If the string is a root path such as "C:", this count includes the backslash in that string.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />This function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if the function was successful, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_FALSE</a> if the string was a root path or if no backslash was found, or an error code otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchremovebackslashex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchremovebackslashex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />