# NativeMethods.ChangeWindowMessageFilterEx Method (SafeHandle, UInt32, ChangeWindowMessageFilterExAction, ChangeFilter)
 

Modifies the `User Interface Privilege Isolation` (`UIPI`) message filter for a specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool ChangeWindowMessageFilterEx(
	SafeHandle hWnd,
	uint msg,
	ChangeWindowMessageFilterExAction action,
	ref ChangeFilter refChangeFilter
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function ChangeWindowMessageFilterEx ( 
	hWnd As SafeHandle,
	msg As UInteger,
	action As ChangeWindowMessageFilterExAction,
	ByRef refChangeFilter As ChangeFilter
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim msg As UInteger
Dim action As ChangeWindowMessageFilterExAction
Dim refChangeFilter As ChangeFilter
Dim returnValue As Boolean

returnValue = NativeMethods.ChangeWindowMessageFilterEx(hWnd, 
	msg, action, refChangeFilter)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool ChangeWindowMessageFilterEx(
	SafeHandle^ hWnd, 
	unsigned int msg, 
	ChangeWindowMessageFilterExAction action, 
	ChangeFilter% refChangeFilter
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member ChangeWindowMessageFilterEx : 
        hWnd : SafeHandle * 
        msg : uint32 * 
        action : ChangeWindowMessageFilterExAction * 
        refChangeFilter : ChangeFilter byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window whose UIPI message filter is to be modified.</dd><dt>msg</dt><dd>Type: System.UInt32<br />The message that the message filter allows through or blocks.</dd><dt>action</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ChangeWindowMessageFilterExAction">DevCase.Interop.Unmanaged.Win32.Enums.ChangeWindowMessageFilterExAction</a><br />The action to be performed.</dd><dt>refChangeFilter</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ChangeFilter">DevCase.Interop.Unmanaged.Win32.Structures.ChangeFilter</a><br />Optional pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ChangeFilter">ChangeFilter</a> structure. 

 If the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChangeWindowMessageFilterEx">ChangeWindowMessageFilterEx(IntPtr, EditControlMessages, ChangeWindowMessageFilterExAction, ChangeFilter)</a> function succeeds, this structure contains information about the success.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd388202%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd388202%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChangeWindowMessageFilterEx">ChangeWindowMessageFilterEx Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />