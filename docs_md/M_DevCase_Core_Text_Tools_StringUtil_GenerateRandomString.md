# StringUtil.GenerateRandomString Method (Char[], Int32)
 

Generates a random string of the specified length using the specified characters.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GenerateRandomString(
	char[] charSet,
	int length
)
```

**VB**<br />
``` VB
Public Shared Function GenerateRandomString ( 
	charSet As Char(),
	length As Integer
) As String
```

**VB Usage**<br />
``` VB Usage
Dim charSet As Char()
Dim length As Integer
Dim returnValue As String

returnValue = StringUtil.GenerateRandomString(charSet, 
	length)
```

**C++**<br />
``` C++
public:
static String^ GenerateRandomString(
	array<wchar_t>^ charSet, 
	int length
)
```

**F#**<br />
``` F#
static member GenerateRandomString : 
        charSet : char[] * 
        length : int -> string 

```


#### Parameters
&nbsp;<dl><dt>charSet</dt><dd>Type: System.Char[]<br />The character set.</dd><dt>length</dt><dd>Type: System.Int32<br />The target string length.</dd></dl>

#### Return Value
Type: String<br />The resulting string.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>charSet</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = GenerateRandomString("ABCDEFGHIJKLMNOPQRSTUVWXYZ".ToCharArray(), 10)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_StringUtil">StringUtil Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_StringUtil_GenerateRandomString">GenerateRandomString Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />