# IPropertyStore.Commit Method 
 

Saves a property change.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult Commit()
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function Commit As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IPropertyStore
Dim returnValue As HResult

returnValue = instance.Commit()
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult Commit()
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract Commit : unit -> HResult 

```


#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> or INPLACE_S_TRUNCATED. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPropertyStore">IPropertyStore Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />