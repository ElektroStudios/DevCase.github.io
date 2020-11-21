# NativeMethods.GetMenuItemCount Method (SafeHandle)
 

Determines the number of items in the specified menu.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static int GetMenuItemCount(
	SafeHandle hMenu
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetMenuItemCount ( 
	hMenu As SafeHandle
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hMenu As SafeHandle
Dim returnValue As Integer

returnValue = NativeMethods.GetMenuItemCount(hMenu)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static int GetMenuItemCount(
	SafeHandle^ hMenu
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetMenuItemCount : 
        hMenu : SafeHandle -> int 

```


#### Parameters
&nbsp;<dl><dt>hMenu</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the menu to be examined.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value specifies the number of items in the menu. 

 If the function fails, the return value is `-1`. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647978%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647978%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMenuItemCount">GetMenuItemCount Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />