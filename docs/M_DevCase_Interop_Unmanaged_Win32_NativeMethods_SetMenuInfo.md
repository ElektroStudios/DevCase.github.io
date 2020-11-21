# NativeMethods.SetMenuInfo Method (IntPtr, MenuInfo)
 

Sets information for a specified menu.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool SetMenuInfo(
	IntPtr hmenu,
	in MenuInfo refInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function SetMenuInfo ( 
	hmenu As IntPtr,
	ByRef refInfo As MenuInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hmenu As IntPtr
Dim refInfo As MenuInfo
Dim returnValue As Boolean

returnValue = NativeMethods.SetMenuInfo(hmenu, 
	refInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool SetMenuInfo(
	IntPtr hmenu, 
	[InAttribute] MenuInfo% refInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member SetMenuInfo : 
        hmenu : IntPtr * 
        refInfo : MenuInfo byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hmenu</dt><dd>Type: System.IntPtr<br />\[Missing <param name="hmenu"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.SetMenuInfo(System.IntPtr,DevCase.Interop.Unmanaged.Win32.Structures.MenuInfo@)"\]</dd><dt>refInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo">DevCase.Interop.Unmanaged.Win32.Structures.MenuInfo</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo">MenuInfo</a> structure that specifies the information to retrieve.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647997%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647997%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetMenuInfo">SetMenuInfo Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />