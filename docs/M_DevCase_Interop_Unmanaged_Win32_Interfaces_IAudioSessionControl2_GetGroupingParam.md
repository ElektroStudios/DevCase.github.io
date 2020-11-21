# IAudioSessionControl2.GetGroupingParam Method 
 

Retrieves the grouping parameter of the audio session.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetGroupingParam(
	out Guid refGroupingId
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetGroupingParam ( 
	<OutAttribute> ByRef refGroupingId As Guid
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionControl2
Dim refGroupingId As Guid
Dim returnValue As HResult

returnValue = instance.GetGroupingParam(refGroupingId)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetGroupingParam(
	[OutAttribute] Guid% refGroupingId
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetGroupingParam : 
        refGroupingId : Guid byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refGroupingId</dt><dd>Type: System.Guid<br />Receives the grouping parameter ID.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2">IAudioSessionControl2 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />