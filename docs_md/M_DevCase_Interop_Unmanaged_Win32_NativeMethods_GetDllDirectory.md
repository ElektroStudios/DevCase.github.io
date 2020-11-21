# NativeMethods.GetDllDirectory Method (UInt32, IntPtr)
 

Retrieves the application-specific portion of the search path used to locate DLLs for the application.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static uint GetDllDirectory(
	uint bufferLength,
	IntPtr buffer
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Unicode, SetLastError := true>]
Public Shared Function GetDllDirectory ( 
	bufferLength As UInteger,
	buffer As IntPtr
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim bufferLength As UInteger
Dim buffer As IntPtr
Dim returnValue As UInteger

returnValue = NativeMethods.GetDllDirectory(bufferLength, 
	buffer)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Unicode, SetLastError = true)]
static unsigned int GetDllDirectory(
	unsigned int bufferLength, 
	IntPtr buffer
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)>]
static member GetDllDirectory : 
        bufferLength : uint32 * 
        buffer : IntPtr -> uint32 

```


#### Parameters
&nbsp;<dl><dt>bufferLength</dt><dd>Type: System.UInt32<br />The size of the output buffer, in characters.</dd><dt>buffer</dt><dd>Type: System.IntPtr<br />A pointer to a buffer that receives the application-specific portion of the search path.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the length of the string copied to *buffer*, in characters, not including the terminating null character. 

 If the return value is greater than *bufferLength*, it specifies the size of the buffer required for the path. 

 If the function fails, the return value is zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/ms683186(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/ms683186(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetDllDirectory">GetDllDirectory Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />