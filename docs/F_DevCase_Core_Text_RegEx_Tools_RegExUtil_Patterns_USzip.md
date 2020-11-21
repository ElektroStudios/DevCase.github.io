# RegExUtil.Patterns.USzip Field
 

A pattern that matches an United States zip code with optional dash-four. 

 For Example: 



**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public const string USzip = "\d{5}(-\d{4})?"
```

**VB**<br />
``` VB
Public Const USzip As String = "\d{5}(-\d{4})?"
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = RegExUtil.Patterns.USzip

```

**C++**<br />
``` C++
public:
literal String^ USzip = "\d{5}(-\d{4})?"
```

**F#**<br />
``` F#
static val mutable USzip: string
```


#### Field Value
Type: String

## See Also


#### Reference
<a href="T_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns">RegExUtil.Patterns Class</a><br /><a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools Namespace</a><br />