# StringExtensions.GetGroupingInfo Method 
 

Gets info about the grooupings of a String.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static GroupingInfo GetGroupingInfo(
	this string sender,
	List<GroupingCharsInfo> groupingChars = null
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetGroupingInfo ( 
	sender As String,
	Optional groupingChars As List(Of GroupingCharsInfo) = Nothing
) As GroupingInfo
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim groupingChars As List(Of GroupingCharsInfo)
Dim returnValue As GroupingInfo

returnValue = sender.GetGroupingInfo(groupingChars)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static GroupingInfo^ GetGroupingInfo(
	String^ sender, 
	List<GroupingCharsInfo^>^ groupingChars = nullptr
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetGroupingInfo : 
        sender : string * 
        ?groupingChars : List<GroupingCharsInfo> 
(* Defaults:
        let _groupingChars = defaultArg groupingChars null
*)
-> GroupingInfo 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>groupingChars (Optional)</dt><dd>Type: System.Collections.Generic.List(<a href="T_DevCase_Core_Text_GroupingCharsInfo">GroupingCharsInfo</a>)<br />The grouping chars. If this value is a null reference (`Nothing` in Visual Basic), the default grouping characters are used instead. The default grouping characters are: "()", "{}" and "[]".</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Text_GroupingInfo">GroupingInfo</a><br />A <a href="T_DevCase_Core_Text_GroupingInfo">GroupingInfo</a> object that contains the grouping info.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>groupingChars</td></tr><tr><td>ArgumentException</td><td>An aperture character cannot be the same as a closure character.;groupingChars</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Private Sub Test()

    Dim source As String() =
        {
            "This is (good)",
            "This (is ({good}))",
            "This is good",
            "This is (bad))",
            "This is (bad",
            "This is bad)",
            "This is bad)("
        }

    Dim groupingCharList As New List(Of GroupingCharsInfo) From
        {
            New GroupingCharsInfo(apertureChar:="("c, closureChar:=")"c),
            New GroupingCharsInfo(apertureChar:="{"c, closureChar:="}"c),
            New GroupingCharsInfo(apertureChar:="["c, closureChar:="]"c)
        }

    For Each str As String In source

        Dim info As GroupingInfo = str.GetGroupingInfo(groupingCharList)

        Dim sb As New Global.System.Text.StringBuilder
        With sb

            .AppendLine(String.Format("Input String: {0}", info.Source))
            .AppendLine()

            .Append("Grouping Characters: ")
            For Each charInfo As GroupingCharsInfo In groupingCharList
                .Append(String.Format("{0}{1} ", charInfo.Aperture, charInfo.Closure))
            Next charInfo
            .AppendLine()

            .AppendLine(String.Format("String has closed agrupations?: {0}", info.HasClosedGroups))
            .AppendLine(String.Format("String has opened agrupations?: {0}", info.HasOpenGroups))
            .AppendLine()

            .AppendLine(String.Format("Closed Agrupations Count: {0}", info.GroupsClosedCount))
            .AppendLine(String.Format("Opened Agrupations Count: {0}", info.GroupsOpenCount))
            .AppendLine()

            .AppendLine("Closed Agrupations indices:")
            For Each item As KeyValuePair(Of Integer, Integer) In info.GroupsClosedPositions
                .AppendLine(String.Format("Start: {0}, End: {1}", CStr(item.Key), CStr(item.Value)))
            Next item
            .AppendLine()

            .AppendLine(String.Format("Opened Agrupations indices: {0}",
                                      String.Join(", ", info.GroupsOpenPositions)))

        End With

        MessageBox.Show(sb.ToString(), "Agrupations Information",
                        MessageBoxButtons.OK, MessageBoxIcon.Information)

    Next str

End Sub
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />