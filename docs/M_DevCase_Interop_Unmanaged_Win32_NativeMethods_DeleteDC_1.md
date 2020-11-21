# NativeMethods.DeleteDC Method (SafeHandle)
 

Deletes the specified device context (DC). 

 An application must not delete a DC whose handle was obtained by calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetDC">GetDC(IntPtr)</a> function. instead, it must call the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ReleaseDC">ReleaseDC(IntPtr, IntPtr)</a> function to free the DC.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll")]
public static bool DeleteDC(
	SafeHandle hdc
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll">]
Public Shared Function DeleteDC ( 
	hdc As SafeHandle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hdc As SafeHandle
Dim returnValue As Boolean

returnValue = NativeMethods.DeleteDC(hdc)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll")]
static bool DeleteDC(
	SafeHandle^ hdc
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll")>]
static member DeleteDC : 
        hdc : SafeHandle -> bool 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the device context.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183533%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183533%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_DeleteDC">DeleteDC Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />