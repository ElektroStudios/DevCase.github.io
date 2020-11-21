# NativeMethods.GetMenuItemInfo Method (IntPtr, UInt32, Boolean, MenuItemInfo)
 

Gets the handle of the form's system menu.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool GetMenuItemInfo(
	IntPtr hMenu,
	uint uItem,
	bool byPosition,
	ref MenuItemInfo refInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetMenuItemInfo ( 
	hMenu As IntPtr,
	uItem As UInteger,
	byPosition As Boolean,
	ByRef refInfo As MenuItemInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hMenu As IntPtr
Dim uItem As UInteger
Dim byPosition As Boolean
Dim refInfo As MenuItemInfo
Dim returnValue As Boolean

returnValue = NativeMethods.GetMenuItemInfo(hMenu, 
	uItem, byPosition, refInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool GetMenuItemInfo(
	IntPtr hMenu, 
	unsigned int uItem, 
	bool byPosition, 
	MenuItemInfo% refInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetMenuItemInfo : 
        hMenu : IntPtr * 
        uItem : uint32 * 
        byPosition : bool * 
        refInfo : MenuItemInfo byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hMenu</dt><dd>Type: System.IntPtr<br />The handle to the menu that contains the menu item.</dd><dt>uItem</dt><dd>Type: System.UInt32<br />The identifier or position of the menu item to get information about. 

 The meaning of this parameter depends on the value of fByPosition.</dd><dt>byPosition</dt><dd>Type: System.Boolean<br />The meaning of *uItem*. If this parameter is `false` (`False` in Visual Basic), uItem is a menu item identifier. 

 If this parameter is `true` (`True` in Visual Basic), it is a menu item position.</dd><dt>refInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo">DevCase.Interop.Unmanaged.Win32.Structures.MenuItemInfo</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo">MenuItemInfo</a> structure that specifies the information to retrieve. 

 Note that you must set the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_SizeOfStruct">SizeOfStruct</a> member to `Marshal.SizeOf(Of MenuItemInfo)` before calling this function.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647980%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647980%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMenuItemInfo">GetMenuItemInfo Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />