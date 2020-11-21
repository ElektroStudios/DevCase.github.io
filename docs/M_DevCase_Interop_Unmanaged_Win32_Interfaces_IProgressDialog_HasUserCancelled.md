# IProgressDialog.HasUserCancelled Method 
 

Checks whether the user has canceled the operation.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
bool HasUserCancelled()
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function HasUserCancelled As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As IProgressDialog
Dim returnValue As Boolean

returnValue = instance.HasUserCancelled()
```

**C++**<br />
``` C++
[PreserveSigAttribute]
bool HasUserCancelled()
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract HasUserCancelled : unit -> bool 

```


#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the user has canceled the operation; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog">IProgressDialog Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />