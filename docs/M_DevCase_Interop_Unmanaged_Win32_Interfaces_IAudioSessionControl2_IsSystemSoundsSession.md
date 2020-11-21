# IAudioSessionControl2.IsSystemSoundsSession Method 
 

Indicates whether the session is a system sounds session.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult IsSystemSoundsSession()
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function IsSystemSoundsSession As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionControl2
Dim returnValue As HResult

returnValue = instance.IsSystemSoundsSession()
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult IsSystemSoundsSession()
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract IsSystemSoundsSession : unit -> HResult 

```


#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if the session is a system sounds session. 

 Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_FALSE</a> if the session is not a system sounds session.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2">IAudioSessionControl2 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />