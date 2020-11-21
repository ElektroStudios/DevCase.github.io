# AlvasAudioUtil.AudioRecorderNames Property 
 

Gets the names of the available audio recorder devices on the current system.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_AlvasAudio">DevCase.ThirdParty.AlvasAudio</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<string> AudioRecorderNames { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property AudioRecorderNames As ReadOnlyCollection(Of String)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As ReadOnlyCollection(Of String)

value = AlvasAudioUtil.AudioRecorderNames

```

**C++**<br />
``` C++
public:
static property ReadOnlyCollection<String^>^ AudioRecorderNames {
	ReadOnlyCollection<String^>^ get ();
}
```

**F#**<br />
``` F#
static member AudioRecorderNames : ReadOnlyCollection<string> with get

```


#### Property Value
Type: ReadOnlyCollection(String)<br />A collection containing the names of the available audio recorder devices on the current system.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_AlvasAudio_AlvasAudioUtil">AlvasAudioUtil Class</a><br /><a href="N_DevCase_ThirdParty_AlvasAudio">DevCase.ThirdParty.AlvasAudio Namespace</a><br />