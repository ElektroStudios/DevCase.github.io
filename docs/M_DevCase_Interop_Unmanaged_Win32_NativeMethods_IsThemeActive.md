# NativeMethods.IsThemeActive Method 
 

Tests if a visual style for the current application is active.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("UxTheme.dll")]
public static bool IsThemeActive()
```

**VB**<br />
``` VB
<DllImportAttribute("UxTheme.dll">]
Public Shared Function IsThemeActive As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = NativeMethods.IsThemeActive()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"UxTheme.dll")]
static bool IsThemeActive()
```

**F#**<br />
``` F#
[<DllImportAttribute("UxTheme.dll")>]
static member IsThemeActive : unit -> bool 

```


#### Return Value
Type: Boolean<br />If a visual style is enabled on the system, the return value is `true` (`True` in Visual Basic). 

 If a visual style is not enabled on the system, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb759813%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb759813%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />