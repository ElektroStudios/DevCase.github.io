# NativeMethods.IsWow64Message Method 
 

Determines whether the last message read from the current thread's queue originated from a WOW64 process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool IsWow64Message()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function IsWow64Message As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = NativeMethods.IsWow64Message()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool IsWow64Message()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member IsWow64Message : unit -> bool 

```


#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the last message read from the current thread's queue originated from a WOW64 process, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/ms684136(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/ms684136(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />