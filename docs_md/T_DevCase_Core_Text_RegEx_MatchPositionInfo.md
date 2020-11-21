# MatchPositionInfo Structure
 

Encapsulates a text value captured by a RegEx, with its start/end position index.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_RegEx">DevCase.Core.Text.RegEx</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("MatchPositionInfo")]
public struct MatchPositionInfo
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("MatchPositionInfo")>
Public Structure MatchPositionInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As MatchPositionInfo
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"MatchPositionInfo")]
public value class MatchPositionInfo
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("MatchPositionInfo")>]
type MatchPositionInfo =  struct end
```

The MatchPositionInfo type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_RegEx_MatchPositionInfo__ctor">MatchPositionInfo</a></td><td>
Initializes a new instance of the MatchPositionInfo structure.</td></tr></table>&nbsp;
<a href="#matchpositioninfo-structure">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_RegEx_MatchPositionInfo_EndIndex">EndIndex</a></td><td>
Gets the end index.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_RegEx_MatchPositionInfo_Length">Length</a></td><td>
Gets the matched text length.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_RegEx_MatchPositionInfo_StartIndex">StartIndex</a></td><td>
Gets the start index.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_RegEx_MatchPositionInfo_Text">Text</a></td><td>
Gets the text value.</td></tr></table>&nbsp;
<a href="#matchpositioninfo-structure">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#matchpositioninfo-structure">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Sub Test()

    Dim regExpr As New Regex("Dog(s)?", RegexOptions.IgnoreCase)

    Dim text As String = "One Dog!, Two Dogs!, three Dogs!"
    RichTextBox1.Text = text

    Dim matchesPos As IEnumerable(Of MatchPositionInfo) = GetMatchesPositions(regExpr, text, groupIndex:=0)

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
<a href="N_DevCase_Core_Text_RegEx">DevCase.Core.Text.RegEx Namespace</a><br />