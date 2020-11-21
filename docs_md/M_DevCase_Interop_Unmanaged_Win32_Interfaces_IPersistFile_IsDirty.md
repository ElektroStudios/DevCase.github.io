# IPersistFile.IsDirty Method 
 

Determines whether an object has changed since it was last saved to its current file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
int IsDirty()
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function IsDirty As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As IPersistFile
Dim returnValue As Integer

returnValue = instance.IsDirty()
```

**C++**<br />
``` C++
[PreserveSigAttribute]
int IsDirty()
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract IsDirty : unit -> int 

```


#### Return Value
Type: Int32<br />This method returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> to indicate that the object has changed. Otherwise, it returns `S_FALSE`.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile">IPersistFile Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />