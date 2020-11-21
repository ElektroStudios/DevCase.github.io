# IOpenControlPanel.GetCurrentView Method 
 

Gets the most recent Control Panel view.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetCurrentView(
	ref ControlPanelView refView
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetCurrentView ( 
	ByRef refView As ControlPanelView
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IOpenControlPanel
Dim refView As ControlPanelView
Dim returnValue As HResult

returnValue = instance.GetCurrentView(refView)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetCurrentView(
	ControlPanelView% refView
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetCurrentView : 
        refView : ControlPanelView byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refView</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ControlPanelView">DevCase.Interop.Unmanaged.Win32.Enums.ControlPanelView</a><br />A pointer that receives the most recent view.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IOpenControlPanel">IOpenControlPanel Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />