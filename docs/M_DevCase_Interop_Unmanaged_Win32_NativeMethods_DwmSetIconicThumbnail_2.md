# NativeMethods.DwmSetIconicThumbnail Method (SafeHandle, SafeBitmapHandle, DwmIconicThumbnailFlags)
 

Sets a static iconic Bitmap on a window or tab to use as a thumbnail representation. 

 The Taskbar can use this Bitmap as a thumbnail switch target for the window or tab.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DwmApi.dll")]
public static int DwmSetIconicThumbnail(
	SafeHandle hWnd,
	SafeBitmapHandle hBitmap,
	DwmIconicThumbnailFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("DwmApi.dll">]
Public Shared Function DwmSetIconicThumbnail ( 
	hWnd As SafeHandle,
	hBitmap As SafeBitmapHandle,
	flags As DwmIconicThumbnailFlags
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim hBitmap As SafeBitmapHandle
Dim flags As DwmIconicThumbnailFlags
Dim returnValue As Integer

returnValue = NativeMethods.DwmSetIconicThumbnail(hWnd, 
	hBitmap, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DwmApi.dll")]
static int DwmSetIconicThumbnail(
	SafeHandle^ hWnd, 
	SafeBitmapHandle^ hBitmap, 
	DwmIconicThumbnailFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DwmApi.dll")>]
static member DwmSetIconicThumbnail : 
        hWnd : SafeHandle * 
        hBitmap : SafeBitmapHandle * 
        flags : DwmIconicThumbnailFlags -> int 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle To the window Or tab. 

 This window must belong To the calling process.</dd><dt>hBitmap</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_SafeHandles_SafeBitmapHandle">DevCase.Interop.Unmanaged.Win32.SafeHandles.SafeBitmapHandle</a><br />A handle to the bitmap to represent the window that *hwnd* specifies.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DwmIconicThumbnailFlags">DevCase.Interop.Unmanaged.Win32.Enums.DwmIconicThumbnailFlags</a><br />The display options for the thumbnail.</dd></dl>

#### Return Value
Type: Int32<br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd389411%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd389411%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_DwmSetIconicThumbnail">DwmSetIconicThumbnail Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />