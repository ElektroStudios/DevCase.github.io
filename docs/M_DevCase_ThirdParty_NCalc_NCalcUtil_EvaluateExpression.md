# NCalcUtil.EvaluateExpression Method 
 

Evaluates an Arithmetic expression then returns the resulting value.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_NCalc">DevCase.ThirdParty.NCalc</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static decimal EvaluateExpression(
	string expr
)
```

**VB**<br />
``` VB
Public Shared Function EvaluateExpression ( 
	expr As String
) As Decimal
```

**VB Usage**<br />
``` VB Usage
Dim expr As String
Dim returnValue As Decimal

returnValue = NCalcUtil.EvaluateExpression(expr)
```

**C++**<br />
``` C++
public:
static Decimal EvaluateExpression(
	String^ expr
)
```

**F#**<br />
``` F#
static member EvaluateExpression : 
        expr : string -> decimal 

```


#### Parameters
&nbsp;<dl><dt>expr</dt><dd>Type: System.String<br />\[Missing <param name="expr"/> documentation for "M:DevCase.ThirdParty.NCalc.NCalcUtil.EvaluateExpression(System.String)"\]</dd></dl>

#### Return Value
Type: Decimal<br />The resulting value.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>EvaluationException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim expr As String = "(1 + (2 - 2)) * (100 / 2.5)" ' = 40
Dim result As Decmial = EvaluateExpression(expr)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_NCalc_NCalcUtil">NCalcUtil Class</a><br /><a href="N_DevCase_ThirdParty_NCalc">DevCase.ThirdParty.NCalc Namespace</a><br />