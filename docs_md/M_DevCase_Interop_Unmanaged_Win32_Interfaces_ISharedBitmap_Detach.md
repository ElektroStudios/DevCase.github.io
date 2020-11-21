# ISharedBitmap.Detach Method 
 

Retrieves the bitmap contained in an <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap</a> object, and returns a copy if the contained bitmap resides in shared memory. 

 After calling this method the bitmap is no longer associated with this <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap</a> object and you cannot call <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap_GetSharedBitmap">GetSharedBitmap(IntPtr)</a> or Detach(IntPtr) on it again.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
HResult Detach(
	out IntPtr refHandle
)
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Function Detach ( 
	<OutAttribute> ByRef refHandle As IntPtr
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As ISharedBitmap
Dim refHandle As IntPtr
Dim returnValue As HResult

returnValue = instance.Detach(refHandle)
```

**C++**<br />
``` C++
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
HResult Detach(
	[OutAttribute] IntPtr% refHandle
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
abstract Detach : 
        refHandle : IntPtr byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refHandle</dt><dd>Type: System.IntPtr<br />When this method returns, contains a pointer to a handle to the bitmap to retrieve.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nf-thumbcache-isharedbitmap-detach" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nf-thumbcache-isharedbitmap-detach</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />