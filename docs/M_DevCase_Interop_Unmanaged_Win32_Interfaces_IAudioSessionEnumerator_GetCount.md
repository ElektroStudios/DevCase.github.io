# IAudioSessionEnumerator.GetCount Method 
 

Gets the total number of audio sessions that are open on the audio device.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetCount(
	ref int refSessionCount
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetCount ( 
	ByRef refSessionCount As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionEnumerator
Dim refSessionCount As Integer
Dim returnValue As HResult

returnValue = instance.GetCount(refSessionCount)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetCount(
	int% refSessionCount
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetCount : 
        refSessionCount : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refSessionCount</dt><dd>Type: System.Int32<br />Receives the total number of audio sessions.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEnumerator">IAudioSessionEnumerator Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />