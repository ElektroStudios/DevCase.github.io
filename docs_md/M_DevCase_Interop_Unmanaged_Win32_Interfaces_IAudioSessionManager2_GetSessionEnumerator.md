# IAudioSessionManager2.GetSessionEnumerator Method 
 

Gets a pointer to the audio session enumerator object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetSessionEnumerator(
	out IAudioSessionEnumerator refSessionEnum
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetSessionEnumerator ( 
	<OutAttribute> ByRef refSessionEnum As IAudioSessionEnumerator
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionManager2
Dim refSessionEnum As IAudioSessionEnumerator
Dim returnValue As HResult

returnValue = instance.GetSessionEnumerator(refSessionEnum)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetSessionEnumerator(
	[OutAttribute] IAudioSessionEnumerator^% refSessionEnum
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetSessionEnumerator : 
        refSessionEnum : IAudioSessionEnumerator byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refSessionEnum</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEnumerator">DevCase.Interop.Unmanaged.Win32.Interfaces.IAudioSessionEnumerator</a><br />Receives an <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEnumerator">IAudioSessionEnumerator</a>.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager2">IAudioSessionManager2 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />