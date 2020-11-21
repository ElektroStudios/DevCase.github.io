# NativeMethods.InvertRect Method (IntPtr, NativeRectangle)
 

Inverts a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> in a window by performing a logical NOT operation on the color values for each pixel in the rectangle's interior.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool InvertRect(
	IntPtr hdc,
	in NativeRectangle refRect
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function InvertRect ( 
	hdc As IntPtr,
	ByRef refRect As NativeRectangle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hdc As IntPtr
Dim refRect As NativeRectangle
Dim returnValue As Boolean

returnValue = NativeMethods.InvertRect(hdc, 
	refRect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool InvertRect(
	IntPtr hdc, 
	[InAttribute] NativeRectangle% refRect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member InvertRect : 
        hdc : IntPtr * 
        refRect : NativeRectangle byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.IntPtr<br />A handle To the device context.</dd><dt>refRect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that contains the logical coordinates of the rectangle to be inverted.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `true` (`True` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd145007(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd145007(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_InvertRect">InvertRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />