# NativeMethods.GetEffectiveClientRect Method (IntPtr, Rectangle, IntPtr)
 

Calculates the dimensions of a rectangle in the client area that contains all the specified controls.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ComCtl32.dll", SetLastError = true)]
public static void GetEffectiveClientRect(
	IntPtr hWnd,
	out Rectangle refRect,
	IntPtr info
)
```

**VB**<br />
``` VB
<DllImportAttribute("ComCtl32.dll", SetLastError := true>]
Public Shared Sub GetEffectiveClientRect ( 
	hWnd As IntPtr,
	<OutAttribute> ByRef refRect As Rectangle,
	info As IntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim refRect As Rectangle
Dim info As IntPtrNativeMethods.GetEffectiveClientRect(hWnd, 
	refRect, info)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ComCtl32.dll", SetLastError = true)]
static void GetEffectiveClientRect(
	IntPtr hWnd, 
	[OutAttribute] Rectangle% refRect, 
	IntPtr info
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ComCtl32.dll", SetLastError = true)>]
static member GetEffectiveClientRect : 
        hWnd : IntPtr * 
        refRect : Rectangle byref * 
        info : IntPtr -> unit 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window that has the client area to check.</dd><dt>refRect</dt><dd>Type: System.Drawing.Rectangle<br />A Rectangle structure that receives the dimensions of the rectangle.</dd><dt>info</dt><dd>Type: System.IntPtr<br />A pointer to a null-terminated array of integers that identify controls in the client area. 

 Each control requires a pair of consecutive elements. 

 The first element of the pair must be nonzero and the second element of the pair must be the control identifier. 

 The first pair represents the menu and is ignored. 

 The last element must be zero to identify the end of the array.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-geteffectiveclientrect" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-geteffectiveclientrect</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetEffectiveClientRect">GetEffectiveClientRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />