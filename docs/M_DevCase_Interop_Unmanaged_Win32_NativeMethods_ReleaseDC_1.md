# NativeMethods.ReleaseDC Method (SafeHandle, IntPtr)
 

Releases a device context (DC), freeing it for use by other applications. 

 The effect of the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ReleaseDC">ReleaseDC(IntPtr, IntPtr)</a> function depends on the type of DC. It frees only common and window DCs. It has no effect on class or private DCs.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool ReleaseDC(
	SafeHandle hWnd,
	IntPtr hdc
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function ReleaseDC ( 
	hWnd As SafeHandle,
	hdc As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim hdc As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.ReleaseDC(hWnd, 
	hdc)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool ReleaseDC(
	SafeHandle^ hWnd, 
	IntPtr hdc
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member ReleaseDC : 
        hWnd : SafeHandle * 
        hdc : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A IntPtr handle to the window whose DC is to be released.</dd><dt>hdc</dt><dd>Type: System.IntPtr<br />A IntPtr handle to the DC to be released.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the DC was released, `false` (`False` in Visual Basic) if the DC was not released.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd162920%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd162920%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ReleaseDC">ReleaseDC Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />