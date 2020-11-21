# Delegates.HookProc Delegate
 

A Delegates.HookProc delegate representing a hook procedure method. 

 ( for parameter `hookProc` of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowsHookEx">SetWindowsHookEx(HookType, Delegates.HookProc, IntPtr, UInt32)</a> function. )

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate IntPtr HookProc(
	int nCode,
	IntPtr wParam,
	IntPtr lParam
)
```

**VB**<br />
``` VB
Public Delegate Function HookProc ( 
	nCode As Integer,
	wParam As IntPtr,
	lParam As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As New HookProc(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate IntPtr HookProc(
	int nCode, 
	IntPtr wParam, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
type HookProc = 
    delegate of 
        nCode : int * 
        wParam : IntPtr * 
        lParam : IntPtr -> IntPtr
```


#### Parameters
&nbsp;<dl><dt>nCode</dt><dd>Type: System.Int32<br />The hook code of the current Delegates.HookProc procedure. 

 So the next call to Delegates.HookProc procedure uses this code to determine how to process the hook information.</dd><dt>wParam</dt><dd>Type: System.IntPtr<br />The `wParam` value passed to the current Delegates.HookProc procedure. 

 The meaning of this parameter depends on the type of hook associated with the current hook chain.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />The `lParam` value passed to the current Delegates.HookProc procedure. 

 The meaning of this parameter depends on the type of hook associated with the current hook chain.</dd></dl>

#### Return Value
Type: IntPtr<br />The meaning of the return value depends on the hook type. 

 For more information, see the descriptions of the individual hook procedures.

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644990%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644990%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />