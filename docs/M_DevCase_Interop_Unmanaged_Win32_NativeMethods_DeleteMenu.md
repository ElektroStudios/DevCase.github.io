# NativeMethods.DeleteMenu Method (IntPtr, UInt32, MenuPosition)
 

Deletes an item from the specified menu. 

 If the menu item opens a menu or submenu, this function destroys the handle to the menu or submenu and frees the memory used by the menu or submenu.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool DeleteMenu(
	IntPtr hMenu,
	uint uPosition,
	MenuPosition uFlags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function DeleteMenu ( 
	hMenu As IntPtr,
	uPosition As UInteger,
	uFlags As MenuPosition
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hMenu As IntPtr
Dim uPosition As UInteger
Dim uFlags As MenuPosition
Dim returnValue As Boolean

returnValue = NativeMethods.DeleteMenu(hMenu, 
	uPosition, uFlags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool DeleteMenu(
	IntPtr hMenu, 
	unsigned int uPosition, 
	MenuPosition uFlags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member DeleteMenu : 
        hMenu : IntPtr * 
        uPosition : uint32 * 
        uFlags : MenuPosition -> bool 

```


#### Parameters
&nbsp;<dl><dt>hMenu</dt><dd>Type: System.IntPtr<br />A handle to the menu to be changed.</dd><dt>uPosition</dt><dd>Type: System.UInt32<br />The menu item to be deleted, as determined by the *uFlags* parameter.</dd><dt>uFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuPosition">DevCase.Interop.Unmanaged.Win32.Enums.MenuPosition</a><br />Indicates how the *uPosition* parameter is interpreted.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647629%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647629%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_DeleteMenu">DeleteMenu Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />