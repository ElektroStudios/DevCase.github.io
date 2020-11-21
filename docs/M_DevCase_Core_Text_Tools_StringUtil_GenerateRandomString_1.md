# StringUtil.GenerateRandomString Method (Char[], Int32, Int32)
 

Generates a random string within the specified string-length range using the specified characters.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GenerateRandomString(
	char[] charSet,
	int minLength,
	int maxLength
)
```

**VB**<br />
``` VB
Public Shared Function GenerateRandomString ( 
	charSet As Char(),
	minLength As Integer,
	maxLength As Integer
) As String
```

**VB Usage**<br />
``` VB Usage
Dim charSet As Char()
Dim minLength As Integer
Dim maxLength As Integer
Dim returnValue As String

returnValue = StringUtil.GenerateRandomString(charSet, 
	minLength, maxLength)
```

**C++**<br />
``` C++
public:
static String^ GenerateRandomString(
	array<wchar_t>^ charSet, 
	int minLength, 
	int maxLength
)
```

**F#**<br />
``` F#
static member GenerateRandomString : 
        charSet : char[] * 
        minLength : int * 
        maxLength : int -> string 

```


#### Parameters
&nbsp;<dl><dt>charSet</dt><dd>Type: System.Char[]<br />The character set.</dd><dt>minLength</dt><dd>Type: System.Int32<br />The minimum string length.</dd><dt>maxLength</dt><dd>Type: System.Int32<br />The maximum string length.</dd></dl>

#### Return Value
Type: String<br />The resulting string.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>charSet</td></tr><tr><td>ArgumentOutOfRangeException</td><td>minLength;Value bigger than 0 is required.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = GenerateRandomString("ABCDEFGHIJKLMNOPQRSTUVWXYZ".ToCharArray(), minLength:=3, maxLength:=5)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_StringUtil">StringUtil Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_StringUtil_GenerateRandomString">GenerateRandomString Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />