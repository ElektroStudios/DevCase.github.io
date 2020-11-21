# CombinatoricsUtil.PermuteCharacters Method 
 

Generates all the permutations of the specified string-length using the given character set.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<string> PermuteCharacters(
	IEnumerable<char> charSet,
	int length,
	bool allowRepetition
)
```

**VB**<br />
``` VB
Public Shared Function PermuteCharacters ( 
	charSet As IEnumerable(Of Char),
	length As Integer,
	allowRepetition As Boolean
) As IEnumerable(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim charSet As IEnumerable(Of Char)
Dim length As Integer
Dim allowRepetition As Boolean
Dim returnValue As IEnumerable(Of String)

returnValue = CombinatoricsUtil.PermuteCharacters(charSet, 
	length, allowRepetition)
```

**C++**<br />
``` C++
public:
static IEnumerable<String^>^ PermuteCharacters(
	IEnumerable<wchar_t>^ charSet, 
	int length, 
	bool allowRepetition
)
```

**F#**<br />
``` F#
static member PermuteCharacters : 
        charSet : IEnumerable<char> * 
        length : int * 
        allowRepetition : bool -> IEnumerable<string> 

```


#### Parameters
&nbsp;<dl><dt>charSet</dt><dd>Type: System.Collections.Generic.IEnumerable(Char)<br />The character set.</dd><dt>length</dt><dd>Type: System.Int32<br />The permuation length.</dd><dt>allowRepetition</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), character repetition is allowed when generating the permutations.</dd></dl>

#### Return Value
Type: IEnumerable(String)<br />An IEnumerable(T) that contains the resulting permutations.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Char-set contains duplicated characters.;charSet</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim permutations As IEnumerable(Of String) = PermuteCharacters("0123456789", 3, allowRepetition:=True)
For Each value As String In permutations
    Debug.WriteLine(value)
Next value
```


## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Tools_CombinatoricsUtil">CombinatoricsUtil Class</a><br /><a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools Namespace</a><br />