# ListBoxExtensions.RemoveDuplicates(*T*) Method (ListBox, IEqualityComparer(*T*))
 

Removes duplicated items of the specified Type in the source ListBox.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void RemoveDuplicates<T>(
	this ListBox sender,
	IEqualityComparer<T> comparer
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub RemoveDuplicates(Of T) ( 
	sender As ListBox,
	comparer As IEqualityComparer(Of T)
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As ListBox
Dim comparer As IEqualityComparer(Of T)

sender.RemoveDuplicates(comparer)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static void RemoveDuplicates(
	ListBox^ sender, 
	IEqualityComparer<T>^ comparer
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member RemoveDuplicates : 
        sender : ListBox * 
        comparer : IEqualityComparer<'T> -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.ListBox<br />The source ListBox.</dd><dt>comparer</dt><dd>Type: System.Collections.Generic.IEqualityComparer(*T*)<br />A IEqualityComparer(T) to use when comparing values in the source ListBox.ObjectCollection.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The <a href="N_DevCase_Core_Extensions_Type">DevCase.Core.Extensions.Type</a> of items to remove.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListBox. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
ListBox1.Items.AddRange({"1", "1", "1"})
ListBox1.RemoveDuplicatedItems(Of String)(StringComparer.OrdinalIgnoreCase)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_ListBox_ListBoxExtensions_RemoveDuplicates">RemoveDuplicates Overload</a><br /><a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox Namespace</a><br />