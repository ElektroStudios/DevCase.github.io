# IDropSource.GiveFeedback Method 
 

Enables a source application to give visual feedback to the end user during a drag-and-drop operation by providing the DoDragDrop function with an enumeration value specifying the visual effect.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GiveFeedback(
	DragDropEffects effect
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GiveFeedback ( 
	effect As DragDropEffects
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IDropSource
Dim effect As DragDropEffects
Dim returnValue As HResult

returnValue = instance.GiveFeedback(effect)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GiveFeedback(
	DragDropEffects effect
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GiveFeedback : 
        effect : DragDropEffects -> HResult 

```


#### Parameters
&nbsp;<dl><dt>effect</dt><dd>Type: System.Windows.Forms.DragDropEffects<br />The DragDropEffects value returned by the most recent call to IDropTarget.DragEnter, IDropTarget.DragOver, or IDropTarget.DragLeave.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If successful, returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. 

 If not successful, returns a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IDropSource">IDropSource Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />