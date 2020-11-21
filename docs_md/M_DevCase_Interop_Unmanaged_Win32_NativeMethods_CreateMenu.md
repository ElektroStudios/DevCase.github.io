# NativeMethods.CreateMenu Method 
 

Creates a menu. 

 The menu is initially empty, but it can be filled with menu items by using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_InsertMenuItem">InsertMenuItem(IntPtr, Int32, Boolean, MenuItemInfo)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_AppendMenu">AppendMenu(IntPtr, UInt32, UIntPtr, String)</a>, and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_InsertMenuItem">InsertMenuItem(IntPtr, Int32, Boolean, MenuItemInfo)</a> functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr CreateMenu()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function CreateMenu As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateMenu()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr CreateMenu()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member CreateMenu : unit -> IntPtr 

```


#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the newly created menu. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647624%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647624%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />