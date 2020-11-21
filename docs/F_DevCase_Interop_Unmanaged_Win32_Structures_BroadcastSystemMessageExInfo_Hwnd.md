# BroadcastSystemMessageExInfo.Hwnd Field
 

A handle to the window that denied the request. 

 This value is returned only if <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BroadcastSystemMessageEx">BroadcastSystemMessageEx(BroadcastSystemMessageFlags, BroadcastSystemMessageInfo, WindowMessages, IntPtr, IntPtr, BroadcastSystemMessageExInfo)</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BroadcastSystemMessageFlags">Query</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr Hwnd
```

**VB**<br />
``` VB
Public Hwnd As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As BroadcastSystemMessageExInfo
Dim value As IntPtr

value = instance.Hwnd

instance.Hwnd = value
```

**C++**<br />
``` C++
public:
IntPtr Hwnd
```

**F#**<br />
``` F#
val mutable Hwnd: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_BroadcastSystemMessageExInfo">BroadcastSystemMessageExInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />