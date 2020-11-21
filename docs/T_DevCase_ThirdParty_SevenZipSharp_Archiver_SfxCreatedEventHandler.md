# Archiver.SfxCreatedEventHandler Delegate
 

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate void SfxCreatedEventHandler(
	Object sender,
	string filepath
)
```

**VB**<br />
``` VB
Public Delegate Sub SfxCreatedEventHandler ( 
	sender As Object,
	filepath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As New SfxCreatedEventHandler(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate void SfxCreatedEventHandler(
	Object^ sender, 
	String^ filepath
)
```

**F#**<br />
``` F#
type SfxCreatedEventHandler = 
    delegate of 
        sender : Object * 
        filepath : string -> unit
```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Object<br /></dd><dt>filepath</dt><dd>Type: System.String<br /></dd></dl>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />