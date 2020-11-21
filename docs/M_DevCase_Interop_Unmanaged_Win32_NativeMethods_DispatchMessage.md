# NativeMethods.DispatchMessage Method 
 

Dispatches a message to a window procedure. 

 It is typically used to dispatch a message retrieved by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMessage">GetMessage(NativeMessage, IntPtr, UInt32, UInt32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto)]
public static IntPtr DispatchMessage(
	in NativeMessage refMsg
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto>]
Public Shared Function DispatchMessage ( 
	ByRef refMsg As NativeMessage
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim refMsg As NativeMessage
Dim returnValue As IntPtr

returnValue = NativeMethods.DispatchMessage(refMsg)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto)]
static IntPtr DispatchMessage(
	[InAttribute] NativeMessage% refMsg
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto)>]
static member DispatchMessage : 
        refMsg : NativeMessage byref -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>refMsg</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">DevCase.Interop.Unmanaged.Win32.Structures.NativeMessage</a><br />A pointer to a structure that contains the message.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value specifies the value returned by the window procedure. 

 Although its meaning depends on the message being dispatched, the return value generally is ignored.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-dispatchmessage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-dispatchmessage</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />