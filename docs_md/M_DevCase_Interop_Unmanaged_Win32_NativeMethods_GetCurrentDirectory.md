# NativeMethods.GetCurrentDirectory Method 
 

Retrieves the current directory for the current process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint GetCurrentDirectory(
	uint bufferLength,
	StringBuilder buffer
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetCurrentDirectory ( 
	bufferLength As UInteger,
	buffer As StringBuilder
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim bufferLength As UInteger
Dim buffer As StringBuilder
Dim returnValue As UInteger

returnValue = NativeMethods.GetCurrentDirectory(bufferLength, 
	buffer)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int GetCurrentDirectory(
	unsigned int bufferLength, 
	StringBuilder^ buffer
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetCurrentDirectory : 
        bufferLength : uint32 * 
        buffer : StringBuilder -> uint32 

```


#### Parameters
&nbsp;<dl><dt>bufferLength</dt><dd>Type: System.UInt32<br />The length of the buffer for the current directory string, in TCHARs. 

 The buffer length must include room for a terminating null character.</dd><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to the buffer that receives the current directory string. This null-terminated string specifies the absolute path to the current directory. 

 To determine the required buffer size, set this parameter to NULL and the *bufferLength* parameter to 0.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value specifies the number of characters that are written to the buffer, not including the terminating null character. 

 If the function fails, the return value is zero. 

 If the buffer that is pointed to by lpBuffer is not large enough, the return value specifies the required size of the buffer, in characters, including the null-terminating character.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getcurrentdirectory" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getcurrentdirectory</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />