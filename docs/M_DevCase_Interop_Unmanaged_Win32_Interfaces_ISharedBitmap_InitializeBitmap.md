# ISharedBitmap.InitializeBitmap Method 
 

Initializes a new <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap</a> object with a given bitmap.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
HResult InitializeBitmap(
	IntPtr handle,
	ThumbnailAlphaType alphaType
)
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Function InitializeBitmap ( 
	handle As IntPtr,
	alphaType As ThumbnailAlphaType
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As ISharedBitmap
Dim handle As IntPtr
Dim alphaType As ThumbnailAlphaType
Dim returnValue As HResult

returnValue = instance.InitializeBitmap(handle, 
	alphaType)
```

**C++**<br />
``` C++
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
HResult InitializeBitmap(
	[InAttribute] IntPtr handle, 
	[InAttribute] ThumbnailAlphaType alphaType
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
abstract InitializeBitmap : 
        handle : IntPtr * 
        alphaType : ThumbnailAlphaType -> HResult 

```


#### Parameters
&nbsp;<dl><dt>handle</dt><dd>Type: System.IntPtr<br />A handle to the bitmap with which to initialize a new <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap</a> object. 

 The bitmap must be a DIB.</dd><dt>alphaType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThumbnailAlphaType">DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailAlphaType</a><br />The alpha type of the bitmap image.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nf-thumbcache-isharedbitmap-initializebitmap" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nf-thumbcache-isharedbitmap-initializebitmap</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />