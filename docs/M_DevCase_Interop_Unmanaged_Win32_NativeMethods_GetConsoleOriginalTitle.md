# NativeMethods.GetConsoleOriginalTitle Method 
 

Retrieves the original title for the current console window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint GetConsoleOriginalTitle(
	StringBuilder buffer,
	uint bufferSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetConsoleOriginalTitle ( 
	buffer As StringBuilder,
	bufferSize As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim buffer As StringBuilder
Dim bufferSize As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetConsoleOriginalTitle(buffer, 
	bufferSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int GetConsoleOriginalTitle(
	StringBuilder^ buffer, 
	unsigned int bufferSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetConsoleOriginalTitle : 
        buffer : StringBuilder * 
        bufferSize : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that receives a null-terminated string containing the original title.</dd><dt>bufferSize</dt><dd>Type: System.UInt32<br />The size of *buffer*, in characters.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the length of the string copied to the buffer, in characters. 

 If the buffer is not large enough to store the title, the return value is zero and GetLastError returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>. 

 If the function fails, the return value is zero and GetLastError returns the error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/getconsoleoriginaltitle" target="_blank">https://docs.microsoft.com/en-us/windows/console/getconsoleoriginaltitle</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />