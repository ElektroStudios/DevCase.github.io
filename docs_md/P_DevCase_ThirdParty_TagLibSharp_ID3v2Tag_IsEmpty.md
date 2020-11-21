# ID3v2Tag.IsEmpty Property 
 

Gets a value indicating whether the `ID3v2` tag is empty.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override bool IsEmpty { get; }
```

**VB**<br />
``` VB
Public Overrides ReadOnly Property IsEmpty As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ID3v2Tag
Dim value As Boolean

value = instance.IsEmpty

```

**C++**<br />
``` C++
public:
virtual property bool IsEmpty {
	bool get () override;
}
```

**F#**<br />
``` F#
abstract IsEmpty : bool with get
override IsEmpty : bool with get
```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the `ID3v2` tag is empty, otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_TagLibSharp_ID3v2Tag">ID3v2Tag Class</a><br /><a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp Namespace</a><br />