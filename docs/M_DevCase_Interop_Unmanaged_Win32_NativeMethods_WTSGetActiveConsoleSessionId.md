# NativeMethods.WTSGetActiveConsoleSessionId Method 
 

Retrieves the session identifier of the console session. 

 The console session is the session that is currently attached to the physical console. 

 Note that it is not necessary that Remote Desktop Services be running for this function to succeed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static uint WTSGetActiveConsoleSessionId()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function WTSGetActiveConsoleSessionId As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UInteger

returnValue = NativeMethods.WTSGetActiveConsoleSessionId()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static unsigned int WTSGetActiveConsoleSessionId()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member WTSGetActiveConsoleSessionId : unit -> uint32 

```


#### Return Value
Type: UInt32<br />The session identifier of the session that is attached to the physical console. 

 If there is no session attached to the physical console, (for example, if the physical console session is in the process of being attached or detached), this function returns UInt32 (`0xFFFFFFFF`).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-wtsgetactiveconsolesessionid" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-wtsgetactiveconsolesessionid</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />