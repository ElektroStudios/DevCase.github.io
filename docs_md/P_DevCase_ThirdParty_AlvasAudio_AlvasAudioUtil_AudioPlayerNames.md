# AlvasAudioUtil.AudioPlayerNames Property 
 

Gets the names of the available audio player devices on the current system.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_AlvasAudio">DevCase.ThirdParty.AlvasAudio</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<string> AudioPlayerNames { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property AudioPlayerNames As ReadOnlyCollection(Of String)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As ReadOnlyCollection(Of String)

value = AlvasAudioUtil.AudioPlayerNames

```

**C++**<br />
``` C++
public:
static property ReadOnlyCollection<String^>^ AudioPlayerNames {
	ReadOnlyCollection<String^>^ get ();
}
```

**F#**<br />
``` F#
static member AudioPlayerNames : ReadOnlyCollection<string> with get

```


#### Property Value
Type: ReadOnlyCollection(String)<br />A collection containing the names of the available audio player devices on the current system.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_AlvasAudio_AlvasAudioUtil">AlvasAudioUtil Class</a><br /><a href="N_DevCase_ThirdParty_AlvasAudio">DevCase.ThirdParty.AlvasAudio Namespace</a><br />