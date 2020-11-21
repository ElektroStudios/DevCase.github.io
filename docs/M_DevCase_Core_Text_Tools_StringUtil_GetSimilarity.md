# StringUtil.GetSimilarity Method 
 

Computes the similarity percentage between two strings, by using the Levenshtein algorithm.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static double GetSimilarity(
	string first,
	string second
)
```

**VB**<br />
``` VB
Public Shared Function GetSimilarity ( 
	first As String,
	second As String
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim first As String
Dim second As String
Dim returnValue As Double

returnValue = StringUtil.GetSimilarity(first, 
	second)
```

**C++**<br />
``` C++
public:
static double GetSimilarity(
	String^ first, 
	String^ second
)
```

**F#**<br />
``` F#
static member GetSimilarity : 
        first : string * 
        second : string -> float 

```


#### Parameters
&nbsp;<dl><dt>first</dt><dd>Type: System.String<br />The first string to compare.</dd><dt>second</dt><dd>Type: System.String<br />The second string to compare.</dd></dl>

#### Return Value
Type: Double<br />The similarity percentage between the two strings. 

 A value of 1 means the two strings are equal. 

 A value of 0 means the two strings have no similarity between.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td /></tr></table>

## Remarks
Wikipedia article: <a href="http://en.wikipedia.org/wiki/Levenshtein_distance" target="_blank">http://en.wikipedia.org/wiki/Levenshtein_distance</a>

 Original source-code: <a href="https://github.com/feature23/StringSimilarity.NET" target="_blank">https://github.com/feature23/StringSimilarity.NET</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim first As String = "Boy"
Dim second As String = "Toy"

Dim similarity As Double = GetSimilarity(first, second)
Console.WriteLine($"{NameOf(similarity)}: {similarity}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_StringUtil">StringUtil Class</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />