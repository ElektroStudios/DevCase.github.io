# NativeMethods.EnableMenuItem Method (IntPtr, UInt32, Int32)
 

Sets the state of the specified menu item.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool EnableMenuItem(
	IntPtr hMenu,
	uint uIDEnableItem,
	int uEnable
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function EnableMenuItem ( 
	hMenu As IntPtr,
	uIDEnableItem As UInteger,
	uEnable As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hMenu As IntPtr
Dim uIDEnableItem As UInteger
Dim uEnable As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.EnableMenuItem(hMenu, 
	uIDEnableItem, uEnable)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool EnableMenuItem(
	IntPtr hMenu, 
	unsigned int uIDEnableItem, 
	int uEnable
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member EnableMenuItem : 
        hMenu : IntPtr * 
        uIDEnableItem : uint32 * 
        uEnable : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>hMenu</dt><dd>Type: System.IntPtr<br />A handle to the menu.</dd><dt>uIDEnableItem</dt><dd>Type: System.UInt32<br />The menu item to be enabled, disabled, or grayed, as determined by the uEnable parameter. 

 This parameter specifies an item in a menu bar, menu, or submenu.</dd><dt>uEnable</dt><dd>Type: System.Int32<br />Controls the interpretation of the *uIDEnableItem* parameter and indicate whether the menu item is enabled, disabled, or grayed.</dd></dl>

#### Return Value
Type: Boolean<br />The previous state of the menu item if it exists, or `-1` otherwise.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647636%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647636%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnableMenuItem">EnableMenuItem Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />