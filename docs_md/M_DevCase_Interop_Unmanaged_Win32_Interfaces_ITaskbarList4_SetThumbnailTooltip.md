# ITaskbarList4.SetThumbnailTooltip Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult SetThumbnailTooltip(
	IntPtr hWnd,
	string pszTip
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function SetThumbnailTooltip ( 
	hWnd As IntPtr,
	pszTip As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As ITaskbarList4
Dim hWnd As IntPtr
Dim pszTip As String
Dim returnValue As HResult

returnValue = instance.SetThumbnailTooltip(hWnd, 
	pszTip)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult SetThumbnailTooltip(
	IntPtr hWnd, 
	String^ pszTip
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract SetThumbnailTooltip : 
        hWnd : IntPtr * 
        pszTip : string -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />\[Missing <param name="hWnd"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetThumbnailTooltip(System.IntPtr,System.String)"\]</dd><dt>pszTip</dt><dd>Type: System.String<br />\[Missing <param name="pszTip"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetThumbnailTooltip(System.IntPtr,System.String)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetThumbnailTooltip(System.IntPtr,System.String)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ITaskbarList4">ITaskbarList4 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />