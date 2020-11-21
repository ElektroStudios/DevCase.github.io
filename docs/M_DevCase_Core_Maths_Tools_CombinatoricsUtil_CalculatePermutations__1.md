# CombinatoricsUtil.CalculatePermutations(*T*) Method (IEnumerable(*T*), Int32, Boolean)
 

Calculates the amount of permutations that can be generated with the specified collection and string length.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static long CalculatePermutations<T>(
	IEnumerable<T> collection,
	int stringLength,
	bool allowRepetition
)

```

**VB**<br />
``` VB
Public Shared Function CalculatePermutations(Of T) ( 
	collection As IEnumerable(Of T),
	stringLength As Integer,
	allowRepetition As Boolean
) As Long
```

**VB Usage**<br />
``` VB Usage
Dim collection As IEnumerable(Of T)
Dim stringLength As Integer
Dim allowRepetition As Boolean
Dim returnValue As Long

returnValue = CombinatoricsUtil.CalculatePermutations(collection, 
	stringLength, allowRepetition)
```

**C++**<br />
``` C++
public:
generic<typename T>
static long long CalculatePermutations(
	IEnumerable<T>^ collection, 
	int stringLength, 
	bool allowRepetition
)
```

**F#**<br />
``` F#
static member CalculatePermutations : 
        collection : IEnumerable<'T> * 
        stringLength : int * 
        allowRepetition : bool -> int64 

```


#### Parameters
&nbsp;<dl><dt>collection</dt><dd>Type: System.Collections.Generic.IEnumerable(*T*)<br />An IEnumerable(T) that contains the elements to permute.</dd><dt>stringLength</dt><dd>Type: System.Int32<br />The desired string length of each permutation.</dd><dt>allowRepetition</dt><dd>Type: System.Boolean<br />A value indicating whether permutation repetition is allowed.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Maths.Tools.CombinatoricsUtil.CalculatePermutations``1(System.Collections.Generic.IEnumerable{``0},System.Int32,System.Boolean)"\]</dd></dl>

#### Return Value
Type: Int64<br />The resulting amount of permutations that can be generated.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim collection As Char() = "1234".ToCharArray()
Dim stringLength As Integer = 2
Dim result As Long = CalculatePermutations(collection, stringLength, allowRepetition:=True)
Console.WriteLine(result)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Tools_CombinatoricsUtil">CombinatoricsUtil Class</a><br /><a href="Overload_DevCase_Core_Maths_Tools_CombinatoricsUtil_CalculatePermutations">CalculatePermutations Overload</a><br /><a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools Namespace</a><br />