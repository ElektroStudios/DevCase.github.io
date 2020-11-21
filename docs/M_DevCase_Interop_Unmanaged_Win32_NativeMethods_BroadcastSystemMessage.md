# NativeMethods.BroadcastSystemMessage Method (BroadcastSystemMessageFlags, BroadcastSystemMessageInfo, WindowMessages, IntPtr, IntPtr)
 

Sends a message to the specified recipients. 

 The recipients can be applications, installable drivers, network drivers, system-level device drivers, or any combination of these system components. 

 To receive additional information if the request is defined, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BroadcastSystemMessageEx">BroadcastSystemMessageEx(BroadcastSystemMessageFlags, BroadcastSystemMessageInfo, WindowMessages, IntPtr, IntPtr, BroadcastSystemMessageExInfo)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static int BroadcastSystemMessage(
	BroadcastSystemMessageFlags flags,
	ref BroadcastSystemMessageInfo refInfo,
	WindowMessages msg,
	[OptionalAttribute] IntPtr wParam,
	[OptionalAttribute] IntPtr lParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function BroadcastSystemMessage ( 
	flags As BroadcastSystemMessageFlags,
	ByRef refInfo As BroadcastSystemMessageInfo,
	msg As WindowMessages,
	<OptionalAttribute> wParam As IntPtr,
	<OptionalAttribute> lParam As IntPtr
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim flags As BroadcastSystemMessageFlags
Dim refInfo As BroadcastSystemMessageInfo
Dim msg As WindowMessages
Dim wParam As IntPtr
Dim lParam As IntPtr
Dim returnValue As Integer

returnValue = NativeMethods.BroadcastSystemMessage(flags, 
	refInfo, msg, wParam, lParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static int BroadcastSystemMessage(
	BroadcastSystemMessageFlags flags, 
	BroadcastSystemMessageInfo% refInfo, 
	WindowMessages msg, 
	[OptionalAttribute] IntPtr wParam, 
	[OptionalAttribute] IntPtr lParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member BroadcastSystemMessage : 
        flags : BroadcastSystemMessageFlags * 
        refInfo : BroadcastSystemMessageInfo byref * 
        msg : WindowMessages * 
        [<OptionalAttribute>] wParam : IntPtr * 
        [<OptionalAttribute>] lParam : IntPtr -> int 

```


#### Parameters
&nbsp;<dl><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BroadcastSystemMessageFlags">DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageFlags</a><br />The broadcast options.</dd><dt>refInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BroadcastSystemMessageInfo">DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageInfo</a><br />A pointer to a variable that contains and receives information about the recipients of the message. 

 When the function returns, this variable receives a combination of these values identifying which recipients actually received the message.</dd><dt>msg</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages</a><br />The message to be sent. See <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WindowMessages</a>.</dd><dt>wParam (Optional)</dt><dd>Type: System.IntPtr<br />Additional message-specific information.</dd><dt>lParam (Optional)</dt><dd>Type: System.IntPtr<br />Additional message-specific information.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value is a positive value. 

 If the function is unable to broadcast the message, the return value is –1. 

 If the *flags* parameter is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BroadcastSystemMessageFlags">Query</a> and at least one recipient returned BROADCAST_QUERY_DENY to the corresponding message, the return value is zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-broadcastsystemmessage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-broadcastsystemmessage</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_BroadcastSystemMessage">BroadcastSystemMessage Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />