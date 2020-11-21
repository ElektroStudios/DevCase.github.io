# NativeMethods.DwmDefWindowProc Method 
 

Default window procedure for Desktop Window Manager (DWM) hit testing within the non-client area. 

 You also need to ensure that DwmDefWindowProc(IntPtr, UInt32, IntPtr, IntPtr, IntPtr) is called for the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcMouseLeave</a> message. 

 If DwmDefWindowProc(IntPtr, UInt32, IntPtr, IntPtr, IntPtr) is not called for the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcMouseLeave</a> message, DWM does not remove the highlighting from the Maximize, Minimize, and Close buttons when the cursor leaves the window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DwmApi.dll", ExactSpelling = true)]
public static bool DwmDefWindowProc(
	IntPtr hwnd,
	uint msg,
	IntPtr wParam,
	IntPtr lParam,
	out IntPtr refResult
)
```

**VB**<br />
``` VB
<DllImportAttribute("DwmApi.dll", ExactSpelling := true>]
Public Shared Function DwmDefWindowProc ( 
	hwnd As IntPtr,
	msg As UInteger,
	wParam As IntPtr,
	lParam As IntPtr,
	<OutAttribute> ByRef refResult As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hwnd As IntPtr
Dim msg As UInteger
Dim wParam As IntPtr
Dim lParam As IntPtr
Dim refResult As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.DwmDefWindowProc(hwnd, 
	msg, wParam, lParam, refResult)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DwmApi.dll", ExactSpelling = true)]
static bool DwmDefWindowProc(
	IntPtr hwnd, 
	unsigned int msg, 
	IntPtr wParam, 
	IntPtr lParam, 
	[OutAttribute] IntPtr% refResult
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DwmApi.dll", ExactSpelling = true)>]
static member DwmDefWindowProc : 
        hwnd : IntPtr * 
        msg : uint32 * 
        wParam : IntPtr * 
        lParam : IntPtr * 
        refResult : IntPtr byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hwnd</dt><dd>Type: System.IntPtr<br />\[Missing <param name="hwnd"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.DwmDefWindowProc(System.IntPtr,System.UInt32,System.IntPtr,System.IntPtr,System.IntPtr@)"\]</dd><dt>msg</dt><dd>Type: System.UInt32<br />The message to be processed.</dd><dt>wParam</dt><dd>Type: System.IntPtr<br />Additional message information. The content of this parameter depends on the value of the *msg* parameter.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />Additional message information. The content of this parameter depends on the value of the *msg* parameter.</dd><dt>refResult</dt><dd>Type: System.IntPtr<br />A pointer to an LRESULT value that, when this method returns successfully,receives the result of the hit test..</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if DwmDefWindowProc handled the message; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/nf-dwmapi-dwmdefwindowproc" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/nf-dwmapi-dwmdefwindowproc</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />