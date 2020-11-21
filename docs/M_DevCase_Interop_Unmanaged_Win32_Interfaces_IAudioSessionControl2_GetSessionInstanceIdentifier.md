# IAudioSessionControl2.GetSessionInstanceIdentifier Method 
 

Retrieves the identifier of the audio session instance.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetSessionInstanceIdentifier(
	out string refValue
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetSessionInstanceIdentifier ( 
	<OutAttribute> ByRef refValue As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionControl2
Dim refValue As String
Dim returnValue As HResult

returnValue = instance.GetSessionInstanceIdentifier(refValue)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetSessionInstanceIdentifier(
	[OutAttribute] String^% refValue
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetSessionInstanceIdentifier : 
        refValue : string byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refValue</dt><dd>Type: System.String<br />Receives the identifier of a particular instance.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2">IAudioSessionControl2 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />