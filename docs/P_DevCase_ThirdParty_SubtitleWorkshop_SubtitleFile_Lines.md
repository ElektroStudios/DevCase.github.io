# SubtitleFile.Lines Property 
 

Gets or sets the lines of the current subtitle file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SubtitleWorkshop">DevCase.ThirdParty.SubtitleWorkshop</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public List<SubtitleLine> Lines { get; set; }
```

**VB**<br />
``` VB
Public Property Lines As List(Of SubtitleLine)
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As SubtitleFile
Dim value As List(Of SubtitleLine)

value = instance.Lines

instance.Lines = value
```

**C++**<br />
``` C++
public:
property List<SubtitleLine^>^ Lines {
	List<SubtitleLine^>^ get ();
	void set (List<SubtitleLine^>^ value);
}
```

**F#**<br />
``` F#
member Lines : List<SubtitleLine> with get, set

```


#### Property Value
Type: List(<a href="T_DevCase_Core_Multimedia_SubtitleLine">SubtitleLine</a>)<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.SubtitleWorkshop.SubtitleFile.Lines"\]

#### Return Value
Type: List(<a href="T_DevCase_Core_Multimedia_SubtitleLine">SubtitleLine</a>)<br />The lines of the current subtitle file.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile">SubtitleFile Class</a><br /><a href="N_DevCase_ThirdParty_SubtitleWorkshop">DevCase.ThirdParty.SubtitleWorkshop Namespace</a><br />