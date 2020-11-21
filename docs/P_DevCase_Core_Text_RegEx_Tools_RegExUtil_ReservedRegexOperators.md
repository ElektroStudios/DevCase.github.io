# RegExUtil.ReservedRegexOperators Property 
 

Gets the reserved RegEx operators.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static char[] ReservedRegexOperators { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ReservedRegexOperators As Char()
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Char()

value = RegExUtil.ReservedRegexOperators

```

**C++**<br />
``` C++
public:
static property array<wchar_t>^ ReservedRegexOperators {
	array<wchar_t>^ get ();
}
```

**F#**<br />
``` F#
static member ReservedRegexOperators : char[] with get

```


#### Property Value
Type: Char[]<br />The reserved RegEx operators.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim reservedChars As String = New String(ReservedRegexOperators)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_RegEx_Tools_RegExUtil">RegExUtil Class</a><br /><a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools Namespace</a><br />