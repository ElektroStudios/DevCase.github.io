# ListViewExtensions.Serialize Method 
 

Serializes the items of the ListView to a binary local file. 

 You can use this method to backup the contents of a ListView, then restore them with the <a href="M_DevCase_Core_Extensions_ListView_ListViewExtensions_Deserialize">Deserialize(ListView, String)</a> method.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListView">DevCase.Core.Extensions.ListView</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void Serialize(
	this ListView sender,
	string filepath
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub Serialize ( 
	sender As ListView,
	filepath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As ListView
Dim filepath As String

sender.Serialize(filepath)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void Serialize(
	ListView^ sender, 
	String^ filepath
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Serialize : 
        sender : ListView * 
        filepath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.ListView<br />The source ListView.</dd><dt>filepath</dt><dd>Type: System.String<br />The target file.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_ListView">DevCase.Core.Extensions.ListView Namespace</a><br />