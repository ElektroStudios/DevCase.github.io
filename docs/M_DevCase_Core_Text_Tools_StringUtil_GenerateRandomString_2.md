# StringUtil.GenerateRandomString Method (Int32)
 

Generates a random alpha-numeric string of the specified length.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GenerateRandomString(
	int length
)
```

**VB**<br />
``` VB
Public Shared Function GenerateRandomString ( 
	length As Integer
) As String
```

**VB Usage**<br />
``` VB Usage
Dim length As Integer
Dim returnValue As String

returnValue = StringUtil.GenerateRandomString(length)
```

**C++**<br />
``` C++
public:
static String^ GenerateRandomString(
	int length
)
```

**F#**<br />
``` F#
static member GenerateRandomString : 
        length : int -> string 

```


#### Parameters
&nbsp;<dl><dt>length</dt><dd>Type: System.Int32<br />The target string length.</dd></dl>

#### Return Value
Type: String<br />The resulting string.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = GenerateRandomString(10)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_StringUtil">StringUtil Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_StringUtil_GenerateRandomString">GenerateRandomString Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />