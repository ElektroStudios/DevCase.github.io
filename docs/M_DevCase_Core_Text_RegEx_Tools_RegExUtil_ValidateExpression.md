# RegExUtil.ValidateExpression Method 
 

Validates the specified regular expression.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ValidateExpression(
	string expr
)
```

**VB**<br />
``` VB
Public Shared Function ValidateExpression ( 
	expr As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim expr As String
Dim returnValue As Boolean

returnValue = RegExUtil.ValidateExpression(expr)
```

**C++**<br />
``` C++
public:
static bool ValidateExpression(
	String^ expr
)
```

**F#**<br />
``` F#
static member ValidateExpression : 
        expr : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>expr</dt><dd>Type: System.String<br />The regular expression.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if pattern validation success, `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim success As Boolean = ValidateExpression("[0-9]++") ' False
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_RegEx_Tools_RegExUtil">RegExUtil Class</a><br /><a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools Namespace</a><br />