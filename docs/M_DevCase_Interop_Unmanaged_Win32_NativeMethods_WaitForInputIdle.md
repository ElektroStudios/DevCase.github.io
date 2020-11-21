# NativeMethods.WaitForInputIdle Method 
 

Waits until the specified process has finished processing its initial input and is waiting for user input with no input pending, or until the time-out interval has elapsed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, SetLastError = true)]
public static uint WaitForInputIdle(
	IntPtr hProcess,
	uint milliseconds
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, SetLastError := true>]
Public Shared Function WaitForInputIdle ( 
	hProcess As IntPtr,
	milliseconds As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim milliseconds As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.WaitForInputIdle(hProcess, 
	milliseconds)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, SetLastError = true)]
static unsigned int WaitForInputIdle(
	IntPtr hProcess, 
	unsigned int milliseconds
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, SetLastError = true)>]
static member WaitForInputIdle : 
        hProcess : IntPtr * 
        milliseconds : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 If this process is a console application or does not have a message queue, WaitForInputIdle(IntPtr, UInt32) returns immediately.</dd><dt>milliseconds</dt><dd>Type: System.UInt32<br />The time-out interval, in milliseconds. 

 If *milliseconds* is INFINITE, the function does not return until the process is idle.</dd></dl>

#### Return Value
Type: UInt32<br />The following table shows the possible return values for this function: 

 0: The wait was satisfied successfully. 

 WAIT_TIMEOUT: The wait was terminated because the time-out interval elapsed 

 WAIT_FAILED: An error occurred. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-waitforinputidle" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-waitforinputidle</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />