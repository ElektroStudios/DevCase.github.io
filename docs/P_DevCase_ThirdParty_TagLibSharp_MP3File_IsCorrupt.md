# MP3File.IsCorrupt Property 
 

Gets a value indicating whether the audio file is possibly corrupt.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool IsCorrupt { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property IsCorrupt As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3File
Dim value As Boolean

value = instance.IsCorrupt

```

**C++**<br />
``` C++
public:
property bool IsCorrupt {
	bool get ();
}
```

**F#**<br />
``` F#
member IsCorrupt : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the audio file is possibly corrupt, otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_TagLibSharp_MP3File">MP3File Class</a><br /><a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp Namespace</a><br />