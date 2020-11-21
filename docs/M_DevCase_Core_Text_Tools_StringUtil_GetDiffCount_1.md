# StringUtil.GetDiffCount Method (String, String, Int32)
 

Computes the total amount of differences (insertions, deletions or substitutions) between two strings, by using the Levenshtein algorithm.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static double GetDiffCount(
	string first,
	string second,
	int limit
)
```

**VB**<br />
``` VB
Public Shared Function GetDiffCount ( 
	first As String,
	second As String,
	limit As Integer
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim first As String
Dim second As String
Dim limit As Integer
Dim returnValue As Double

returnValue = StringUtil.GetDiffCount(first, 
	second, limit)
```

**C++**<br />
``` C++
public:
static double GetDiffCount(
	String^ first, 
	String^ second, 
	int limit
)
```

**F#**<br />
``` F#
static member GetDiffCount : 
        first : string * 
        second : string * 
        limit : int -> float 

```


#### Parameters
&nbsp;<dl><dt>first</dt><dd>Type: System.String<br />The first string to compare.</dd><dt>second</dt><dd>Type: System.String<br />The second string to compare.</dd><dt>limit</dt><dd>Type: System.Int32<br />The maximum result to compute before stopping. 

 This means that the calculation can terminate early if you only care about strings with a certain similarity. 

 Set the limit to Int32 if you want to run the calculation to completion in every case.</dd></dl>

#### Return Value
Type: Double<br />The total amount of differences (insertions, deletions or substitutions) between the two strings.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td /></tr></table>

## Remarks
Wikipedia article: <a href="http://en.wikipedia.org/wiki/Levenshtein_distance" target="_blank">http://en.wikipedia.org/wiki/Levenshtein_distance</a>

 Original source-code: <a href="https://github.com/feature23/StringSimilarity.NET" target="_blank">https://github.com/feature23/StringSimilarity.NET</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim first As String = "Hello"
Dim second As String = "H3ll0"

Dim diffCount As Double = GetDiffCount(first, second, Integer.MaxValue)
Console.WriteLine($"{NameOf(diffCount)}: {diffCount}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_StringUtil">StringUtil Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_StringUtil_GetDiffCount">GetDiffCount Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />