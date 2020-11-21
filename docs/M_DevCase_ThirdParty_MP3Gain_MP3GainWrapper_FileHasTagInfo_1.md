# MP3GainWrapper.FileHasTagInfo Method (String)
 

Determines whether the specified file contains an `APEv2` tag containing `MP3Gain` information.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Gain">DevCase.ThirdParty.MP3Gain</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool FileHasTagInfo(
	string filepath
)
```

**VB**<br />
``` VB
Public Function FileHasTagInfo ( 
	filepath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3GainWrapper
Dim filepath As String
Dim returnValue As Boolean

returnValue = instance.FileHasTagInfo(filepath)
```

**C++**<br />
``` C++
public:
bool FileHasTagInfo(
	String^ filepath
)
```

**F#**<br />
``` F#
member FileHasTagInfo : 
        filepath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The audio filepath to analyze.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified file contains an `APEv2` tag containing `MP3Gain` information, otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Gain_MP3GainWrapper">MP3GainWrapper Class</a><br /><a href="Overload_DevCase_ThirdParty_MP3Gain_MP3GainWrapper_FileHasTagInfo">FileHasTagInfo Overload</a><br /><a href="N_DevCase_ThirdParty_MP3Gain">DevCase.ThirdParty.MP3Gain Namespace</a><br />