# StringUtil.GenerateRandomString Method (Int32, Int32)
 

Generates a random alpha-numeric string within the specified string-length range.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GenerateRandomString(
	int minLength,
	int maxLength
)
```

**VB**<br />
``` VB
Public Shared Function GenerateRandomString ( 
	minLength As Integer,
	maxLength As Integer
) As String
```

**VB Usage**<br />
``` VB Usage
Dim minLength As Integer
Dim maxLength As Integer
Dim returnValue As String

returnValue = StringUtil.GenerateRandomString(minLength, 
	maxLength)
```

**C++**<br />
``` C++
public:
static String^ GenerateRandomString(
	int minLength, 
	int maxLength
)
```

**F#**<br />
``` F#
static member GenerateRandomString : 
        minLength : int * 
        maxLength : int -> string 

```


#### Parameters
&nbsp;<dl><dt>minLength</dt><dd>Type: System.Int32<br />The minimum string length.</dd><dt>maxLength</dt><dd>Type: System.Int32<br />The maximum string length.</dd></dl>

#### Return Value
Type: String<br />The resulting string.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>charSet</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = GenerateRandomString(minLength:=3, maxLength:=5)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_StringUtil">StringUtil Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_StringUtil_GenerateRandomString">GenerateRandomString Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />