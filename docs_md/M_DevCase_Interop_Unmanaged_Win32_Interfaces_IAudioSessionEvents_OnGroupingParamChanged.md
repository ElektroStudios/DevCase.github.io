# IAudioSessionEvents.OnGroupingParamChanged Method 
 

Notifies the client that the grouping parameter for the session has changed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult OnGroupingParamChanged(
	in Guid groupingId,
	in Guid refEventContext
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function OnGroupingParamChanged ( 
	ByRef groupingId As Guid,
	ByRef refEventContext As Guid
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionEvents
Dim groupingId As Guid
Dim refEventContext As Guid
Dim returnValue As HResult

returnValue = instance.OnGroupingParamChanged(groupingId, 
	refEventContext)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult OnGroupingParamChanged(
	[InAttribute] Guid% groupingId, 
	[InAttribute] Guid% refEventContext
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract OnGroupingParamChanged : 
        groupingId : Guid byref * 
        refEventContext : Guid byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>groupingId</dt><dd>Type: System.Guid<br />The new grouping parameter for the session.</dd><dt>refEventContext</dt><dd>Type: System.Guid<br />A user context value that is passed to the notification callback.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents">IAudioSessionEvents Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />