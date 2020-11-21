# NCalcUtil.ValidateExpression Method 
 

Validates the syntax of an Arithmetic expression.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_NCalc">DevCase.ThirdParty.NCalc</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

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

returnValue = NCalcUtil.ValidateExpression(expr)
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
&nbsp;<dl><dt>expr</dt><dd>Type: System.String<br />\[Missing <param name="expr"/> documentation for "M:DevCase.ThirdParty.NCalc.NCalcUtil.ValidateExpression(System.String)"\]</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the Arithmetic expression does not contain syntax errors, otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim expr As String = "1 + ABC"
Dim isValid As Boolean = ValidateExpression(expr)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_NCalc_NCalcUtil">NCalcUtil Class</a><br /><a href="N_DevCase_ThirdParty_NCalc">DevCase.ThirdParty.NCalc Namespace</a><br />