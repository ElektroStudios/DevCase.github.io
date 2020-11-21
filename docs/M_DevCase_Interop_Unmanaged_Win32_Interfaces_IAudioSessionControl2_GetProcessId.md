# IAudioSessionControl2.GetProcessId Method 
 

Retrieves the process identifier of the audio session.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetProcessId(
	out uint refValue
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetProcessId ( 
	<OutAttribute> ByRef refValue As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionControl2
Dim refValue As UInteger
Dim returnValue As HResult

returnValue = instance.GetProcessId(refValue)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetProcessId(
	[OutAttribute] unsigned int% refValue
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetProcessId : 
        refValue : uint32 byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refValue</dt><dd>Type: System.UInt32<br />Receives the process identifier of the audio session.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2">IAudioSessionControl2 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />