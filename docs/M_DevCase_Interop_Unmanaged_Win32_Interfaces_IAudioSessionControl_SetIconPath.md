# IAudioSessionControl.SetIconPath Method 
 

Assigns a display icon to the current session.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult SetIconPath(
	string iconPath,
	Guid eventContext
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function SetIconPath ( 
	iconPath As String,
	eventContext As Guid
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionControl
Dim iconPath As String
Dim eventContext As Guid
Dim returnValue As HResult

returnValue = instance.SetIconPath(iconPath, 
	eventContext)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult SetIconPath(
	[InAttribute] String^ iconPath, 
	[InAttribute] Guid eventContext
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract SetIconPath : 
        iconPath : string * 
        eventContext : Guid -> HResult 

```


#### Parameters
&nbsp;<dl><dt>iconPath</dt><dd>Type: System.String<br />A string that specifies the fully qualified path of the file that contains the new icon.</dd><dt>eventContext</dt><dd>Type: System.Guid<br />A user context value that is passed to the notification callback.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl">IAudioSessionControl Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />