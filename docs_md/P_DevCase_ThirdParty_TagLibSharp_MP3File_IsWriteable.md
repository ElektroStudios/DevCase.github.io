# MP3File.IsWriteable Property 
 

Gets a value indicating whether the tags can be written or not in the audio file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool IsWriteable { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property IsWriteable As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3File
Dim value As Boolean

value = instance.IsWriteable

```

**C++**<br />
``` C++
public:
property bool IsWriteable {
	bool get ();
}
```

**F#**<br />
``` F#
member IsWriteable : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the tags can be written in the audio file, otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_TagLibSharp_MP3File">MP3File Class</a><br /><a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp Namespace</a><br />