# ListBoxExtensions.AsIEnumerable Method (ListBox.SelectedObjectCollection)
 

Converts the specified a ListBox.SelectedObjectCollection to a IEnumerable(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<Object> AsIEnumerable(
	this ListBox.SelectedObjectCollection sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function AsIEnumerable ( 
	sender As ListBox.SelectedObjectCollection
) As IEnumerable(Of Object)
```

**VB Usage**<br />
``` VB Usage
Dim sender As ListBox.SelectedObjectCollection
Dim returnValue As IEnumerable(Of Object)

returnValue = sender.AsIEnumerable()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IEnumerable<Object^>^ AsIEnumerable(
	ListBox.SelectedObjectCollection^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AsIEnumerable : 
        sender : ListBox.SelectedObjectCollection -> IEnumerable<Object> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.ListBox.SelectedObjectCollection<br />The source ListBox.SelectedObjectCollection.</dd></dl>

#### Return Value
Type: IEnumerable(Object)<br />The resulting IEnumerable(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListBox.SelectedObjectCollection. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_ListBox_ListBoxExtensions_AsIEnumerable">AsIEnumerable Overload</a><br /><a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox Namespace</a><br />