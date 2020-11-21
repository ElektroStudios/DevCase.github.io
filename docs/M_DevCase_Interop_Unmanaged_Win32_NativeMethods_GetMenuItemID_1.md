# NativeMethods.GetMenuItemID Method (SafeHandle, Int32)
 

Retrieves the menu item identifier of a menu item located at the specified position in a menu.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static int GetMenuItemID(
	SafeHandle hMenu,
	int nPos
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function GetMenuItemID ( 
	hMenu As SafeHandle,
	nPos As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hMenu As SafeHandle
Dim nPos As Integer
Dim returnValue As Integer

returnValue = NativeMethods.GetMenuItemID(hMenu, 
	nPos)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static int GetMenuItemID(
	SafeHandle^ hMenu, 
	int nPos
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member GetMenuItemID : 
        hMenu : SafeHandle * 
        nPos : int -> int 

```


#### Parameters
&nbsp;<dl><dt>hMenu</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the menu that contains the item whose identifier is to be retrieved.</dd><dt>nPos</dt><dd>Type: System.Int32<br />The zero-based relative position of the menu item whose identifier is to be retrieved.</dd></dl>

#### Return Value
Type: Int32<br />The return value is the identifier of the specified menu item. 

 If the menu item identifier is Zero or if the specified item opens a submenu, the return value is `-1`.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647979%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647979%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMenuItemID">GetMenuItemID Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />