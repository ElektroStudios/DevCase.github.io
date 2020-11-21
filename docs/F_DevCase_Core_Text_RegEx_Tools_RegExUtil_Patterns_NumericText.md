# RegExUtil.Patterns.NumericText Field
 

A pattern that matches numeric text, integer or decimal.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public const string NumericText = "((4\d{3})|(5[1-5]\d{2})|(6011))-?\d{4}-?\d"
```

**VB**<br />
``` VB
Public Const NumericText As String = "((4\d{3})|(5[1-5]\d{2})|(6011))-?\d{4}-?\d"
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = RegExUtil.Patterns.NumericText

```

**C++**<br />
``` C++
public:
literal String^ NumericText = "((4\d{3})|(5[1-5]\d{2})|(6011))-?\d{4}-?\d"
```

**F#**<br />
``` F#
static val mutable NumericText: string
```


#### Field Value
Type: String

## See Also


#### Reference
<a href="T_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns">RegExUtil.Patterns Class</a><br /><a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools Namespace</a><br />