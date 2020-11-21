# NativeMethods.LockWorkStation Method 
 

Locks the workstation's display. 

 Locking a workstation protects it from unauthorized use.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool LockWorkStation()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function LockWorkStation As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = NativeMethods.LockWorkStation()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool LockWorkStation()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member LockWorkStation : unit -> bool 

```


#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 Because the function executes asynchronously, a `true` (`True` in Visual Basic) return value indicates that the operation has been initiated; 

 It does not indicate whether the workstation has been successfully locked. 



 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa376875%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa376875%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />