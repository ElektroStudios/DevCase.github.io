# ISimpleAudioVolume.GetMute Method 
 

Retrieves the current muting state for the audio session.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetMute(
	out bool refIsMuted
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetMute ( 
	<OutAttribute> ByRef refIsMuted As Boolean
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As ISimpleAudioVolume
Dim refIsMuted As Boolean
Dim returnValue As HResult

returnValue = instance.GetMute(refIsMuted)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetMute(
	[OutAttribute] bool% refIsMuted
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetMute : 
        refIsMuted : bool byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refIsMuted</dt><dd>Type: System.Boolean<br />Receives the muting state.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISimpleAudioVolume">ISimpleAudioVolume Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />