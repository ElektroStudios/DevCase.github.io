# NativeMethods.KeybdEvent Method (Byte, Byte, KeybdEventFlags, UIntPtr)
 

Synthesizes a keystroke. 

 The system can use such a synthesized keystroke to generate a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_KeyDown</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_KeyUp</a> message. 

 The keyboard driver's interrupt handler calls the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_KeybdEvent">KeybdEvent(VirtualKeys, Byte, KeybdEventFlags, UIntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", EntryPoint = "keybd_event", SetLastError = true)]
public static void KeybdEvent(
	byte vkey,
	byte scanCode,
	KeybdEventFlags flags,
	UIntPtr extraInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", EntryPoint := "keybd_event", SetLastError := true>]
Public Shared Sub KeybdEvent ( 
	vkey As Byte,
	scanCode As Byte,
	flags As KeybdEventFlags,
	extraInfo As UIntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim vkey As Byte
Dim scanCode As Byte
Dim flags As KeybdEventFlags
Dim extraInfo As UIntPtrNativeMethods.KeybdEvent(vkey, scanCode, flags, 
	extraInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", EntryPoint = L"keybd_event", SetLastError = true)]
static void KeybdEvent(
	unsigned char vkey, 
	unsigned char scanCode, 
	KeybdEventFlags flags, 
	UIntPtr extraInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", EntryPoint = "keybd_event", SetLastError = true)>]
static member KeybdEvent : 
        vkey : byte * 
        scanCode : byte * 
        flags : KeybdEventFlags * 
        extraInfo : UIntPtr -> unit 

```


#### Parameters
&nbsp;<dl><dt>vkey</dt><dd>Type: System.Byte<br />A virtual-key code.</dd><dt>scanCode</dt><dd>Type: System.Byte<br />A hardware scan code for the key.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_KeybdEventFlags">DevCase.Interop.Unmanaged.Win32.Enums.KeybdEventFlags</a><br />Controls various aspects of function operation.</dd><dt>extraInfo</dt><dd>Type: System.UIntPtr<br />An additional value associated with the key stroke.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-keybd_event" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-keybd_event</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_KeybdEvent">KeybdEvent Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />