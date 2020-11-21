# MP3File.CorruptionReasons Property 
 

Gets the reasons, if any, for which the file is corrupt.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IEnumerable<string> CorruptionReasons { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property CorruptionReasons As IEnumerable(Of String)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3File
Dim value As IEnumerable(Of String)

value = instance.CorruptionReasons

```

**C++**<br />
``` C++
public:
property IEnumerable<String^>^ CorruptionReasons {
	IEnumerable<String^>^ get ();
}
```

**F#**<br />
``` F#
member CorruptionReasons : IEnumerable<string> with get

```


#### Property Value
Type: IEnumerable(String)<br />The reasons, if any, for which the file is corrupt.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_TagLibSharp_MP3File">MP3File Class</a><br /><a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp Namespace</a><br />