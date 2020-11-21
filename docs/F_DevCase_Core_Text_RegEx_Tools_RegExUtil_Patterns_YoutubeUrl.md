# RegExUtil.Patterns.YoutubeUrl Field
 

A pattern that matches a Youtube Url. 

 For Example: 

`https://www.youtube.com/watch?v=Hzmn4-vtl5M&feature=em-uploademail`

`http://www.youtube.com/attribution_link?a=Od7TH6HFkco&u=/watch?v%3DHzmn4-vtl5M%26feature%3Dem-uploademail`

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public const string YoutubeUrl = "(?:https?:\/\/)?(?:www\.)?(?:youtu\.be\/|youtube\.com\/(?:embed\/|(attribution_link.+)?|v\/|watch\?v=|watch\?.+&v=))((\w|-){11})(?:\S+)?"
```

**VB**<br />
``` VB
Public Const YoutubeUrl As String = "(?:https?:\/\/)?(?:www\.)?(?:youtu\.be\/|youtube\.com\/(?:embed\/|(attribution_link.+)?|v\/|watch\?v=|watch\?.+&v=))((\w|-){11})(?:\S+)?"
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = RegExUtil.Patterns.YoutubeUrl

```

**C++**<br />
``` C++
public:
literal String^ YoutubeUrl = "(?:https?:\/\/)?(?:www\.)?(?:youtu\.be\/|youtube\.com\/(?:embed\/|(attribution_link.+)?|v\/|watch\?v=|watch\?.+&v=))((\w|-){11})(?:\S+)?"
```

**F#**<br />
``` F#
static val mutable YoutubeUrl: string
```


#### Field Value
Type: String

## See Also


#### Reference
<a href="T_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns">RegExUtil.Patterns Class</a><br /><a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools Namespace</a><br />