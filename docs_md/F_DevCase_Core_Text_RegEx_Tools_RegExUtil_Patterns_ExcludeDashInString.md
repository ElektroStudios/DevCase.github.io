# RegExUtil.Patterns.ExcludeDashInString Field
 

A pattern that matches any string that does not contain a dash character (-). 

 For Example: 

 Match: `"Everybody"`

 Don't Match: `"Every-body"`

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public const string ExcludeDashInString = "^([^-]*)$"
```

**VB**<br />
``` VB
Public Const ExcludeDashInString As String = "^([^-]*)$"
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = RegExUtil.Patterns.ExcludeDashInString

```

**C++**<br />
``` C++
public:
literal String^ ExcludeDashInString = "^([^-]*)$"
```

**F#**<br />
``` F#
static val mutable ExcludeDashInString: string
```


#### Field Value
Type: String

## See Also


#### Reference
<a href="T_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns">RegExUtil.Patterns Class</a><br /><a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools Namespace</a><br />