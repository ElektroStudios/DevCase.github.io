# ISharedBitmap.GetFormat Method 
 

Retrieves the alpha type of the bitmap image..

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
HResult GetFormat(
	out ThumbnailAlphaType refAlphaType
)
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Function GetFormat ( 
	<OutAttribute> ByRef refAlphaType As ThumbnailAlphaType
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As ISharedBitmap
Dim refAlphaType As ThumbnailAlphaType
Dim returnValue As HResult

returnValue = instance.GetFormat(refAlphaType)
```

**C++**<br />
``` C++
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
HResult GetFormat(
	[OutAttribute] ThumbnailAlphaType% refAlphaType
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
abstract GetFormat : 
        refAlphaType : ThumbnailAlphaType byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refAlphaType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThumbnailAlphaType">DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailAlphaType</a><br />When this method returns, contains a pointer to the alpha type of the bitmap image.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nf-thumbcache-isharedbitmap-getformat" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nf-thumbcache-isharedbitmap-getformat</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />