# RegExUtil.Patterns.HtmlTag Field
 

A pattern that matches the content of an Html enclosed tag.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public const string HtmlTag = "/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/"
```

**VB**<br />
``` VB
Public Const HtmlTag As String = "/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/"
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = RegExUtil.Patterns.HtmlTag

```

**C++**<br />
``` C++
public:
literal String^ HtmlTag = "/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/"
```

**F#**<br />
``` F#
static val mutable HtmlTag: string
```


#### Field Value
Type: String

## See Also


#### Reference
<a href="T_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns">RegExUtil.Patterns Class</a><br /><a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools Namespace</a><br />