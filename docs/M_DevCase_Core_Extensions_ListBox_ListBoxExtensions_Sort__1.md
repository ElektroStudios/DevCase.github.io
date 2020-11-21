# ListBoxExtensions.Sort(*T*) Method (ListBox)
 

Sorts the items in the ListBox.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void Sort<T>(
	this ListBox sender
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub Sort(Of T) ( 
	sender As ListBox
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As ListBox

sender.Sort()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static void Sort(
	ListBox^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Sort : 
        sender : ListBox -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.ListBox<br />The source ListBox.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Extensions.ListBox.ListBoxExtensions.Sort``1(System.Windows.Forms.ListBox)"\]</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListBox. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_ListBox_ListBoxExtensions_Sort">Sort Overload</a><br /><a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox Namespace</a><br />