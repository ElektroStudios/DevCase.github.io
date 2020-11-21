# NativeMethods.NotifyWinEvent Method 
 

Signals the system that a predefined event occurred. 

 If any client applications have registered a hook function for the event, the system calls the client's hook function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static void NotifyWinEvent(
	uint winEvent,
	IntPtr hWnd,
	int idObject,
	int idChild
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Sub NotifyWinEvent ( 
	winEvent As UInteger,
	hWnd As IntPtr,
	idObject As Integer,
	idChild As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim winEvent As UInteger
Dim hWnd As IntPtr
Dim idObject As Integer
Dim idChild As Integer

NativeMethods.NotifyWinEvent(winEvent, hWnd, 
	idObject, idChild)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static void NotifyWinEvent(
	unsigned int winEvent, 
	IntPtr hWnd, 
	int idObject, 
	int idChild
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member NotifyWinEvent : 
        winEvent : uint32 * 
        hWnd : IntPtr * 
        idObject : int * 
        idChild : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>winEvent</dt><dd>Type: System.UInt32<br />Specifies the event that occurred. This value must be one of the event constants.</dd><dt>hWnd</dt><dd>Type: System.IntPtr<br />Handle to the window that contains the object that generated the event.</dd><dt>idObject</dt><dd>Type: System.Int32<br />Identifies the object that generated the event. This value is either one of the predefined object identifiers or a custom object ID value.</dd><dt>idChild</dt><dd>Type: System.Int32<br />Identifies whether the event was generated by an object or by a child element of the object. If this value is CHILDID_SELF, the event was generated by the object itself. 

 If not CHILDID_SELF, this value is the child ID of the element that generated the event.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-notifywinevent" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-notifywinevent</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />