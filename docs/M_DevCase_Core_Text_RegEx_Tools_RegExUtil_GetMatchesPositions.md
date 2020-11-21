# RegExUtil.GetMatchesPositions Method (Regex, String)
 

Gets a friendlly collection of all the RegEx matches being at group index Zero, and their matches positions.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<MatchPositionInfo> GetMatchesPositions(
	Regex regEx,
	string text
)
```

**VB**<br />
``` VB
Public Shared Function GetMatchesPositions ( 
	regEx As Regex,
	text As String
) As IEnumerable(Of MatchPositionInfo)
```

**VB Usage**<br />
``` VB Usage
Dim regEx As Regex
Dim text As String
Dim returnValue As IEnumerable(Of MatchPositionInfo)

returnValue = RegExUtil.GetMatchesPositions(regEx, 
	text)
```

**C++**<br />
``` C++
public:
static IEnumerable<MatchPositionInfo>^ GetMatchesPositions(
	Regex^ regEx, 
	String^ text
)
```

**F#**<br />
``` F#
static member GetMatchesPositions : 
        regEx : Regex * 
        text : string -> IEnumerable<MatchPositionInfo> 

```


#### Parameters
&nbsp;<dl><dt>regEx</dt><dd>Type: System.Text.RegularExpressions.Regex<br />The RegEx pattern.</dd><dt>text</dt><dd>Type: System.String<br />The text where to test the matches.</dd></dl>

#### Return Value
Type: IEnumerable(<a href="T_DevCase_Core_Text_RegEx_MatchPositionInfo">MatchPositionInfo</a>)<br />An IEnumerable(T) that contains the RegEx matches and their positions.

## Examples
This is a code example. 
**VB**<br />
``` VB
Sub Test()

    Dim regExpr As New Regex("Dog(s)?", RegexOptions.IgnoreCase)

    Dim text As String = "One Dog!, Two Dogs!, three Dogs!"
    RichTextBox1.Text = text

    Dim matchesPos As IEnumerable(Of MatchPositionInfo) = GetMatchesPositions(regExpr, text)

    For Each matchPos As MatchPositionInfo In matchesPos

        Console.WriteLine(text.Substring(matchPos.StartIndex, matchPos.Length))

        With RichTextBox1
            .SelectionStart = matchPos.StartIndex
            .SelectionLength = matchPos.Length
            .SelectionBackColor = Color.IndianRed
            .SelectionColor = Color.WhiteSmoke
            .SelectionFont = New Font(RichTextBox1.Font.Name, RichTextBox1.Font.SizeInPoints, FontStyle.Bold)
        End With

    Next matchPos

    With RichTextBox1
        .SelectionStart = 0
        .SelectionLength = 0
    End With

End Sub
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_RegEx_Tools_RegExUtil">RegExUtil Class</a><br /><a href="Overload_DevCase_Core_Text_RegEx_Tools_RegExUtil_GetMatchesPositions">GetMatchesPositions Overload</a><br /><a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools Namespace</a><br />