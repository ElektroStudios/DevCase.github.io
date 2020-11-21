# RegExUtil.Patterns.ExcludeDashInFilename Field
 

A pattern that matches any filename that does not contain a dash character (-). 

 For Example: 

 Match: `"Everybody.mp3"`

 Don't Match: `"Every-body.mp3"`

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public const string ExcludeDashInFilename = "^([^-]*\.+(?<fileextension>([A-z\d])+))$"
```

**VB**<br />
``` VB
Public Const ExcludeDashInFilename As String = "^([^-]*\.+(?<fileextension>([A-z\d])+))$"
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = RegExUtil.Patterns.ExcludeDashInFilename

```

**C++**<br />
``` C++
public:
literal String^ ExcludeDashInFilename = "^([^-]*\.+(?<fileextension>([A-z\d])+))$"
```

**F#**<br />
``` F#
static val mutable ExcludeDashInFilename: string
```


#### Field Value
Type: String

## See Also


#### Reference
<a href="T_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns">RegExUtil.Patterns Class</a><br /><a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools Namespace</a><br />