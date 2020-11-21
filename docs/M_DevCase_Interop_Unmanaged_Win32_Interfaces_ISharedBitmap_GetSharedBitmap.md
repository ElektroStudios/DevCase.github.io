# ISharedBitmap.GetSharedBitmap Method 
 

Retrieves the bitmap contained in an <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap</a> object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
HResult GetSharedBitmap(
	out IntPtr refHandle
)
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Function GetSharedBitmap ( 
	<OutAttribute> ByRef refHandle As IntPtr
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As ISharedBitmap
Dim refHandle As IntPtr
Dim returnValue As HResult

returnValue = instance.GetSharedBitmap(refHandle)
```

**C++**<br />
``` C++
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
HResult GetSharedBitmap(
	[OutAttribute] IntPtr% refHandle
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
abstract GetSharedBitmap : 
        refHandle : IntPtr byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refHandle</dt><dd>Type: System.IntPtr<br />A pointer to a handle to the bitmap.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nf-thumbcache-isharedbitmap-getsharedbitmap" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nf-thumbcache-isharedbitmap-getsharedbitmap</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />