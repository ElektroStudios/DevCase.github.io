# IAudioSessionControl.GetIconPath Method 
 

Retrieves the path for the display icon for the audio session.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetIconPath(
	out string refIconPath
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetIconPath ( 
	<OutAttribute> ByRef refIconPath As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionControl
Dim refIconPath As String
Dim returnValue As HResult

returnValue = instance.GetIconPath(refIconPath)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetIconPath(
	[OutAttribute] String^% refIconPath
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetIconPath : 
        refIconPath : string byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refIconPath</dt><dd>Type: System.String<br />Receives a string that specifies the fully qualified path of the file that contains the icon.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl">IAudioSessionControl Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />