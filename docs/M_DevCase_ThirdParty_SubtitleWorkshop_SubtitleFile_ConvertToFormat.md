# SubtitleFile.ConvertToFormat Method (SubtitleFormat, Single, String)
 

Converts the current subtitle file to other subtitle format.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SubtitleWorkshop">DevCase.ThirdParty.SubtitleWorkshop</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool ConvertToFormat(
	SubtitleFormat subtitleFormat,
	float fps,
	string filepath
)
```

**VB**<br />
``` VB
Public Function ConvertToFormat ( 
	subtitleFormat As SubtitleFormat,
	fps As Single,
	filepath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As SubtitleFile
Dim subtitleFormat As SubtitleFormat
Dim fps As Single
Dim filepath As String
Dim returnValue As Boolean

returnValue = instance.ConvertToFormat(subtitleFormat, 
	fps, filepath)
```

**C++**<br />
``` C++
public:
bool ConvertToFormat(
	SubtitleFormat subtitleFormat, 
	float fps, 
	String^ filepath
)
```

**F#**<br />
``` F#
member ConvertToFormat : 
        subtitleFormat : SubtitleFormat * 
        fps : float32 * 
        filepath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>subtitleFormat</dt><dd>Type: <a href="T_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFormat">DevCase.ThirdParty.SubtitleWorkshop.SubtitleFormat</a><br />The target subtitle format.</dd><dt>fps</dt><dd>Type: System.Single<br />The target FPS.</dd><dt>filepath</dt><dd>Type: System.String<br />The target subtitle filepath.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the operation success, otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile">SubtitleFile Class</a><br /><a href="Overload_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile_ConvertToFormat">ConvertToFormat Overload</a><br /><a href="N_DevCase_ThirdParty_SubtitleWorkshop">DevCase.ThirdParty.SubtitleWorkshop Namespace</a><br />