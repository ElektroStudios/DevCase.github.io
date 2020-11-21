# StringUtil.GenerateWhiteSpacedString Method 
 

Generates a white-spaced string with the specified length.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GenerateWhiteSpacedString(
	int length
)
```

**VB**<br />
``` VB
Public Shared Function GenerateWhiteSpacedString ( 
	length As Integer
) As String
```

**VB Usage**<br />
``` VB Usage
Dim length As Integer
Dim returnValue As String

returnValue = StringUtil.GenerateWhiteSpacedString(length)
```

**C++**<br />
``` C++
public:
static String^ GenerateWhiteSpacedString(
	int length
)
```

**F#**<br />
``` F#
static member GenerateWhiteSpacedString : 
        length : int -> string 

```


#### Parameters
&nbsp;<dl><dt>length</dt><dd>Type: System.Int32<br />The white-space length.</dd></dl>

#### Return Value
Type: String<br />The white-spaced string.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim s As String = GetWhiteSpacedString(10)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_StringUtil">StringUtil Class</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />