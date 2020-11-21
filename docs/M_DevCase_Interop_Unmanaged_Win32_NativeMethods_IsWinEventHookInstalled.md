# NativeMethods.IsWinEventHookInstalled Method 
 

Determines whether there is an installed WinEvent hook that might be notified of a specified event.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static bool IsWinEventHookInstalled(
	uint winEvent
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function IsWinEventHookInstalled ( 
	winEvent As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim winEvent As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.IsWinEventHookInstalled(winEvent)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static bool IsWinEventHookInstalled(
	unsigned int winEvent
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member IsWinEventHookInstalled : 
        winEvent : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>winEvent</dt><dd>Type: System.UInt32<br />The event constant that hooks might be notified of. The function checks whether there is an installed hook for this event constant.</dd></dl>

#### Return Value
Type: Boolean<br />If there is a hook to be notified of the specified event, the return value is `true` (`True` in Visual Basic). 

 If there are no hooks to be notified of the specified event, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-iswineventhookinstalled" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-iswineventhookinstalled</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />