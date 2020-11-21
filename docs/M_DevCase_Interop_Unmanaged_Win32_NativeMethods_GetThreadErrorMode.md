# NativeMethods.GetThreadErrorMode Method 
 

Retrieves the error mode for the current thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static ThreadErrorMode GetThreadErrorMode()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function GetThreadErrorMode As ThreadErrorMode
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As ThreadErrorMode

returnValue = NativeMethods.GetThreadErrorMode()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static ThreadErrorMode GetThreadErrorMode()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member GetThreadErrorMode : unit -> ThreadErrorMode 

```


#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadErrorMode">ThreadErrorMode</a><br />The previous state of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadErrorMode">ThreadErrorMode</a> of the current thread.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd553629%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd553629%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />