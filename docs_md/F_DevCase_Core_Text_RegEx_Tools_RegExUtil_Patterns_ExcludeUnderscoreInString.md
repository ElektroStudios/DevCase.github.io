# RegExUtil.Patterns.ExcludeUnderscoreInString Field
 

A pattern that matches any string that does not contain a underscore character (_). 

 For Example: 

 Match: `"Everybody"`

 Don't Match: `"Every_body"`

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public const string ExcludeUnderscoreInString = "^([^_]*)$"
```

**VB**<br />
``` VB
Public Const ExcludeUnderscoreInString As String = "^([^_]*)$"
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = RegExUtil.Patterns.ExcludeUnderscoreInString

```

**C++**<br />
``` C++
public:
literal String^ ExcludeUnderscoreInString = "^([^_]*)$"
```

**F#**<br />
``` F#
static val mutable ExcludeUnderscoreInString: string
```


#### Field Value
Type: String

## See Also


#### Reference
<a href="T_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns">RegExUtil.Patterns Class</a><br /><a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools Namespace</a><br />