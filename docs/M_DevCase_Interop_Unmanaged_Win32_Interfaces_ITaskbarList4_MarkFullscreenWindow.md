# ITaskbarList4.MarkFullscreenWindow Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult MarkFullscreenWindow(
	IntPtr hWnd,
	bool fFullscreen
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function MarkFullscreenWindow ( 
	hWnd As IntPtr,
	fFullscreen As Boolean
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As ITaskbarList4
Dim hWnd As IntPtr
Dim fFullscreen As Boolean
Dim returnValue As HResult

returnValue = instance.MarkFullscreenWindow(hWnd, 
	fFullscreen)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult MarkFullscreenWindow(
	IntPtr hWnd, 
	bool fFullscreen
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract MarkFullscreenWindow : 
        hWnd : IntPtr * 
        fFullscreen : bool -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />\[Missing <param name="hWnd"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.MarkFullscreenWindow(System.IntPtr,System.Boolean)"\]</dd><dt>fFullscreen</dt><dd>Type: System.Boolean<br />\[Missing <param name="fFullscreen"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.MarkFullscreenWindow(System.IntPtr,System.Boolean)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.MarkFullscreenWindow(System.IntPtr,System.Boolean)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ITaskbarList4">ITaskbarList4 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />