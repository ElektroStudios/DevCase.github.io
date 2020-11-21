# NativeMethods.DwmSetIconicLivePreviewBitmap Method (IntPtr, IntPtr, NativePoint, DwmIconicLivePreviewFlags)
 

Sets a static iconic Bitmap on a window or tab to use as a thumbnail representation. 

 The Taskbar can use this Bitmap as a thumbnail switch target for the window or tab.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DwmApi.dll")]
public static int DwmSetIconicLivePreviewBitmap(
	IntPtr hWnd,
	IntPtr hBitmap,
	ref NativePoint refOffset,
	DwmIconicLivePreviewFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("DwmApi.dll">]
Public Shared Function DwmSetIconicLivePreviewBitmap ( 
	hWnd As IntPtr,
	hBitmap As IntPtr,
	ByRef refOffset As NativePoint,
	flags As DwmIconicLivePreviewFlags
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim hBitmap As IntPtr
Dim refOffset As NativePoint
Dim flags As DwmIconicLivePreviewFlags
Dim returnValue As Integer

returnValue = NativeMethods.DwmSetIconicLivePreviewBitmap(hWnd, 
	hBitmap, refOffset, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DwmApi.dll")]
static int DwmSetIconicLivePreviewBitmap(
	IntPtr hWnd, 
	IntPtr hBitmap, 
	NativePoint% refOffset, 
	DwmIconicLivePreviewFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DwmApi.dll")>]
static member DwmSetIconicLivePreviewBitmap : 
        hWnd : IntPtr * 
        hBitmap : IntPtr * 
        refOffset : NativePoint byref * 
        flags : DwmIconicLivePreviewFlags -> int 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle To the window Or tab. 

 This window must belong To the calling process.</dd><dt>hBitmap</dt><dd>Type: System.IntPtr<br />A handle to the bitmap to represent the window that *hwnd* specifies.</dd><dt>refOffset</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">DevCase.Interop.Unmanaged.Win32.Structures.NativePoint</a><br />The offset of a tab window's client region (the content area inside the client window frame) from the host window's frame. 

 This offset enables the tab window's contents to be drawn correctly in a live preview when it is drawn without its frame.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DwmIconicLivePreviewFlags">DevCase.Interop.Unmanaged.Win32.Enums.DwmIconicLivePreviewFlags</a><br />The display options for the live preview.</dd></dl>

#### Return Value
Type: Int32<br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd389410%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd389410%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_DwmSetIconicLivePreviewBitmap">DwmSetIconicLivePreviewBitmap Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />