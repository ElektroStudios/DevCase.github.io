# NativeMethods.BroadcastSystemMessageEx Method (BroadcastSystemMessageFlags, BroadcastSystemMessageInfo, UInt32, IntPtr, IntPtr, BroadcastSystemMessageExInfo)
 

Sends a message to the specified recipients. 

 The recipients can be applications, installable drivers, network drivers, system-level device drivers, or any combination of these system components. 

 This function is similar to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BroadcastSystemMessage">BroadcastSystemMessage(BroadcastSystemMessageFlags, BroadcastSystemMessageInfo, WindowMessages, IntPtr, IntPtr)</a> except that this function can return more information from the recipients

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, SetLastError = true)]
public static int BroadcastSystemMessageEx(
	BroadcastSystemMessageFlags flags,
	ref BroadcastSystemMessageInfo refInfo,
	uint msg,
	[OptionalAttribute] IntPtr wParam,
	[OptionalAttribute] IntPtr lParam,
	ref BroadcastSystemMessageExInfo refMsgInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, SetLastError := true>]
Public Shared Function BroadcastSystemMessageEx ( 
	flags As BroadcastSystemMessageFlags,
	ByRef refInfo As BroadcastSystemMessageInfo,
	msg As UInteger,
	<OptionalAttribute> wParam As IntPtr,
	<OptionalAttribute> lParam As IntPtr,
	ByRef refMsgInfo As BroadcastSystemMessageExInfo
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim flags As BroadcastSystemMessageFlags
Dim refInfo As BroadcastSystemMessageInfo
Dim msg As UInteger
Dim wParam As IntPtr
Dim lParam As IntPtr
Dim refMsgInfo As BroadcastSystemMessageExInfo
Dim returnValue As Integer

returnValue = NativeMethods.BroadcastSystemMessageEx(flags, 
	refInfo, msg, wParam, lParam, refMsgInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, SetLastError = true)]
static int BroadcastSystemMessageEx(
	BroadcastSystemMessageFlags flags, 
	BroadcastSystemMessageInfo% refInfo, 
	unsigned int msg, 
	[OptionalAttribute] IntPtr wParam, 
	[OptionalAttribute] IntPtr lParam, 
	BroadcastSystemMessageExInfo% refMsgInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, SetLastError = true)>]
static member BroadcastSystemMessageEx : 
        flags : BroadcastSystemMessageFlags * 
        refInfo : BroadcastSystemMessageInfo byref * 
        msg : uint32 * 
        [<OptionalAttribute>] wParam : IntPtr * 
        [<OptionalAttribute>] lParam : IntPtr * 
        refMsgInfo : BroadcastSystemMessageExInfo byref -> int 

```


#### Parameters
&nbsp;<dl><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BroadcastSystemMessageFlags">DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageFlags</a><br />The broadcast options.</dd><dt>refInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BroadcastSystemMessageInfo">DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageInfo</a><br />A pointer to a variable that contains and receives information about the recipients of the message. 

 When the function returns, this variable receives a combination of these values identifying which recipients actually received the message.</dd><dt>msg</dt><dd>Type: System.UInt32<br />The message to be sent. See <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WindowMessages</a>.</dd><dt>wParam (Optional)</dt><dd>Type: System.IntPtr<br />Additional message-specific information.</dd><dt>lParam (Optional)</dt><dd>Type: System.IntPtr<br />Additional message-specific information.</dd><dt>refMsgInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_BroadcastSystemMessageExInfo">DevCase.Interop.Unmanaged.Win32.Structures.BroadcastSystemMessageExInfo</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_BroadcastSystemMessageExInfo">BroadcastSystemMessageExInfo</a> structure that contains additional information if the request is denied and *flags* is set to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BroadcastSystemMessageFlags">Query</a>.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value is a positive value. 

 If the function is unable to broadcast the message, the return value is –1. 

 If the *flags* parameter is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BroadcastSystemMessageFlags">Query</a> and at least one recipient returned BROADCAST_QUERY_DENY to the corresponding message, the return value is zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-broadcastsystemmessageexa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-broadcastsystemmessageexa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_BroadcastSystemMessageEx">BroadcastSystemMessageEx Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />