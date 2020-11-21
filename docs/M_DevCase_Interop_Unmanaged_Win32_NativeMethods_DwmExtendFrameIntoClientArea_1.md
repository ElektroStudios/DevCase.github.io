# NativeMethods.DwmExtendFrameIntoClientArea Method (SafeHandle, Margins)
 

Extends the window frame into the client area.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DwmApi.dll")]
public static int DwmExtendFrameIntoClientArea(
	SafeHandle hWnd,
	ref Margins refMargins
)
```

**VB**<br />
``` VB
<DllImportAttribute("DwmApi.dll">]
Public Shared Function DwmExtendFrameIntoClientArea ( 
	hWnd As SafeHandle,
	ByRef refMargins As Margins
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim refMargins As Margins
Dim returnValue As Integer

returnValue = NativeMethods.DwmExtendFrameIntoClientArea(hWnd, 
	refMargins)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DwmApi.dll")]
static int DwmExtendFrameIntoClientArea(
	SafeHandle^ hWnd, 
	Margins% refMargins
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DwmApi.dll")>]
static member DwmExtendFrameIntoClientArea : 
        hWnd : SafeHandle * 
        refMargins : Margins byref -> int 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window in which the frame will be extended into the client area.</dd><dt>refMargins</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Margins">DevCase.Interop.Unmanaged.Win32.Structures.Margins</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Margins">Margins</a> structure that describes the margins to use when extending the frame into the client area.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. 

 Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa969512%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa969512%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_DwmExtendFrameIntoClientArea">DwmExtendFrameIntoClientArea Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />