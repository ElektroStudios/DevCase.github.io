# IAudioSessionEnumerator.GetSession Method 
 

Notifies the client that the display name for the session has changed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetSession(
	int sessionCount,
	ref IAudioSessionControl refSession
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetSession ( 
	sessionCount As Integer,
	ByRef refSession As IAudioSessionControl
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionEnumerator
Dim sessionCount As Integer
Dim refSession As IAudioSessionControl
Dim returnValue As HResult

returnValue = instance.GetSession(sessionCount, 
	refSession)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetSession(
	int sessionCount, 
	IAudioSessionControl^% refSession
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetSession : 
        sessionCount : int * 
        refSession : IAudioSessionControl byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>sessionCount</dt><dd>Type: System.Int32<br />The session number. If there are n sessions, the sessions are numbered from 0 to n – 1. 

 To get the number of sessions, call the <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEnumerator_GetCount">GetCount(Int32)</a> function.</dd><dt>refSession</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl">DevCase.Interop.Unmanaged.Win32.Interfaces.IAudioSessionControl</a><br />Receives a pointer to the <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl">IAudioSessionControl</a> interface of the session object in the collection that is maintained by the session enumerator. 

 The caller must release the interface pointer.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEnumerator">IAudioSessionEnumerator Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />