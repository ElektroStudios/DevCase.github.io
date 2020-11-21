# NativeMethods.SHChangeNotify Method (SHChangeNotifyEventID, SHChangeNotifyFlags, IntPtr, IntPtr)
 

Notifies the system of an event that an application has performed. 

 An application should use this function if it performs an action that may affect the Shell.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", SetLastError = true)]
public static void SHChangeNotify(
	SHChangeNotifyEventID eventId,
	SHChangeNotifyFlags flags,
	IntPtr item1,
	IntPtr item2
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", SetLastError := true>]
Public Shared Sub SHChangeNotify ( 
	eventId As SHChangeNotifyEventID,
	flags As SHChangeNotifyFlags,
	item1 As IntPtr,
	item2 As IntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim eventId As SHChangeNotifyEventID
Dim flags As SHChangeNotifyFlags
Dim item1 As IntPtr
Dim item2 As IntPtrNativeMethods.SHChangeNotify(eventId, flags, 
	item1, item2)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", SetLastError = true)]
static void SHChangeNotify(
	SHChangeNotifyEventID eventId, 
	SHChangeNotifyFlags flags, 
	IntPtr item1, 
	IntPtr item2
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", SetLastError = true)>]
static member SHChangeNotify : 
        eventId : SHChangeNotifyEventID * 
        flags : SHChangeNotifyFlags * 
        item1 : IntPtr * 
        item2 : IntPtr -> unit 

```


#### Parameters
&nbsp;<dl><dt>eventId</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyEventID">DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID</a><br />Describes the event that has occurred. Typically, only one event is specified at a time. 

 If more than one event is specified, the values contained in the *item1* and *item2* parameters must be the same, respectively, for all specified events.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyFlags</a><br />Flags that, when combined bitwise with `SHCNF_TYPE`, indicate the meaning of the dwItem1 and *item2* parameters.</dd><dt>item1</dt><dd>Type: System.IntPtr<br />Optional. First event-dependent value.</dd><dt>item2</dt><dd>Type: System.IntPtr<br />Optional. Second event-dependent value.</dd></dl>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762118%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762118%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHChangeNotify">SHChangeNotify Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />