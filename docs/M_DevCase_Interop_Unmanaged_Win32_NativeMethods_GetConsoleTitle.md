# NativeMethods.GetConsoleTitle Method 
 

Retrieves the title for the current console window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint GetConsoleTitle(
	StringBuilder buffer,
	uint bufferSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetConsoleTitle ( 
	buffer As StringBuilder,
	bufferSize As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim buffer As StringBuilder
Dim bufferSize As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetConsoleTitle(buffer, 
	bufferSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int GetConsoleTitle(
	StringBuilder^ buffer, 
	unsigned int bufferSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetConsoleTitle : 
        buffer : StringBuilder * 
        bufferSize : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that receives a null-terminated string containing the title. 

 If the buffer is too small to store the title, the function stores as many characters of the title as will fit in the buffer, ending with a null terminator.</dd><dt>bufferSize</dt><dd>Type: System.UInt32<br />The size of the buffer pointed to by the *buffer* parameter, in characters.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the length of the console window's title, in characters. 

 If the function fails, the return value is zero and GetLastError returns the error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/getconsoletitle" target="_blank">https://docs.microsoft.com/en-us/windows/console/getconsoletitle</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />