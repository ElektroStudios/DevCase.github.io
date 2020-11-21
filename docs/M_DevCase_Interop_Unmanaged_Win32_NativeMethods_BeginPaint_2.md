# NativeMethods.BeginPaint Method (SafeHandle, PaintStruct)
 

Prepares the specified window for painting and fills a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PaintStruct">PaintStruct</a> structure with information about the painting.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto)]
public static IntPtr BeginPaint(
	SafeHandle hWnd,
	out PaintStruct refPaint
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto>]
Public Shared Function BeginPaint ( 
	hWnd As SafeHandle,
	<OutAttribute> ByRef refPaint As PaintStruct
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim refPaint As PaintStruct
Dim returnValue As IntPtr

returnValue = NativeMethods.BeginPaint(hWnd, 
	refPaint)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto)]
static IntPtr BeginPaint(
	SafeHandle^ hWnd, 
	[InAttribute] [OutAttribute] PaintStruct% refPaint
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto)>]
static member BeginPaint : 
        hWnd : SafeHandle * 
        refPaint : PaintStruct byref -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window to be repainted.</dd><dt>refPaint</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PaintStruct">DevCase.Interop.Unmanaged.Win32.Structures.PaintStruct</a><br />Pointer to the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PaintStruct">PaintStruct</a> structure that will receive painting information.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the handle to a display device context for the specified window. 

 If the function fails, the return value is Zero, indicating that no display device context is available.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183362(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183362(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_BeginPaint">BeginPaint Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />