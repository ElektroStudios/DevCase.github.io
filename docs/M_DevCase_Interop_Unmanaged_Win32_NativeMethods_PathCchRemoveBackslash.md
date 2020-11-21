# NativeMethods.PathCchRemoveBackslash Method 
 

Removes the trailing backslash from the end of a path string. 

 This function differs from PathRemoveBackslash in that it accepts paths with "\", "\?" and "\?\UNC" prefixes. 



**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult PathCchRemoveBackslash(
	StringBuilder buffer,
	uint bufferSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("KernelBase.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function PathCchRemoveBackslash ( 
	buffer As StringBuilder,
	bufferSize As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim buffer As StringBuilder
Dim bufferSize As UInteger
Dim returnValue As HResult

returnValue = NativeMethods.PathCchRemoveBackslash(buffer, 
	bufferSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"KernelBase.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult PathCchRemoveBackslash(
	StringBuilder^ buffer, 
	unsigned int bufferSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member PathCchRemoveBackslash : 
        buffer : StringBuilder * 
        bufferSize : uint32 -> HResult 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to the path string. When this function returns successfully, the string contains the path with any trailing backslash removed. 

 If no trailing backslash was found, the string is unchanged.</dd><dt>bufferSize</dt><dd>Type: System.UInt32<br />The size of the buffer pointed to by *buffer*, in characters.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />This function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if the function was successful, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_FALSE</a> if the string was a root path or if no backslash was found, or an error code otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchremovebackslash" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchremovebackslash</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />