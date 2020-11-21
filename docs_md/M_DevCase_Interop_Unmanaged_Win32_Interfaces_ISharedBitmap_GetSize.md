# ISharedBitmap.GetSize Method 
 

Retrieves the size of the bitmap contained in an <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap</a> object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
HResult GetSize(
	out NativeSize refSize
)
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Function GetSize ( 
	<OutAttribute> ByRef refSize As NativeSize
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As ISharedBitmap
Dim refSize As NativeSize
Dim returnValue As HResult

returnValue = instance.GetSize(refSize)
```

**C++**<br />
``` C++
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
HResult GetSize(
	[OutAttribute] NativeSize% refSize
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
abstract GetSize : 
        refSize : NativeSize byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refSize</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">DevCase.Interop.Unmanaged.Win32.Structures.NativeSize</a><br />When this method returns, contains a pointer to a value that specifies the size, in pixels, of the contained bitmap.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nf-thumbcache-isharedbitmap-getsize" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nf-thumbcache-isharedbitmap-getsize</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />