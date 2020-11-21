# NativeMethods.GetCurrentThreadId Method 
 

Gets the thread identifier of the calling thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static uint GetCurrentThreadId()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function GetCurrentThreadId As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UInteger

returnValue = NativeMethods.GetCurrentThreadId()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static unsigned int GetCurrentThreadId()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member GetCurrentThreadId : unit -> uint32 

```


#### Return Value
Type: UInt32<br />The thread identifier of the calling thread.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms683183%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms683183%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />