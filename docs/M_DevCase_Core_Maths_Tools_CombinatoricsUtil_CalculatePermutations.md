# CombinatoricsUtil.CalculatePermutations Method (Int32, Int32, Boolean)
 

Calculates the amount of permutations that can be generated with the specified character set and string length.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static long CalculatePermutations(
	int charsetLength,
	int stringLength,
	bool allowRepetition
)
```

**VB**<br />
``` VB
Public Shared Function CalculatePermutations ( 
	charsetLength As Integer,
	stringLength As Integer,
	allowRepetition As Boolean
) As Long
```

**VB Usage**<br />
``` VB Usage
Dim charsetLength As Integer
Dim stringLength As Integer
Dim allowRepetition As Boolean
Dim returnValue As Long

returnValue = CombinatoricsUtil.CalculatePermutations(charsetLength, 
	stringLength, allowRepetition)
```

**C++**<br />
``` C++
public:
static long long CalculatePermutations(
	int charsetLength, 
	int stringLength, 
	bool allowRepetition
)
```

**F#**<br />
``` F#
static member CalculatePermutations : 
        charsetLength : int * 
        stringLength : int * 
        allowRepetition : bool -> int64 

```


#### Parameters
&nbsp;<dl><dt>charsetLength</dt><dd>Type: System.Int32<br />The length of the chararacter set. That is, the amount of elements in the set.</dd><dt>stringLength</dt><dd>Type: System.Int32<br />The desired string length of each permutation.</dd><dt>allowRepetition</dt><dd>Type: System.Boolean<br />A value indicating whether permutation repetition is allowed.</dd></dl>

#### Return Value
Type: Int64<br />The resulting amount of permutations that can be generated.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>stringLength; The value of 'stringLength' must be smaller than 'charsetLength'.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim charSet As Char() = "1234".ToCharArray()
Dim charSetLength As Integer = charSet.Length
Dim stringLength As Integer = 2
Dim result As Long = CalculatePermutations(charSetLength, stringLength, allowRepetition:=True)
Console.WriteLine(result)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Tools_CombinatoricsUtil">CombinatoricsUtil Class</a><br /><a href="Overload_DevCase_Core_Maths_Tools_CombinatoricsUtil_CalculatePermutations">CalculatePermutations Overload</a><br /><a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools Namespace</a><br />