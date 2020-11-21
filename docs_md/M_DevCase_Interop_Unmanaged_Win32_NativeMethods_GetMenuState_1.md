# NativeMethods.GetMenuState Method (SafeHandle, UInt32, MenuPosition)
 

**Note: This API is now obsolete.**

Retrieves the menu flags associated with the specified menu item. 

 If the menu item opens a submenu, this function also returns the number of items in the submenu.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
[ObsoleteAttribute]
public static uint GetMenuState(
	SafeHandle hMenu,
	uint uId,
	MenuPosition uFlags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
<ObsoleteAttribute>
Public Shared Function GetMenuState ( 
	hMenu As SafeHandle,
	uId As UInteger,
	uFlags As MenuPosition
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hMenu As SafeHandle
Dim uId As UInteger
Dim uFlags As MenuPosition
Dim returnValue As UInteger

returnValue = NativeMethods.GetMenuState(hMenu, 
	uId, uFlags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
[ObsoleteAttribute]
static unsigned int GetMenuState(
	SafeHandle^ hMenu, 
	unsigned int uId, 
	MenuPosition uFlags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
[<ObsoleteAttribute>]
static member GetMenuState : 
        hMenu : SafeHandle * 
        uId : uint32 * 
        uFlags : MenuPosition -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hMenu</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the menu that contains the menu item whose flags are to be retrieved.</dd><dt>uId</dt><dd>Type: System.UInt32<br />The menu item for which the menu flags are to be retrieved, as determined by the *uFlags* parameter.</dd><dt>uFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuPosition">DevCase.Interop.Unmanaged.Win32.Enums.MenuPosition</a><br />Indicates how the *uId* parameter is interpreted.</dd></dl>

#### Return Value
Type: UInt32<br />If the specified item does not exist, the return value is -1. 

 If the menu item opens a submenu, the low-order byte of the return value contains the menu flags associated with the item, and the high-order byte contains the number of items in the submenu opened by the item. 

 Otherwise, the return value is a mask (Bitwise `OR`) of the menu flags.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647982%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647982%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMenuState">GetMenuState Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />