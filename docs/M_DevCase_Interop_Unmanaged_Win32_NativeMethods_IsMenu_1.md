# NativeMethods.IsMenu Method (SafeHandle)
 

Determines whether a handle is a menu handle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool IsMenu(
	SafeHandle hMenu
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function IsMenu ( 
	hMenu As SafeHandle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hMenu As SafeHandle
Dim returnValue As Boolean

returnValue = NativeMethods.IsMenu(hMenu)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool IsMenu(
	SafeHandle^ hMenu
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member IsMenu : 
        hMenu : SafeHandle -> bool 

```


#### Parameters
&nbsp;<dl><dt>hMenu</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to be tested.</dd></dl>

#### Return Value
Type: Boolean<br />If the handle is a menu handle, the return is `true` (`True` in Visual Basic). 

 If the handle is not a menu handle, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647989%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647989%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_IsMenu">IsMenu Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />