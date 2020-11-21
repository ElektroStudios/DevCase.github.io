# NativeMethods.GetClipBox Method (SafeHandle, NativeRectangle)
 

Retrieves the dimensions of the tightest bounding rectangle that can be drawn around the current visible area on the device. 

 The visible area is defined by the current clipping region or clip path, as well as any overlapping windows.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static ClipBoxComplexity GetClipBox(
	SafeHandle hdc,
	ref NativeRectangle refRect
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function GetClipBox ( 
	hdc As SafeHandle,
	ByRef refRect As NativeRectangle
) As ClipBoxComplexity
```

**VB Usage**<br />
``` VB Usage
Dim hdc As SafeHandle
Dim refRect As NativeRectangle
Dim returnValue As ClipBoxComplexity

returnValue = NativeMethods.GetClipBox(hdc, 
	refRect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static ClipBoxComplexity GetClipBox(
	SafeHandle^ hdc, 
	NativeRectangle% refRect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member GetClipBox : 
        hdc : SafeHandle * 
        refRect : NativeRectangle byref -> ClipBoxComplexity 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the device context.</dd><dt>refRect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that is to receive the rectangle dimensions, in logical units.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ClipBoxComplexity">ClipBoxComplexity</a><br />If the function succeeds, the return value specifies the clipping box's complexity. 



## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd144865%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd144865%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetClipBox">GetClipBox Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />