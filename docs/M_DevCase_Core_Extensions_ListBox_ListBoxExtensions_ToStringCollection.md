# ListBoxExtensions.ToStringCollection Method 
 

Converts the specified a ListBox.ObjectCollection to a StringCollection.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static StringCollection ToStringCollection(
	this ListBox.ObjectCollection sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToStringCollection ( 
	sender As ListBox.ObjectCollection
) As StringCollection
```

**VB Usage**<br />
``` VB Usage
Dim sender As ListBox.ObjectCollection
Dim returnValue As StringCollection

returnValue = sender.ToStringCollection()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static StringCollection^ ToStringCollection(
	ListBox.ObjectCollection^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToStringCollection : 
        sender : ListBox.ObjectCollection -> StringCollection 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.ListBox.ObjectCollection<br />The source ListBox.ObjectCollection.</dd></dl>

#### Return Value
Type: StringCollection<br />The resulting StringCollection.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListBox.ObjectCollection. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox Namespace</a><br />