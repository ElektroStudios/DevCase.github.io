# NativeMethods.DefFrameProc Method 
 

Provides default processing for any window messages that the window procedure of a multiple-document interface (MDI) frame window does not process. 

 All window messages that are not explicitly processed by the window procedure must be passed to the DefFrameProc(IntPtr, IntPtr, UInt32, IntPtr, IntPtr) function, not the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DefWindowProc">DefWindowProc(IntPtr, UInt32, IntPtr, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static IntPtr DefFrameProc(
	IntPtr hWnd,
	IntPtr hWndMDIClient,
	uint msg,
	IntPtr wParam,
	IntPtr lParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function DefFrameProc ( 
	hWnd As IntPtr,
	hWndMDIClient As IntPtr,
	msg As UInteger,
	wParam As IntPtr,
	lParam As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim hWndMDIClient As IntPtr
Dim msg As UInteger
Dim wParam As IntPtr
Dim lParam As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.DefFrameProc(hWnd, 
	hWndMDIClient, msg, wParam, lParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static IntPtr DefFrameProc(
	IntPtr hWnd, 
	IntPtr hWndMDIClient, 
	unsigned int msg, 
	IntPtr wParam, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member DefFrameProc : 
        hWnd : IntPtr * 
        hWndMDIClient : IntPtr * 
        msg : uint32 * 
        wParam : IntPtr * 
        lParam : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the MDI frame window.</dd><dt>hWndMDIClient</dt><dd>Type: System.IntPtr<br />A handle to the MDI client window.</dd><dt>msg</dt><dd>Type: System.UInt32<br />The message to be processed.</dd><dt>wParam</dt><dd>Type: System.IntPtr<br />Additional message information. The content of this parameter depends on the value of the *msg* parameter.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />Additional message information. The content of this parameter depends on the value of the *msg* parameter.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value specifies the result of the message processing and depends on the message. 

 If the *hWndMDIClient* parameter is Zero, the return value is the same as for the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DefWindowProc">DefWindowProc(IntPtr, UInt32, IntPtr, IntPtr)</a> function.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-defframeproca" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-defframeproca</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />