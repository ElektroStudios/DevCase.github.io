# NativeMethods.AppendMenu Method (SafeHandle, UInt32, UIntPtr, String)
 

Appends a new item to the end of the specified menu bar, drop-down menu, submenu, or shortcut menu. 

 You can use this function to specify the content, appearance, and behavior of the menu item.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool AppendMenu(
	SafeHandle hMenu,
	uint uFlags,
	UIntPtr uIDNewItem,
	string lpNewItem
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function AppendMenu ( 
	hMenu As SafeHandle,
	uFlags As UInteger,
	uIDNewItem As UIntPtr,
	lpNewItem As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hMenu As SafeHandle
Dim uFlags As UInteger
Dim uIDNewItem As UIntPtr
Dim lpNewItem As String
Dim returnValue As Boolean

returnValue = NativeMethods.AppendMenu(hMenu, 
	uFlags, uIDNewItem, lpNewItem)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool AppendMenu(
	SafeHandle^ hMenu, 
	unsigned int uFlags, 
	UIntPtr uIDNewItem, 
	String^ lpNewItem
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member AppendMenu : 
        hMenu : SafeHandle * 
        uFlags : uint32 * 
        uIDNewItem : UIntPtr * 
        lpNewItem : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>hMenu</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the menu bar, drop-down menu, submenu, or shortcut menu to be changed.</dd><dt>uFlags</dt><dd>Type: System.UInt32<br />Controls the appearance and behavior of the new menu item.</dd><dt>uIDNewItem</dt><dd>Type: System.UIntPtr<br />The identifier of the new menu item or, if the uFlags parameter is set to `MF_POPUP` a handle to the drop-down menu or submenu.</dd><dt>lpNewItem</dt><dd>Type: System.String<br />The content of the new menu item.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647616%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647616%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_AppendMenu">AppendMenu Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />