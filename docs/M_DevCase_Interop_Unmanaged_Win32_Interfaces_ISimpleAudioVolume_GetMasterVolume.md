# ISimpleAudioVolume.GetMasterVolume Method 
 

Retrieves the client volume level for the audio session.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetMasterVolume(
	out float refLevelNormalization
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetMasterVolume ( 
	<OutAttribute> ByRef refLevelNormalization As Single
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As ISimpleAudioVolume
Dim refLevelNormalization As Single
Dim returnValue As HResult

returnValue = instance.GetMasterVolume(refLevelNormalization)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetMasterVolume(
	[OutAttribute] float% refLevelNormalization
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetMasterVolume : 
        refLevelNormalization : float32 byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refLevelNormalization</dt><dd>Type: System.Single<br />Receives the volume level expressed as a normalized value between 0.0 and 1.0.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISimpleAudioVolume">ISimpleAudioVolume Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />