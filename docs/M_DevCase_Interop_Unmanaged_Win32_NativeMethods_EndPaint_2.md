# NativeMethods.EndPaint Method (SafeHandle, PaintStruct)
 

Marks the end of painting in the specified window. 

 This function is required for each call to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BeginPaint">BeginPaint(IntPtr, PaintStruct)</a> function, but only after painting is complete.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto)]
public static bool EndPaint(
	SafeHandle hWnd,
	ref PaintStruct refPaint
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto>]
Public Shared Function EndPaint ( 
	hWnd As SafeHandle,
	ByRef refPaint As PaintStruct
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim refPaint As PaintStruct
Dim returnValue As Boolean

returnValue = NativeMethods.EndPaint(hWnd, 
	refPaint)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto)]
static bool EndPaint(
	SafeHandle^ hWnd, 
	PaintStruct% refPaint
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto)>]
static member EndPaint : 
        hWnd : SafeHandle * 
        refPaint : PaintStruct byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window that has been repainted.</dd><dt>refPaint</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PaintStruct">DevCase.Interop.Unmanaged.Win32.Structures.PaintStruct</a><br />Pointer to the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PaintStruct">PaintStruct</a> structure that contains the painting information retrieved by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BeginPaint">BeginPaint(IntPtr, PaintStruct)</a> function.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is the handle to a display device context for the specified window. 

 If the function fails, the return value is Zero, indicating that no display device context is available.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd162598(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd162598(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_EndPaint">EndPaint Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />