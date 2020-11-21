# IDropSource.QueryContinueDrag Method 
 

Determines whether a drag-and-drop operation should be continued, canceled, or completed. 

 You do not call this method directly. The OLE DoDragDrop function calls this method during a drag-and-drop operation.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult QueryContinueDrag(
	bool escapePressed,
	uint keyState
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function QueryContinueDrag ( 
	escapePressed As Boolean,
	keyState As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IDropSource
Dim escapePressed As Boolean
Dim keyState As UInteger
Dim returnValue As HResult

returnValue = instance.QueryContinueDrag(escapePressed, 
	keyState)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult QueryContinueDrag(
	bool escapePressed, 
	unsigned int keyState
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract QueryContinueDrag : 
        escapePressed : bool * 
        keyState : uint32 -> HResult 

```


#### Parameters
&nbsp;<dl><dt>escapePressed</dt><dd>Type: System.Boolean<br />Indicates whether the `Escape` key has been pressed since the previous call to QueryContinueDrag(Boolean, UInt32) or to DoDragDrop function if this is the first call to QueryContinueDrag(Boolean, UInt32). 

 A `true` (`True` in Visual Basic) value indicates the end user has pressed the escape key; a `false` (`False` in Visual Basic) value indicates it has not been pressed.</dd><dt>keyState</dt><dd>Type: System.UInt32<br />The current state of the keyboard modifier keys on the keyboard. Possible values can be a combination of any of the flags: MK_CONTROL, MK_SHIFT, MK_ALT, MK_BUTTON, MK_LBUTTON, MK_MBUTTON, and MK_RBUTTON.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br /><a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>: 

 The drag operation should continue. This result occurs if no errors are detected, the mouse button starting the drag-and-drop operation has not been released, and the Esc key has not been detected. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">DRAGDROP_S_DROP</a>: 

 The drop operation should occur completing the drag operation. This result occurs if *keyState* indicates that the key that started the drag-and-drop operation has been released. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">DRAGDROP_S_CANCEL</a>: 

 The drag operation should be canceled with no drop operation occurring. This result occurs if *escapePressed* is `true` (`True` in Visual Basic), indicating the `Escape` key has been pressed.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IDropSource">IDropSource Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />