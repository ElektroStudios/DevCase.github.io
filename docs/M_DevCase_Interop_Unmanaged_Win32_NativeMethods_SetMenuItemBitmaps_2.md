# NativeMethods.SetMenuItemBitmaps Method (SafeHandle, UInt32, MenuPosition, SafeBitmapHandle, SafeBitmapHandle)
 

Associates the specified bitmap with a menu item. 

 Whether the menu item is selected or clear, the system displays the appropriate bitmap next to the menu item.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool SetMenuItemBitmaps(
	SafeHandle hMenu,
	uint uPosition,
	MenuPosition uFlags,
	SafeBitmapHandle hBitmapUnchecked,
	SafeBitmapHandle hBitmapChecked
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function SetMenuItemBitmaps ( 
	hMenu As SafeHandle,
	uPosition As UInteger,
	uFlags As MenuPosition,
	hBitmapUnchecked As SafeBitmapHandle,
	hBitmapChecked As SafeBitmapHandle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hMenu As SafeHandle
Dim uPosition As UInteger
Dim uFlags As MenuPosition
Dim hBitmapUnchecked As SafeBitmapHandle
Dim hBitmapChecked As SafeBitmapHandle
Dim returnValue As Boolean

returnValue = NativeMethods.SetMenuItemBitmaps(hMenu, 
	uPosition, uFlags, hBitmapUnchecked, 
	hBitmapChecked)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool SetMenuItemBitmaps(
	SafeHandle^ hMenu, 
	unsigned int uPosition, 
	MenuPosition uFlags, 
	SafeBitmapHandle^ hBitmapUnchecked, 
	SafeBitmapHandle^ hBitmapChecked
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member SetMenuItemBitmaps : 
        hMenu : SafeHandle * 
        uPosition : uint32 * 
        uFlags : MenuPosition * 
        hBitmapUnchecked : SafeBitmapHandle * 
        hBitmapChecked : SafeBitmapHandle -> bool 

```


#### Parameters
&nbsp;<dl><dt>hMenu</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the menu containing the item to receive new check-mark bitmaps.</dd><dt>uPosition</dt><dd>Type: System.UInt32<br />The menu item to be changed, as determined by the *uFlags* parameter.</dd><dt>uFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuPosition">DevCase.Interop.Unmanaged.Win32.Enums.MenuPosition</a><br />Specifies how the *uPosition* parameter is to be interpreted.</dd><dt>hBitmapUnchecked</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_SafeHandles_SafeBitmapHandle">DevCase.Interop.Unmanaged.Win32.SafeHandles.SafeBitmapHandle</a><br />A handle to the bitmap displayed when the menu item is not selected.</dd><dt>hBitmapChecked</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_SafeHandles_SafeBitmapHandle">DevCase.Interop.Unmanaged.Win32.SafeHandles.SafeBitmapHandle</a><br />A handle to the bitmap displayed when the menu item is selected.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647998%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647998%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetMenuItemBitmaps">SetMenuItemBitmaps Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />