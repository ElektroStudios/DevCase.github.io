# StringExtensions.ToTreeString Method 
 

Transforms an array of string into a string with tree formatting.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ToTreeString(
	this IEnumerable<string> collection,
	bool decorate = false
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToTreeString ( 
	collection As IEnumerable(Of String),
	Optional decorate As Boolean = false
) As String
```

**VB Usage**<br />
``` VB Usage
Dim collection As IEnumerable(Of String)
Dim decorate As Boolean
Dim returnValue As String

returnValue = collection.ToTreeString(decorate)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ToTreeString(
	IEnumerable<String^>^ collection, 
	bool decorate = false
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToTreeString : 
        collection : IEnumerable<string> * 
        ?decorate : bool 
(* Defaults:
        let _decorate = defaultArg decorate false
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>collection</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The source collection.</dd><dt>decorate (Optional)</dt><dd>Type: System.Boolean<br />A value that indicates whether or not to replace tabulation characters with ASCII tree decoration characters. 

 An example of the transformation applied when *decorate* is `true` (`True` in Visual Basic): 

 " Node" -> "└───Node" 

 Default value is `false` (`False` in Visual Basic).</dd></dl>

#### Return Value
Type: String<br />The resulting string with tree formatting.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(String). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim collection As String() = {"First", "Second", "Third", "Fourth", "Fifth"}
Dim treeString As String = ToTreeString(collection, decorate:=True)

Debug.WriteLine(treeString)

' Resulting output string (with decoration):
'
' First
' └───Second
'     └───Third
'         └───Fourth
'             └───Fifth
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />