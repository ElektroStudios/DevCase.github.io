# IEnumerableExtensions.ToTreeString(*T*) Method 
 

Transforms an array of string into a string with tree formatting.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ToTreeString<T>(
	this IEnumerable<T> collection,
	Func<T, string> selector,
	bool decorate = false
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToTreeString(Of T) ( 
	collection As IEnumerable(Of T),
	selector As Func(Of T, String),
	Optional decorate As Boolean = false
) As String
```

**VB Usage**<br />
``` VB Usage
Dim collection As IEnumerable(Of T)
Dim selector As Func(Of T, String)
Dim decorate As Boolean
Dim returnValue As String

returnValue = collection.ToTreeString(selector, 
	decorate)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static String^ ToTreeString(
	IEnumerable<T>^ collection, 
	Func<T, String^>^ selector, 
	bool decorate = false
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToTreeString : 
        collection : IEnumerable<'T> * 
        selector : Func<'T, string> * 
        ?decorate : bool 
(* Defaults:
        let _decorate = defaultArg decorate false
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>collection</dt><dd>Type: System.Collections.Generic.IEnumerable(*T*)<br />The source collection.</dd><dt>selector</dt><dd>Type: System.Func(*T*, String)<br />A transform function to apply to each source element.</dd><dt>decorate (Optional)</dt><dd>Type: System.Boolean<br />A value that indicates whether or not to replace tabulation characters with ASCII tree decoration characters. 

 An example of the transformation applied when *decorate* is `true` (`True` in Visual Basic): 

 " Node" -> "└───Node" 

 Default value is `false` (`False` in Visual Basic).</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of *collection*.</dd></dl>

#### Return Value
Type: String<br />The resulting string with tree formatting.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim collection As Guid() = {Guid.NewGuid(), Guid.NewGuid(), Guid.NewGuid(), Guid.NewGuid(), Guid.NewGuid()}
Dim treeString As String = ToTreeString(Of Guid)(collection, Function(guid As Guid) guid.ToString().ToUpper(), decorate:=True)

Debug.WriteLine(treeString)

' Resulting output string (with decoration):
'
' 6C0A2C2E-B968-466E-B4A4-D401E790CBE3
' └───F8EE007E-E814-4EA9-B090-DBBFD0C56DA6
'     └───BD3A3DF8-F9AA-4FC2-8AD6-C24C960B3654
'         └───EE32FA3B-AF5B-46E4-9059-E3C821B6E80B
'             └───CB3983B8-E831-4DD8-9697-2554F44256A5
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable Namespace</a><br />