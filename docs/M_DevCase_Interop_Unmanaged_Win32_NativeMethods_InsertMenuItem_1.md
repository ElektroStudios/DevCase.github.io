# NativeMethods.InsertMenuItem Method (SafeHandle, Int32, Boolean, MenuItemInfo)
 

Insert a menu item into an existing menu.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool InsertMenuItem(
	SafeHandle hMenu,
	int uItem,
	bool byPosition,
	ref MenuItemInfo refInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function InsertMenuItem ( 
	hMenu As SafeHandle,
	uItem As Integer,
	byPosition As Boolean,
	ByRef refInfo As MenuItemInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hMenu As SafeHandle
Dim uItem As Integer
Dim byPosition As Boolean
Dim refInfo As MenuItemInfo
Dim returnValue As Boolean

returnValue = NativeMethods.InsertMenuItem(hMenu, 
	uItem, byPosition, refInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool InsertMenuItem(
	SafeHandle^ hMenu, 
	int uItem, 
	bool byPosition, 
	MenuItemInfo% refInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member InsertMenuItem : 
        hMenu : SafeHandle * 
        uItem : int * 
        byPosition : bool * 
        refInfo : MenuItemInfo byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hMenu</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the menu in which the new menu item is inserted.</dd><dt>uItem</dt><dd>Type: System.Int32<br />The identifier or position of the menu item before which to insert the new item. 

 The meaning of this parameter depends on the value of *byPosition*.</dd><dt>byPosition</dt><dd>Type: System.Boolean<br />Controls the meaning of uItem. 

 If this parameter is `false` (`False` in Visual Basic), uItem is a menu item identifier. Otherwise, it is a menu item position.</dd><dt>refInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo">DevCase.Interop.Unmanaged.Win32.Structures.MenuItemInfo</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo">MenuItemInfo</a> structure that contains information about the new menu item.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647988%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647988%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_InsertMenuItem">InsertMenuItem Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />