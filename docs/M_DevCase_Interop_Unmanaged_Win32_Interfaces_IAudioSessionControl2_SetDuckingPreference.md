# IAudioSessionControl2.SetDuckingPreference Method 
 

Enables or disables the default stream attenuation experience (auto-ducking) provided by the system.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult SetDuckingPreference(
	bool optOut
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function SetDuckingPreference ( 
	optOut As Boolean
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionControl2
Dim optOut As Boolean
Dim returnValue As HResult

returnValue = instance.SetDuckingPreference(optOut)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult SetDuckingPreference(
	bool optOut
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract SetDuckingPreference : 
        optOut : bool -> HResult 

```


#### Parameters
&nbsp;<dl><dt>optOut</dt><dd>Type: System.Boolean<br />A variable that enables or disables system auto-ducking.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2">IAudioSessionControl2 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />