# ITaskbarList4.SetOverlayIcon Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult SetOverlayIcon(
	IntPtr hWnd,
	IntPtr hIcon,
	string pszDescription
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function SetOverlayIcon ( 
	hWnd As IntPtr,
	hIcon As IntPtr,
	pszDescription As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As ITaskbarList4
Dim hWnd As IntPtr
Dim hIcon As IntPtr
Dim pszDescription As String
Dim returnValue As HResult

returnValue = instance.SetOverlayIcon(hWnd, 
	hIcon, pszDescription)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult SetOverlayIcon(
	IntPtr hWnd, 
	IntPtr hIcon, 
	String^ pszDescription
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract SetOverlayIcon : 
        hWnd : IntPtr * 
        hIcon : IntPtr * 
        pszDescription : string -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />\[Missing <param name="hWnd"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetOverlayIcon(System.IntPtr,System.IntPtr,System.String)"\]</dd><dt>hIcon</dt><dd>Type: System.IntPtr<br />\[Missing <param name="hIcon"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetOverlayIcon(System.IntPtr,System.IntPtr,System.String)"\]</dd><dt>pszDescription</dt><dd>Type: System.String<br />\[Missing <param name="pszDescription"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetOverlayIcon(System.IntPtr,System.IntPtr,System.String)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetOverlayIcon(System.IntPtr,System.IntPtr,System.String)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ITaskbarList4">ITaskbarList4 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />